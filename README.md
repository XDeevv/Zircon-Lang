![image](https://img.shields.io/badge/Version-0.0.0-red)
![image](https://img.shields.io/badge/license-MIT-green)

<p align="center"><img src="https://cdn.discordapp.com/attachments/936652528966320168/1007262058766667796/Zircon_Logo_Transparent_Dark.png" width="420" height="200"></p>


# About Zircon
> **Warning**: This is a small overview of the programming language and its not released yet.

Zircon is a simple to write, line ignoring and interpreted language inspired by **swift**, **rust** and **c#**. its made in ``c++`` and a few open surce libraries. also it has a rich list of packages from the built in package installer you can use for free.
- **Current addition**: **[Added grammar file](https://github.com/vp10gr/Zircon-Lang/blob/main/Grammar/zircon_grammar.txt)**, **Changed license to apache v2**
- **Currently working on**: **``VSCode snippets``**

#### Some useful links:
- 🌐 Zircon website: `not up yet`
- 📦 Package installer: `not up yet`
- 🌐 My website: [Click here](https://www.xarisdev.com/)
- 💿 Wiki page: [Click here](https://github.com/vp10gr/podzol/wiki)
- 🔍 Source code: `not up yet`
- 🧶 License: [Click here](https://github.com/vp10gr/podzol/blob/main/license)
- 🌐 Official github repository [Click here](https://github.com/vp10gr/Zircon-Lang/)
- 🔌 Official vscode extension pack: `not up yet`

# Examples 
### Some important things to know:
- All Zircon programs start with ``.zc``
- To use certain libraries, you need to use "``implement "<namespace>";``"
- "``global``" means public and by default all variablers and methods are private
- To make singleline comments you use "``#Comment``" or "``//Comment``"
- To make multiline comments you use "``/*Comment*/``" or "``##Comment##``"
- the "``die;``" block kills the program
- using this diagram "``msgbx("<Text>", "<Title>", <Error/Info/Warn>);``" you can create messageboxes like [this](https://imgur.com/a/XxfUIIg) 
- you can specify if you a part of your code to run on release or debug using this: "``on(debug/release) { <code>; }``", **Changed license to apache v2**

*More info is coming soon, when I got more stuff done.*

### Hello World

```swift
implement "<org.zc.standard>";
namespace "hello";

global func main() {
    displayline("Hello, world");
}
```

### Hello, "yourname"

```swift
implement "<org.zc.standard>";
namespace "hello";

global func main() {
    string name = getline("Enter your name: ");
    int age = getline("How old are you?: ");
    displayline($"Hello, {name}. you are {age} years old!");
}

```

---
© 2022 XarisDev
