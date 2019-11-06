WebViewJavascriptBridge
=======================

Installation (iOS)
------------------------

### Installation with CocoaPods
Add this to your [podfile](https://guides.cocoapods.org/using/getting-started.html) and run `pod install` to install:

```ruby
pod 'WebViewJavascriptBridge', '~> 6.0'
```

### Manual installation

Drag the `WebViewJavascriptBridge` folder into your project.

In the dialog that appears, uncheck "Copy items into destination group's folder" and select "Create groups for any folders".


Usage
-----

1) Import the header file and declare an ivar property:

```objc
#import "WKWebViewJavascriptBridge.h"
```

...

```objc
@property WKWebViewJavascriptBridge* bridge;
```

2) Instantiate WKWebViewJavascriptBridge with a WKWebView

```objc
self.bridge = [WKWebViewJavascriptBridge bridgeForWebView:webView];
```
