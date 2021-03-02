# C-
# Lecture 1
# Console.WriteLine("Hello world"); 
prints console in a new line
# Console.Write("hello");
prints console in the same line
# comments
//Comments for single line
/* comments
for
multiple
line
*/
# c# is case sensitive


# Lecture 2
```

//String
string firstName="Bob";
Console.WriteLine(firstName);
//Char
char myFirstLetter='A';
char mySecondLetter='a';
Console.WriteLine(myFirstLetter);
Console.WriteLine(mySecondLetter);
//Int
int myScore=100;
Console.WriteLine(myScore);
Console.WriteLine(int.MaxValue);
//bool
bool isAvailable=true;
Console.WriteLine(isAvailable);

//Decimal

```

# Assignments

```
var userName="Bob";
var itemInInbox=3;
var temp=34.4;
Console.Write("Hello, ");
Console.Write(userName);
Console.Write("! You have  ");
Console.Write(itemInInbox);
Console.Write(" in your inbox. The temperature is ");
Console.Write(temp);
Console.Write("celsius");
```

# Strings
\n create a new line
\t add a tab
\"something\" used to add quotation 
Console.WriteLine("c:\\source\\repos"); =======>//c:\source\repos
```
Console.WriteLine($"{firstName} {middleName} {lastName}");
Console.WriteLine(string.Format("{0} {1} {2}", firstName, middleName, lastName));
```

# Exercise
```
Console.WriteLine("Generating invoices for customer \"ABC Corp\" ...\n");
Console.WriteLine("Invoice:\t1021\t\tComplete");
Console.WriteLine("Invoice:\t1021\t\tComplete\n");
Console.WriteLine("Output\tDirectory:");
```
```
Generating invoices for customer "ABC Corp" ...

Invoice:	1021		Complete
Invoice:	1021		Complete

Output	Directory:
```
# Verbatim String Literal
Console.WriteLine(@"   c:\source\repos   
      (this is where your code goes)");
 
 #  String Concatenation
 ```
 Console.WriteLine($@"C:\Output\{projectName}\Data");
 ```
 # Exercise
 ```
 string projectName = "ACME";

string russianMessage = "\u041f\u043e\u0441\u043c\u043e\u0442\u0440\u0435\u0442\u044c \u0440\u0443\u0441\u0441\u043a\u0438\u0439 \u0432\u044b\u0432\u043e\u0434";
Console.WriteLine(@"View English output:
		c:\Exercise\ACME\data.txt");

Console.WriteLine(russianMessage);
Console.WriteLine(@"		c:\Exercise\ACME\ru-RU\data.txt");

```
