## Notes on some basic Python syntax, coding styles

For private methods, coding convention is to keep an underscore before the method name. Using double underscores makes the use of the method by others more difficult.

```Python

_myPrivateMethod()

__superPrivateMethod()


```

Any whole number is an *integer* e.g 1 is a whole number, 1.0 is a floating point. **integers are represented by int data type. –9,223,372,036,854,775,808 and 9,223,372,036,854,775,807 range is any number for int in 64 bit variable.**

**float data type** The maximum value that a floating‐point variable
can contain is **±1.7976931348623157 × 10308** and the minimum value that a floating point variable can contain is **±2.2250738585072014 × 10‐308 on most platforms**

**complex number** consists of a real number and an imaginary number that are paired together. The **imaginary number always appears with the j after it**

```Python

myComplexNumber = 4 + 5j


```

**logical operators require Boolean values** using the **bool** type. A variable of this type has only two values, True or False. e.g. 

```Python

myBool = 1 > 2 //false

```

Operator :

= Assigns value found in the right operand to the left operand

+= Adds the value found in the right operand to the value found in the left operand and places the result in the left operant e.g. myVar += 2, will mean 


## Strings 

Strings are a data type is simply any grouping of characters you place within double quotes.

```Python

meString = "Pythons are cool" 

```

All this does is assigns a string of characters to meString

The machine sees the character stored in memory A would be 65. To see if the value in the terminal type ord("A")
You may be able to pass any single letter to the ord() function.

converting strings to integers myInt = int() function, inversely myStr = str(123.45)


```Python

# simple operators

in  # Determines whether the value in the left operand appears in the sequence found in the right operand

not in  # Determines whether the value in the left operand is missing from the sequence found in the right operand

is # type(2) is int is True

is not # type(2) is not int is False

# is evaluates to true when the type of the value or expression in the right operand points to the same type in the left operand

# is not Evaluates to true when the type of the value or expression in the right operand points to a different type than the value or expression in the left operand

```

```Python

import datetime

str(datetime.datetime.now().date())

```

Just a high level definition of a function 

**The caller supplies information to the function (arguments, or params) and the function processes that information(data)
and returns a value**

	Reduce development time

	Reduce programming error

	Increase application reliability

	Allow entire groups to benefit from the work of one programmer

	Make code easier to understand

	Improve application efficiency


A function can require a caller to provide an argument. The argument is a variable that must contain data to work.

```Python

	def funcSum( Value1, Value2 ):
		return Value1 + Value2 

```

@note [01]

## Positional arguments means that we have supplied values in the order in which they appear in the argument list for the function definition, left to right

## In Python you will be able to send arguments by keyword. This way you supply the name of the argument followed by an equal sign and the argument value

e.g.

```Python

def DisplayValueSum( Value1, Value2 ):
	print(str (Value1) + ' + ' + str(Value2) + ' = ' + 
	str((Value1 + Value2)))

```



