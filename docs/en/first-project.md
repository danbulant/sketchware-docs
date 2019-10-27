---
id: first-project
title: Creating your new application
---
## New project
To create your first app, you need to create a *project* for it.
You can do it by opening sketchware and tapping "**Create new project**" (the **+** button).

Sketchware will then ask you for some basic information. For now, you just need to enter the name of your app (To be shown under the icon).

## Tabs

When your new project is created, you will see 3 tabs. The one selected now is View, where you change how your application looks.

### View

In the view tab, there are 3 main things. On the left, you'll see a list of *objects* you can use.
On the right, there is a canvas which is used to drop objects in.

Try dropping a *TextView* on the canvas and select it. Now you will see the third part of this tab - properties of the currently selected object.
To **to change the text**, select text property in object properties. A dialog asking for a new text will appear. Write anything you like.

### Event

Before learning about the **event tab**, we first need to learn how Android application works.

Android is a event driven language, which means it fires an event when a user do something or a response is get.

#### Tab contents

In the tab, their are 3 main contents which are used. On the left, you can see groups of events. You can switch between them by clicking on their icons.

On the right, you can see a list of events in the currently selected group.

Finally, on the bottom right, there's a **FAB** - Floating Action Button. It has **+** icon in it.
This button will show you a dialog to create a new event listener.

#### Event listeners

Event listener is a function (or method) that's called when a certain event is fired. For example, when you run your app, a onCreate event will be fired. There's already a listener for this event. Select *Activity* group and you will see it. Click on it's name and code editor will open.

#### Code editor

Remember how we mentioned Scratch in the main page? The code editor uses it's design. You can then make your logic for the event there.

### Components

In the components tab, there's a list of **currently available app components.** In the real programming, they are called *Classes*, but for the sake of simplicity, we will continue to call them *components*.
When you open Components tab for the first time in your project, you will see it's empty. To add a new component, click the **+ icon on FAB**. This will show a dialog with a gridlist of available components. Select one of them and enter it's name (must be unique, we will point out why later) to add it to your app (there are some [exceptions](#)).


## Conclusion

That's all! You learnt how to create your first app and how to use the project UI.
