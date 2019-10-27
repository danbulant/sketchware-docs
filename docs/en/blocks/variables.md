---
title: Variables
id: variables
---

## What it is

Variable is a key-value pair. A variable is used to save data into RAM. This means, that where app is closed, variables are deleted.

## Variable types

### Boolean

*1 or 0*

Boolean is a variable that can be either true (1) or false (0). It's directly usable in if statement.

### Number

*20.35, 25, 27.5*

Number (programmatically known as Double) is a variable that can save most numbers (some are too big). It has double precision.

### String

*foo, bar, hello*

String is a variable that can save text.

### Map

*a = str, b = hello*

Map is a list of key-value pairs. Get and save data to it by keys, have same rules as variable names.

### List

*0 = hello, 1 = hi*

A list (known as array) is a variable that works as map, but instead of string as key, it uses offset number. This means, that the first value has index of 0. The last has Length - 1.

### Widgets

A widget is a variable too. A variable with the same name as id of the widget is used to save reference and to use it in blocks such as setText.

### Components

Components are saved in variable, same as widgets, they're saved to keep a reference to use it in future.

## Naming rules

A variable must have at least one character(can be either case). It must start with a character, then it can contain any number of characters, numbers or dashes.
In RegEx, it would be written as ''' [a-zA-Z][a-zA-Z1-9-]* '''

Must not be duplicate name. See [Why you can't have duplicate names](duplicate-vars.md).
