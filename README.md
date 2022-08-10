![image](https://img.shields.io/badge/Version-0.0.0-red)
![image](https://img.shields.io/badge/license-MIT-green)

<img src="https://cdn.discordapp.com/attachments/936652528966320168/1006971462244110457/Zirgon_Logo_Transparent_Dark.png" width="400" height="200">


# About Zirgon
**!WARNING!**: This is a small overview of the prgramming language, its nt released yet.

Zirgon is a simple to write, line ignoring and interpreted language inspired by **swift**, **rust** and **c#**. its made in ``c++`` and a few open surce libraries. also it has a rich list of packages from the built in package installer you can use for free.

#### Some useful links:
- 🌐 Zirgon website: `not up yet`
- 🌐 My website: https://www.xarisdev.com/
- 💿 Wiki page: https://github.com/vp10gr/podzol/wiki
- 🔍 Source code: `not up yet`
- 🧶 License: https://github.com/vp10gr/podzol/blob/main/license

 

# Examples 
### Some important things to know:
- All podzol programs start with ``.zgn``
- To use certain libraries, you need to use "``implement "<namespace>";``"
- "``global``" means public and by default all variablers and methods are private
- To make singleline comments you use "``#Comment``" or "``//Comment``"
- To make multiline comments you use "``/*Comment*/``" or "``##Comment##``"
- the "``die;``" block kills the program
- using this diagram "``msgbx("<Text>", "<Title>", <Error/Info/Warn>);``" you can create messagebxes like this: https://imgur.com/a/XxfUIIg
- you can specify if you a part of your code to run on release or debug using this: "``on(debug/release) { <code>; }``" 

*More info is coming soon, when I got more stuff done.*

### Hello World

```swift
implement "<org.zgn.standard>";
namespace "hello";

global func main() {
    displayline("Hello, world");
}
```

### Hello, "yourname"

```swift
implement "<org.zgn.standard>";
namespace "hello";

global func main() {
    string name = getline("Enter your name: ");
    int age = getline("How old are you?: ");
    displayline($"Hello, {name}. you are {age} years old!");
}

```

---
© 2022 XarisDev
