![cflatats](https://user-images.githubusercontent.com/72033313/169621673-f19a3a71-08bc-43fc-9737-8b22a4ad2651.png)

# WARNING: This language is in very early stage.

CFLAT is a simple programming language, it is a hobby of mine and my first interaction with C++.
The language is not ready to be released yet, which means that I can only give examples of what it will be like.

It is heavily inspired by C# and Swift too. It will also be used as a scripting system for my game "Rigid".

# Example code
Some important things to note:
- To use certain libraries, you need to use "need" and then specify them inside of the brackets.
- "global" means public and "local means private.
- OnStart() and OnNewFrame() are special methods which run at the start and at every frame.
- To make comments you use "**"

More info is coming soon, when I got more stuff done.

## Temperature

```
depends system

global func main(input) {
    string temperatre = getinput("Whats the temperature: );
    if (temperature < 20) {
        displayline("Its cold today");
    } 
    elif (temperature > 20) {
        displayline("Its hot today");
    }
} 
```

## Hello World

```
depends system
global func main(input) {
   display("Hello, world");
}
```

