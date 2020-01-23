# Swifty-Companion

## OAuth2
* **CocoaPods:** https://cocoapods.org/pods/OAuth2-Swift
* **Github:** https://github.com/muhammadbassio/OAuth2

Basically the same instructions OAuth2 gives, just a few minor differances for the school computers

1. Install CocoaPods with brew, so the school computers allow it: `brew install cocoapods`
2. `pod init _myapp_.xcodeproj`
3. Add to Podfile:
```ruby
source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '9.0'
use_frameworks!

target '<Your Target Name>' do
    pod 'OAuth2-Swift'
end
```
4. `pod install`
5. Drag the folder "source" to your Xcode project, making sure you put it as a _group_ rather than a _file_ (folder should be yellow, not blue)
