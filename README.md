# iOSGuide
Cover different topics

iOS Topics

Swift
Design Patterns
  MVVM
  Protocol Oriented Programming
Core Data
Testing
Crashylytics/Diagnostics
Instruments
DevOps

Github
Agile

iOS Topics

Swift
Design Patterns
  	MVVM
  	Protocol Oriented Programming
Core Data
Testing
Crashylytics/Diagnostics
Instruments
DevOps

Github
Agile

<br><br>
CustomStringConvertible protocol and add description property to the object.

struct Device : CustomStringConvertible {
 var type: String
 var price: Float
 var color: String

 var description: String {
  return "Type: \(type), Price: \(price), Color: \(color)"
 }
}

Print statement will be much cleaner 😀

[Type: iPhone, Price: 799.0, Color: White, Type: iPhone, Price: 699.0, Color: Black]
