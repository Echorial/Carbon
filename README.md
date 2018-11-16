# Carbon programming language
[**Homepage**](https://www.echorial.com/carbon)

A clean c++/c# like language that transpiles to Javascript, PHP, C++ and more, while maintaining native performance.

## Specification
Specs should come soon ( [Before Carbonite 1.0](https://github.com/Echorial/carbonite/milestone/1) ) and will be hosted in this repo.

## Example
``` csharp
class App {
    int start(<string>array args) {
        let msg = ["Hello", "world!"];
        
        Console.log(msg.join(" "));
        
        return 0;
    }
}
```

## Projects built with carbon
* [Carbonite](https://github.com/Echorial/carbonite) *Carbon compiler written in carbon.*
* [Websom](https://github.com/Echorial/websom) *Web framework that runs on Node.js and PHP*
* [Carpeg](https://github.com/Echorial/carpeg) *Small [PEG](https://en.wikipedia.org/wiki/Parsing_expression_grammar) based parser generator.*
* Add to this list by opening an issue.
