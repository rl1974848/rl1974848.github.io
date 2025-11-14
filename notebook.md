# My Coding Notebook

## Table of Contents
- [Flutter Notes](#flutter-notes)
  - [What is Flutter](#what-is-flutter)
  - [Key Terms And Definitions](#key-terms-and-definitions)
  - [Layout and design Widgets](layout-and-deisgn-widgets)
  - [Definitions With Structures](#flutter_definitions-with-structures)
- [Day 2](#day-2)
- [Notebook Style Guide](#markdown-style-guide-for-coding-notebooks)



## Flutter Notes

### What is Flutter?
- Definition: A framework made my google for building apps that work on web, Android, and iOS- with one code base
- Why is it useful?

---

### Key Terms and Definitions

| Term             | Definition                                      | Example / Notes                          |
|------------------|--------------------------------------------------|-------------------------------------------|
| Widget           |        Basic block of a Flutter app. Everything is a widget.                                          | Text, image, container,column                                          |
| MaterialApp      |        The root of the app. Sets up routes and themes.                                          | Found in main. dart                                          |
| Scaffold         |        provides basic visual layout-like a header, body, floating button                                          |                                           |
| StatelessWidget  |        A widget that doesnt change                                          |                                           |
| StatefulWidget   |        A widget that can change over time                                          |                                           |
| Navigator        |        Manages screen transtions                                          |                                           |
| AppBar           |        Top navigation bar                                          |                                           |
| Column           |        vertical layout                                          |                                           |
| Row              |        horizontal layout          |                                           |
| Container        |        wraps content with padding, margin, or color                                         |                                           |
| Text             |        displays text                                          |                                           |
| Image.network    |        displays images from a URL                                          |                                           |



---

### Layout and Design Widgets
- How do you center a widget?
- How do you align something to the left or right?
- What widget adds space around content?

## Flutter Definitions With structures

| Term | Definition and Description | Base Structure | Real Life Example | App Example |
|------|----------------------------|----------------|-------------------|-------------|
|  main    | A function that runs when your app starts. It tells Flutter what app to show. | `void main() => runApp(MyApp());` |  |in main dart, void main() => runApp(MyPortfolioApp());  |
|  MaterialApp    | The widget that sets up your whole app’s look and navigation. | `MaterialApp(...)` |  |return MaterialApp( debugShowCheckedModeBanner: false, title: 'TSA Portfolio',theme: ThemeData(|
|  scaffold    | A widget that gives you the basic layout: background, navigation bar, floating button, etc. | `Scaffold(...)` |  |in showcase.dart, return Scaffold(body: Column( mainAxisAlignment:MainAxisAlignment.start, children: [  |
|  columm    | A widget that holds and displays your content in a straight line from top to bottom. | `Column(...)` |  |  |
|  Row    | A widget that shows things side-by-side. | `Row(...)` |  |  |
|  Container    | A box that holds other widgets. You can add color, padding, borders, or size. | `Container(...)` |  |  |
|  text    | A widget to display text on the screen. | `Text('Hello')` |  |  |
|  image.network    | A widget to show an image using a link from the internet. | `Image.network('https://...')` |  |  |
|  elevatedbutton    | A clickable button that floats above content. You choose what happens when it's clicked. | `ElevatedButton(onPressed: ..., child: ...)` |  |  |
|  onPressed    | The code that gets run when a button is tapped or something happens. | `onPressed: () => doSomething()` |  |  |
|  statelesswidget    | A class that creates widgets that never change. Good for static screens. | `class HomeScreen extends StatelessWidget` |  |  |
|  statefulwidget    | A class for widgets that can change while the app is running. | `class MyWidget extends StatefulWidget` |  |  |
|  navigator    | Lets you move from one screen to another using route names. | `Navigator.pushNamed(context, '/about')` |  |  |
|  padding    | Makes space around a widget inside its container. | `Padding(padding: EdgeInsets.all(8.0), child: ...)` |  |  |
|  center    | Aligns content in the center of the screen or container. | `Center(child: ...)` |  |  |
|  wrap    | Automatically puts widgets onto a new line when there's no space. | `Wrap(children: [...])` |  |  |
|  @override    | This marks a method as one that’s replacing a method in a parent class. | `@override` |  |  |
|  build    | The special function in every widget that describes what gets drawn on the screen. | `Widget build(BuildContext context) {...}` |  |  |
|  build    | Required in every widget class to describe what to show. | `build` |  |  |
|  buildcontext    | A variable that helps the widget know where it is and lets it communicate with the app. | `BuildContext context` |  |  |
|  superkey    | A keyword used to pass a value to the parent widget. | `super.key` |  |  |
|  const    | A keyword that means the value won't change and is set once. | `const` |  |  |

 [Code Definitions](#code-definitions)

| Term | Definition | Base Structure / Syntax | Real Life Example | App Example |
|------|------------|--------------------------|-------------------|-------------|
|   variable   | A named container used to store a value that may change. | `var x = 5;` | height is 4,9 |  |
|  constant    | A fixed value that cannot change once set. | `const PI = 3.14;` | logo |  |
|   data type   | The kind of value a variable holds, like numbers or text. | `int`, `String`, `bool` | number vs fabric |  |
|   string   | A sequence of characters used to represent words or text. | `"Hello World"` |filtering spam emails  |  |
|   integer   | Whole number values. | `int age = 16;` |a team/sports score  |  |
|   double   | Number values with decimals. | `double age = 16.2;` | math for data analysis |  |
|  boolean    | A value that can be true or false. | `bool isLoggedIn = false;` | online forms that check for verification/ valid imput |  |
|  list    | A collection of values in a specific order. | `List<String> names = [];` |information on user  |  |
|   null   | A special value that means “nothing.” | `String? name = null;` |a loading level  |  |
|   function   | A reusable block of code that performs an action. | `void sayHi() { print("Hi"); }` |buisness software  |  |
|  parameter    | The information passed into a function to change how it works. | `greet(String name)` | video game charactors cusomization  |  |
|  return    | The result a function gives back. | `return total;` |smart devices  |  |
|  scope    | Where a variable or function can be used. | (No set syntax — concept-based) | cyber security  |  |
|   class   | Blueprint for creating objects with specific structure and behavior. | `class Dog {}` | template for creativity |  |
|  object    | A specific version of a class. | `Dog myDog = Dog();` |a type of car  |  |
|  property    | A variable that belongs to a class/object. | `String name;` |screen size  |  |
|   method   | A function that belongs to a class. | `void bark() {}` |a traffic light  |  |
|   constructor   | A special function used to set up a class when it’s created. | `Dog(this.name);` | meals that are pre-packeged  |  |
|   abstraction   | Hiding the inner workings of code so users only interact with what they need. | (Concept — not specific code) | a remote control |  |
|   override   | Changing how a built-in or inherited function behaves. | `@override` |a circle and rectangle  |  |
|    void  | A function that does not return a value. | `void printMessage() {}` | " print this document" or" turn on the light" |  |
|scanner|creates a scanner object to take input from user|Scanner in = new Scanner (System.in);|||
|import scanner|Gives access to Scanner class, reqired at top|import java.util.scanner; |||
|print line statement|prints whats in the parethesis, adds line after||||
|print statement|prints the content in the parenthesis||||
|input nextLine|reads in a string from the user||||
|input nextInt|reads in an int from the user||||
|input nextDouble|reads in a double (decimal) from the user||||
|input nextBoolean|reads in a boolean (true/false) from the user||||
|arithmetic operators|  -  *  /  % (modulus, returns the remainder||||
|compound operators|||||
|maximum int|the max value an int can hold: 2147483647|integer.MAX_VALUME|||
|minimum int|the minimum value an int can hold: -2147483648|integer.MIN_VALUE|||
|integer overFlow|integer.MAX_VALUE + 1 == MIN_VALUE, it wraps around||||
|integer underflow||||
|round-off error|||||
|overloaded method/function or constructor |uses the same name, but has different parameters |pizza(), pizza (string toppings) 2 constructors, first is a default cheese pizza, 2nd has 1 topping|||
|dot notation |methods are called on objects using a dot after the object name|object.method(vaule);|||
|concatnate|to combine strings with other strings and/or variables|strings greeting = "Hello" + " my name is " + name". ";|||
|algorithms|define step by step processes to follow when completing a task or solving a problem |no syntax|make a grilled cheese|verify user|
|sequencing|define an order for when steps in an algorithm are completed|follows 1,2,3|which step comes first in making a grilled cheese||
|index|location value of each charactor  in a string or list, starting at 0 |"hello" index of 'e' is 1|||
|substring | part of a larger string | "llo" is a substring of "hello"|||


[string notes](#string-notes)
### string notes
 -strings have indices (plural for index,)

 
<img width="856" height="422" alt="image" src="https://github.com/user-attachments/assets/f7b4d7f6-2adf-4072-bb02-a1215642e36d" />


## Markdown Style Guide for Coding Notebooks

Follow this guide to keep your coding notebook **clear, consistent, and professional**.  
This ensures your notes are easy for you (and others) to read later.

---

## 🔹 Headings
**When to use:** Organize your notebook into sections (like days, topics, or projects).  
- `#` for the notebook title (use once at the top).  
- `##` for each day or major topic.  
- `###` for subsections (like "Notes", "Practice", "Reflections").  

✅ Example:


# My Coding Notebook
## Day 1
### Notes
### Practice

🔡 Text Formatting
When to use: Highlight important ideas or add emphasis.

Use bold for key terms or definitions.

Use italic for emphasis or side comments.

Use inline code for keywords, functions, or commands.

 

✅ Example:

**Class** = a blueprint for objects  
*Remember:* always test your code  
Use `System.out.println()` to print

 

💻 Code Blocks
When to use: Anytime you write multiple lines of code.

Inline code for short snippets.

Fenced code blocks with language for full examples.

✅ Example:

```java
public class Hello {
    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}
```

🧾 Lists
When to use: Organize steps, notes, or key points.

Numbered lists for sequences or steps.

Bulleted lists for unordered ideas.

✅ Example:

1. Define the class
2. Write the main method
3. Test your program

Variables
- Loops
- Conditionals
 

✅ Checklists
When to use: Track progress on assignments or tasks.

✅ Example:

[x] Complete coding warm-up
- [ ] Finish project draft
- [ ] Reflect on learning

 

➡️ Blockquotes
When to use: Call out notes, reminders, or teacher comments.

✅ Example:

> 💡 Remember: Loops repeat code until a condition is false.

 

📊 Tables
When to use: Compare values, track progress, or organize data neatly.

✅ Example:

| Task        | Status   | Notes          |
|-------------|----------|----------------|
| Homework 1  | Done ✅  | Submitted      |
| Homework 2  | Pending  | Needs review   |

 

🔗 Links & Images
When to use: Add references, resources, or visuals.

✅ Example:

[Java Docs](https://docs.oracle.com/javase/8/docs/api/)  
![Markdown Logo](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

 

📂 Collapsible Sections
When to use: Hide solutions, extended notes, or extra details.

✅ Example:

<details>
  <summary>Click to reveal solution</summary>
  
System.out.println("Answer: 42");

</details>

 

📝 Footnotes
When to use: Add references or side notes without cluttering the page.

✅ Example:

This concept is related to object-oriented programming.[^1]

[^1]: See "Objects and Classes" in your textbook.

 

🎯 Style Rules
Consistency matters more than creativity

Always use headings to structure your notes.

Always use code blocks for multi-line code.

Clarity first

Bold key terms.

Use lists instead of long sentences when outlining steps.

Professional tone

Don’t mix casual notes with formal work in the same section.

Use blockquotes for reflections or teacher feedback.

Track your learning

Use checklists to mark what’s done.

Use collapsible sections if you want to hide answers until review time.

 

✅ Bottom Line:

Headings = Structure

Bold/Italic = Emphasis

Code blocks = Code

Lists = Steps/Ideas

Tables = Organization

Checklists = Progress

Blockquotes = Notes/Tips

Collapsible = Hide/Show detail

Keep it simple, consistent, and clear.
