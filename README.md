# iOS

xcrun simctl list devices | grep "(Booted)"
    iPhone 13 mini (89476DC7-CC9A-4D15-82F8-C796309371FA) (Booted) 
    iPhone 13 (32D8766E-A9FB-4620-B156-223D9EF142A0) (Booted) 
xcrun simctl spawn 89476DC7-CC9A-4D15-82F8-C796309371FA launchctl list | grep MMT
38230	0	UIKitApplication:com.Iphone.MMT[e4cd][rb-legacy]
 
