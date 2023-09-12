# Lecture 3: Getting Started with VR Development

In this lecture, I will introduce the VR development pipeline and demonstrate how to create simple virtual environments using the Godot Engine.

## Prerequisites

To follow along with this lecture, you will first need to install:

- [Godot Engine 4.1.1](https://godotengine.org/) -  We will be using the standard version in class, which only supports GDScript. However, you may optionally install the .NET version if you would also like to use C# in your assignments.
- [Visual Studio Code](https://code.visualstudio.com/)

I also recommend you install the following useful VS Code extensions:

- [godot-tools](https://marketplace.visualstudio.com/items?itemName=geequlim.godot-tools) - Make sure you use "Open Folder" and select your entire project folder for this to work properly!
- [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) - Useful for source control within VS Code.

## Notes

There are a couple additional notes regarding this lecture:

- The bug I encountered at the end of the class was actually due to an environment variable that was overriding the default OpenXR runtime. I had set it a month ago while working on a VR simulator as a side project and then forgotten about it.  Note to self: don't set global environment variables for temporary functionality; use a script instead. 
- I forgot to mention that Godot has an integrated code editor. This is the default option when editing scripts, and it works quite well. However, if you prefer to use VS Code or another external IDE, you can set the path in Editor_>Editor Settings->Text Editor->External.

## License

Material for [CSCI 5619 Fall 2023](https://canvas.umn.edu/courses/391288/assignments/syllabus) by [Evan Suma Rosenberg](https://illusioneering.umn.edu/) is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).