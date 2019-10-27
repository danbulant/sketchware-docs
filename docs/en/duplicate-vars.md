---
id: duplicate-vars
title: Why is sketchware showing that name xxx is not available
---

There are quite a few answers, actually. It's mostly because there is another variable with the same name.
But for better debugging of this project, we first need to know how *what's variable*. Even if it **sounds trivial**, it **isn't**.

## What's variable

A variable can be multiple things:
- Literal variable. These are created in logic editor by clicking *Add variable* in *variable* tab.
- Widget. A widget id must be unique. The ID is stored as a variable, thus the widget can be a variable. That's also why you can see widgets id inside variable tab in code editor.
- Component. As we have pointed out in [*Create your first project*](en/first-project.md), the components are actually a classes which are saved in a variable.

This brings us to a new question:

## Why we can't have duplicate variable names

This seems quite obvious (and it *realy* is). You can't have variable a = "dummy string" and use a object named a. This would lead into problems like a.setText() is not function.
Also another reason could be how Android handles *types*. [Learn what a type is here](en/blocks/variables.md). You can't assign a *string* to *number* variable. That's like trying to store water in a bag. (Don't try it). Although this type juggling (You can learn more at Google) is possible in certain languages (php, Javascript etc.), it is not in Android (as it's more bug-safe and has certain performance advantages.)
