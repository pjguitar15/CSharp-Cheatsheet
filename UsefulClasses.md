## C# Properties
> set and get simplified
```csharp
class Person
{
  private string name; // field

  public string Name   // property
  {
    get { return name; }   // get method
    set { name = value; }  // set method
  }
}

public class Main
{
  public static void Main(string[] args)
  {
      Person person = new Person("Philcob");
      // you're only gonna touch the Name property to set and get the field
      person.Name = "Josol";
      Console.WriteLine(anotherClass.Name);
  }
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

## CharAt using CSharp
> you basically just have to get the specific character with Array syntax
```csharp
  string myString = "Hello";
  Console.WriteLine(myString[0]);  // Outputs "H"
```
