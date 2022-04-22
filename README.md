# OtpView-SwiftUI
Otp view swift package implemented with Swift &amp; SwiftUI.

![](Simulator%20Screen%20Recording%20-%20iPhone%2013%20-%202022-04-22%20at%2015.27.30.gif)


## How to use

**Create an instance

It supports AutoLayout completely.

```swift
@State var otpCode: String = ""
@State var otpCodeLength: Int = 6
@State var textColor = .black
@State var textSize = CGFloat(27)

var body: some View {
    HStack {
        //OTPTextField { otp, completionHandler in }
        OtpView_SwiftUI(otpCode: $otpCode, otpCodeLengh: $otpCodeLength, textColor: $textColor, textSize: $textSize)
    }
}
```

## Requirements

iOS 15.0+ Swift 5.5+

## Installation

- Supports following:
  - Swift Package Manager
