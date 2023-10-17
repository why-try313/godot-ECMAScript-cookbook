<p align="center">
    <br><br>
    <img height="152" src="https://github.com/why-try313/godot-ECMAScript-cookbook/blob/master/wiki-images/godotJS-logo-128.png" alt="Godot JS">
    <br><br>
</p>

<br>

# Godot ECMAScript Manual

A wiki repo on how to use [Geequlim's ECMAScript Godot Module](https://github.com/Geequlim/ECMAScript)

Head to the [Wiki tab](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki) to get more information

If you'd like an alternative source of documentation you can head to the github page of this project:<br>
[🏷️ Alpha: https://geequlim.github.io/ECMAScript/](https://geequlim.github.io/ECMAScript/)

<br>

## Contents

- <b>3.5 ‐ 01 Getting started</b>
  - [Description](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-01-Getting-started#description)
  - [Syntax](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-01-Getting-started#syntax)
  - [Using _ready, _process and _physics_process](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-01-Getting-started#using-_ready-_process-and-_physics_process)
  - [Using get_node, add_child and other tree management methods](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-01-Getting-started#using-get_node-add_child-and-other-tree-management-methods)
    - [Using call_deferred when get_node in _ready is not working](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-01-Getting-started#using-call_deferred-when-get_node-in-_ready-is-not-working)
  - [Understanding this and godot keywords](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-01-Getting-started#understanding-this-and-godot-keywords)
    - [this keyword](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-01-Getting-started#this-keyword)
    - [godot keyword](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-01-Getting-started#godot-keyword)
- <b>3.5 ‐ 02 Creating Elements</b>
  - [Description](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-02-Creating-Elements#description)
  - [Syntax](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-02-Creating-Elements#syntax)
  - [How to use it with examples](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-02-Creating-Elements#how-to-use-it-with-examples)
  - [Advanced use](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-02-Creating-Elements#advanced-use)
    - [Full list of new godot.TYPE](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-02-Creating-Elements#full-list-of-new-godottype)
- <b>3.5 ‐ 03 Property variables and hints</b>
  - [Description](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-03-Property-variables-and-hints#description)
  - [Syntax](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-03-Property-variables-and-hints#syntax)
  - [Type and Hints](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-03-Property-variables-and-hints#type-and-hints)
    - [godot Core Types](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-03-Property-variables-and-hints#godot-core-types)
    - [godot PropertyHint and arguments](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-03-Property-variables-and-hints#godot-propertyhint-and-arguments)
  - [How to use it with examples](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-03-Property-variables-and-hints#how-to-use-it-with-examples)
    - [Export a float](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-03-Property-variables-and-hints#export-a-float)
    - [Export a float in range](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-03-Property-variables-and-hints#export-a-float-in-range)
    - [Export a NodePath](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-03-Property-variables-and-hints#export-a-nodepath)
    - [Export a FilePath](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-03-Property-variables-and-hints#export-a-filepath)
  - [Advanced use](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-03-Property-variables-and-hints#advanced-use)
- <b>3.5 ‐ 04 Signals</b>
  - [Description](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-04-Signals#description)
  - [Syntax](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-04-Signals#syntax)
  - [How to use it with examples](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-04-Signals#how-to-use-it-with-examples)
    - [Connecting to current node's signal](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-04-Signals#connecting-to-current-nodes-signal)
    - [Connecting to another node's signal](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-04-Signals#connecting-to-another-nodes-signal)
    - [Triggering a method and passing optional arguments](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-04-Signals#triggering-a-method-and-passing-optional-arguments)
    - [Registering and emitting custom signals](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-04-Signals#registering-and-emitting-custom-signals)
  - [Advanced use](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-04-Signals#advanced-use)
- <b>3.5 ‐ 05 Importing modules</b>
  - [Description](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-05-Importing-modules#description)
  - [Syntax](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-05-Importing-modules#syntax)
  - [How to use it with examples](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-05-Importing-modules#how-to-use-it-with-examples)
  - [Do's and dont's](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-05-Importing-modules#dos-and-donts)
- <b>3.5 ‐ 06 Tooled scripts</b>
  - [Description](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-06-Tooled-scripts#description)
  - [Syntax](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-06-Tooled-scripts#syntax)
  - [How to use it with examples](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-06-Tooled-scripts#how-to-use-it-with-examples)
  - [Hot-reload is not supported (for now)](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-06-Tooled-scripts#hot-reload-is-not-supported-for-now)
- <b>3.5 ‐ 07 Singletons</b>
  - [Description](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-07-Singletons#description)
  - [Syntax](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-07-Singletons#syntax)
  - [How to use it with examples](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-07-Singletons#how-to-use-it-with-examples)
    - [The get_node method](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-07-Singletons#the-get_node-method)
    - [The self-referenced method with import](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/3.5-%E2%80%90-07-Singletons#the-self-referenced-method-with-import)
- [Q&A](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/Q&A)
  - [How to duplicate an object without its attached script?](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/Q&A#how-to-duplicate-an-object-without-its-attached-script)
  - [How to set a material to all children of an object?](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/Q&A#how-to-set-a-material-to-all-children-of-an-object)
  - [How to export a curve?](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki/Q&A#how-to-export-a-curve)
<br><br>

> Page missing?<br>
> Noticed a typo?<br>
> Confusing content?<br>
> Feel free to open an  [🔗 issue](https://github.com/why-try313/godot-ECMAScript-cookbook/issues) and I'll fix it as soon as possible! 
