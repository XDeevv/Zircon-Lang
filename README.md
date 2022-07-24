![image](https://cdn.discordapp.com/attachments/910436116811878410/977341210228322324/textbutgray.png)
![image](https://img.shields.io/badge/Version-0.0.0-red)
![image](https://img.shields.io/badge/license-MIT-green)



# This language is not done yet and coming soon

Wsharp is an easy to use programming language, its made with c++ and enspired by swift
also it has a flexible package manager whit lots of free to use scripts

# Example codes
Some important things to know:
- To use certain libraries, you need to use "``implement "<namespace>";``"
- "``global``" means public and by default all variablers and methods are private
- To make singleline comments you use "``#Comment``" or "``//Comment``"
- To make multiline comments you use "``/*Comment*/``" or "``#-Comment-#``"
- the "``die;``" block kills the program
- using this diagram "``msgbx("<Text>", "<Title>", <Error/Info/Warn>);``" you can create messagebxes like this: https://imgur.com/a/XxfUIIg
- you can specify if you a part of your code to run on release or debug using this: "``on(debug/release) { <code>; }``" 

**More info is coming soon, when I got more stuff done.**

## Hello World

```swift
implement "<gq.pdz.standard>";
namespace "hello";

global func main() {
    displayline("Hello, world");
}
```

## Hello, <name>

```swift
implement "<gq.pdz.standard>";
namespace "hello";

global func main() {
    string name = getline("Enter your name: ");
    int age = getline("How old are you?: ");
    displayline($"Hello, {name}. you are {age} years old!");
}

```


