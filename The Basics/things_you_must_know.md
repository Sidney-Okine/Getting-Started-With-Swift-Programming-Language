
### Important things to note in Swift


```swift
//Variables in swift act as containers for values which may be in different forms such as Integer (Int) or decimals such as Float and Double {We'll get here shortly} and string values that carry the format of text and so on, whereas Constants in swift are variables that do not change upon their declaration, hence you cannot assign a new value to a constant once it has been declared already

//Let's deep dive into it
	var name = "Sidney" // name is of type String
	var age = 222 // 222 is of type Integer
	let pi = 3.14159 //3.14159 is of type Float and is set or declared a constant    
```

```swift
// Multi-variable or constant declaration is also supported in swift, example below
	var a=1, b=2, c=3
	print(a)
	print(b)
	print(c)

```
	Output:
		1
		2
		3

```swift
//Type Annotations is a practice where you set the data-type of the variable or constant without initializing it to any value
	var Greetings: String
	// the colon represents the phrase "...of type..."

	//so you can read the above line of code as : (variable Greetings is of type String, meaning that the variable can only store data of type String)
	Greetings = "Hello Sidney"
	print(Greetings)
```
	Output:
		Hello Sidney

```swift
//Floating-point Numbers are basically numbers with some sort of decimal notation or fractional component.
//Examples are 3.14159, 0.5,0.1
```
	* Float represents a 32-bit Floating point number
	* Double on the other hand represents a 64-bit Floating point number

```swift
//Numeric Literals

```

	Integer Literals can be written as:
		* A decimal number with no prefix
		* A binary number with an 0b prefix
		* An octal number with a 0o prefix
		* A hexadecimal number with the 0x prefix
