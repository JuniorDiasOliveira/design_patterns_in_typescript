# Design Patterns in TypeScript #

Here are the implementations of the following design patterns in TypeScript:

### Creational ###

* [Singleton](https://github.com/JuniorDiasOliveira/design_patterns_in_typescript/tree/master/singleton)
* [Abstract Factory](https://github.com/JuniorDiasOliveira/design_patterns_in_typescript/tree/master/abstract_factory)
* [Factory Method](https://github.com/JuniorDiasOliveira/design_patterns_in_typescript/tree/master/factory_method)
* [Builder](https://github.com/JuniorDiasOliveira/design_patterns_in_typescript/tree/master/builder)
* [Prototype](https://github.com/JuniorDiasOliveira/design_patterns_in_typescript/tree/master/prototype)


### Structural Patterns ###

* [Adapter](https://github.com/JuniorDiasOliveira/design_patterns_in_typescript/tree/master/adapter)
* [Bridge](https://github.com/JuniorDiasOliveira/design_patterns_in_typescript/tree/master/bridge)
* [Composite](https://github.com/JuniorDiasOliveira/design_patterns_in_typescript/tree/master/composite)
* [Decorator](https://github.com/JuniorDiasOliveira/design_patterns_in_typescript/tree/master/decorator)
* [Facade](https://github.com/JuniorDiasOliveira/design_patterns_in_typescript/tree/master/facade)
* [Flyweight](https://github.com/JuniorDiasOliveira/design_patterns_in_typescript/tree/master/flyweight)
* [Proxy](https://github.com/JuniorDiasOliveira/design_patterns_in_typescript/tree/master/proxy)


### Behavioral Patterns ###

* [Chain of Responsibility](https://github.com/JuniorDiasOliveira/design_patterns_in_typescript/tree/master/chain_of_responsibility)
* [Command](https://github.com/JuniorDiasOliveira/design_patterns_in_typescript/tree/master/command)
* [Interpreter](https://github.com/JuniorDiasOliveira/design_patterns_in_typescript/tree/master/interpreter)
* [Iterator](https://github.com/JuniorDiasOliveira/design_patterns_in_typescript/tree/master/iterator)
* [Mediator](https://github.com/JuniorDiasOliveira/design_patterns_in_typescript/tree/master/mediator)
* [Memento](https://github.com/JuniorDiasOliveira/design_patterns_in_typescript/tree/master/memento)
* [Observer](https://github.com/JuniorDiasOliveira/design_patterns_in_typescript/tree/master/observer)
* [State](https://github.com/JuniorDiasOliveira/design_patterns_in_typescript/tree/master/state)
* [Strategy](https://github.com/JuniorDiasOliveira/design_patterns_in_typescript/tree/master/strategy)
* [Template Method](https://github.com/JuniorDiasOliveira/design_patterns_in_typescript/tree/master/template_method)
* [Visitor](https://github.com/JuniorDiasOliveira/design_patterns_in_typescript/tree/master/visitor)

## Compile the project

```
$ git clone https://github.com/JuniorDiasOliveira/design_patterns_in_typescript.git
$ cd design_patterns_in_typescript
$ tsc
```

There is a `tsconfig.json` file in the root directory which is responsible for the compiler options.

As it is set the default target is Ecmascript5 now.

Any additional options come here.

By default the output is a `patterns.js` file.


To compile only one pattern, use the following command.

```
$ cd design_patterns_in_typescript/visitor
$ tsc --target ES5 --module system --outFile visitor.js visitor.ts
```

## Execute the project

After the compilation of the project, a `patterns.js` is generated by default.
Executing the file is:

```
node patterns.js
```
