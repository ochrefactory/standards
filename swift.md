# Swift Standards

Use [The Official raywenderlich.com Swift Style Guide](https://github.com/raywenderlich/swift-style-guide)
as a starting point.

Use Cocoapods to include 3rd party libraries.

Prefer using storyboards and Interface Builder where possible.
If you need to customize more than one
object in Interface Builder
to have the same appearance,
create a class in a Components directory
that inherits from the proper UIKit class
with the custom styling/functionality incorporated.
If appropriate, include `@IBDesignable` directives
to make it possible to customize the object in Interface Builder.

Use Autolayout wherever possible,
and try to keep the scenes free of warnings and errors.

Use deprecation notices
when you want to remove code from a codebase,
but cannot take the time
to remove all references to the code yet.

Prefer structs to classes.

Prefer completion blocks over NSNotificationCenter
for asynchronous code.
