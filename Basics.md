## Basic Technical concepts
# User Input & Output

```csharp
// User Input & Output
string userName;

Console.WriteLine("Enter your name:");
userName = Console.ReadLine();

Console.WriteLine("Hello, " + userName);

string city;

Console.WriteLine("Enter your city:");
city = Console.ReadLine();

Console.WriteLine($"Welcome from {city}!");
```

# Arithmetic Operators

```csharp
// Arithmetic Operators
int a;
int b;

Console.WriteLine("Enter the value of first number");
a = int.Parse(Console.ReadLine());

Console.WriteLine("Enter the value of Second number");
b = int.Parse(Console.ReadLine());

Console.WriteLine($"{a} + {b} = {a + b}");
Console.WriteLine($"{a} - {b} = {a - b}");
Console.WriteLine($"{a} * {b} = {a * b}");
Console.WriteLine($"{a} / {b} = {a / b}");
Console.WriteLine($"{a} % {b} = {a % b}");

int x, y;

Console.WriteLine("Enter first number:");
x = Convert.ToInt32(Console.ReadLine());

Console.WriteLine("Enter second number:");
y = Convert.ToInt32(Console.ReadLine());

Console.WriteLine($"Sum = {x + y}");
Console.WriteLine($"Difference = {x - y}");
Console.WriteLine($"Product = {x * y}");
```

# Comparison Operators

```csharp
// Comparison Operators
int age = 17;
bool hasId = true;

Console.WriteLine(age >= 18);
Console.WriteLine(age == 18);
Console.WriteLine(age != 20);

Console.WriteLine(age >= 13 && age <= 19);
Console.WriteLine(age < 13 || hasId);
Console.WriteLine(!hasId);

int marks = 65;
bool isSportsQuota = false;

Console.WriteLine(marks >= 50);
Console.WriteLine(marks == 100);
Console.WriteLine(marks != 0);

Console.WriteLine(marks >= 60 && !isSportsQuota);
Console.WriteLine(marks < 40 || isSportsQuota);
```

# If Statement

```csharp
// If Statement
int number = 42;

if (number % 2 == 0)
{
    Console.WriteLine($"{number} is EVEN");
}
else
{
    Console.WriteLine($"{number} is ODD");
}

string type = (number % 2 == 0) ? "even" : "odd";
Console.WriteLine(type);

int num;

Console.WriteLine("Enter a number:");
num = int.Parse(Console.ReadLine());

if (num % 2 != 0)
{
    Console.WriteLine("Number is ODD");
}
else
{
    Console.WriteLine("Number is EVEN");
}

Console.WriteLine(num % 2 == 0 ? "Even Number" : "Odd Number");

if (condition1)
{
    // code to be executed if condition1 is true
}
else if (condition2)
{
    // code to be executed if condition2 is true
}
else if (condition3)
{
    // code to be executed if condition3 is true
}
else
{
    // code to be executed if all the conditions are false
}
```

# Switch Case

```csharp
// Switch Case
Console.Write("Enter grade letter (A/B/C/D/F): ");
string grade = Console.ReadLine().ToUpper();

switch (grade)
{
    case "A":
        Console.WriteLine("Excellent! Keep it up.");
        break;
    case "B":
        Console.WriteLine("Good work.");
        break;
    case "C":
        Console.WriteLine("Satisfactory.");
        break;
    case "D":
        Console.WriteLine("Pass – needs improvement.");
        break;
    case "F":
        Console.WriteLine("Failed. Try harder next time.");
        break;
    default:
        Console.WriteLine("Invalid grade entered.");
        break;
}

Console.Write("Enter day number (1-7): ");
int day = int.Parse(Console.ReadLine());

switch (day)
{
    case 1:
        Console.WriteLine("Monday");
        break;
    case 2:
        Console.WriteLine("Tuesday");
        break;
    case 3:
        Console.WriteLine("Wednesday");
        break;
    case 4:
        Console.WriteLine("Thursday");
        break;
    case 5:
        Console.WriteLine("Friday");
        break;
    case 6:
        Console.WriteLine("Saturday");
        break;
    case 7:
        Console.WriteLine("Sunday");
        break;
    default:
        Console.WriteLine("Invalid day number");
        break;
}
```
