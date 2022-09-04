# iOSGuide
Cover different topics

iOS Topics

- Swift
- Design Patterns
 - MVVM
 - Protocol Oriented Programming
- Core Data
- Testing
- Crashylytics/Diagnostics
- Instruments
- DevOps
- Github
- Agile

<br><br>
CustomStringConvertible protocol and add description property to the object.
```
struct Device : CustomStringConvertible {
 var type: String
 var price: Float
 var color: String

 var description: String {
  return "Type: \(type), Price: \(price), Color: \(color)"
 }
}
```
```
Print statement will be much cleaner 
[Type: iPhone, Price: 799.0, Color: White, Type: iPhone, Price: 699.0, Color: Black]
```

### Ideal way to share framework without exposing code: 
- https://help.apple.com/xcode/mac/current/#/dev6f6ac218b
- https://developer.apple.com/documentation/xcode/distributing-binary-frameworks-as-swift-packages
- https://medium.com/trueengineering/xcode-and-xcframeworks-new-format-of-packing-frameworks-ca15db2381d3
