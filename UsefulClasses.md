### VSCODE Create a C# project
```bash
dotnet new console
```

## C# Properties
> set and get simplified
```csharp
class Person {
  private string name; // field

  public string Name { // property
    get { return name; }   // get method
    set { name = value; }  // set method
  }
}

public class Main {
  public static void Main(string[] args) {
      Person person = new Person("Philcob");
      // you're only gonna touch the Name property to set and get the field
      person.Name = "Josol";
      Console.WriteLine(anotherClass.Name);
  }
}
```

## Automatic Properties
> even more simplified properties
```csharp
class Person {
  public string Name  // property
  { get; set; }
}

class Program {
  static void Main(string[] args) {
    Person myObj = new Person();
    myObj.Name = "Liam";
    Console.WriteLine(myObj.Name);
  }
}
```

## Simplified Inheritance
> no need use keywords like "extends" in Java
```csharp
// base class (parent) 
class Vehicle { 

  // Vehicle field
  public string brand = "Ford";  
  
  // Vehicle method 
  public void honk() { 
    Console.WriteLine("Tuut, tuut!");
  }
}

// derived class (child)
class Car : Vehicle {
  public string modelName = "Mustang";  // Car field
}
```

## Convert String to Integer
```csharp
  string num = "45";
  int sum = Int32.Parse(num) + 45;
```

## Take User Input
```csharp
  string name = Console.ReadLine(); 
```

## Math Object
```csharp
  Math.Max(5, 10);
  Math.Min(5, 10);  
  Math.Round(9.99);
  Math.Abs(-4.7);  
  Math.Sqrt(64);
```

## String Methods
```csharp
  string str = "Hello World";
  str.Length; // string length
  str.ToUpper(); // to uppercase
  str.ToLower(); // to lowercase
  str.Concat(str + str); // concatenate
  name.Substring(2);
  
  // indexOf
  string myString = "Hello";
  Console.WriteLine(myString.IndexOf("e"));  // Outputs "1"
  
```

## String interpolation
```csharp
  string firstName = "John";
  string lastName = "Doe";
  string name = $"My full name is: {firstName} {lastName}";
  Console.WriteLine(name);
```

## String interpolation (from class)
```csharp
  string firstName = "John";
  string lastName = "Doe";  
  Console.WriteLine("My full name is: {0} {1}", firstName, lastName);
```

## CharAt using CSharp
> you basically just have to get the specific character with Array syntax
```csharp
  string myString = "Hello";
  Console.WriteLine(myString[0]);  // Outputs "H"
```

### Arrays in C#
> arrays should be like this
```csharp
string[] myString = {"one", "two"};
```

### Two Dimentional Array
```csharp
int[ , ] x = { { 1, 2 ,3}, { 3, 4, 5 } };
```
