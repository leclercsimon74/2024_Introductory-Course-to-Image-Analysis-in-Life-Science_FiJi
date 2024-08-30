# Introductory Course to Image Analysis in Life Science using FiJi
**Important ressources:**
- ImageJ website for plugins: https://imagej.net/ij/
- Advice for macro writing: https://imagej.net/ij/developer/macro/macros.html
- **Built-in Macro function**: https://imagej.net/ij/developer/macro/functions.html


## Why scripting?
- Improve reproducibility on image analysis
- Automating repetitive tasks in image analysis
- Creating custom image processing workflows
- Batch processing large sets of images
- Extending ImageJ's functionality without writing Java plugins

A simple example, going from this movie of a bacterial 🦠 growth

![rounding_assay.gif](Images/Readme_images/rounding_assay.gif)

To, with the help of a simple macro

![Macro_example_macro.png](Images/Readme_images/Macro_example_macro.png)

At a result table showing the shape evolution of the bacterial population

![Macro_example_result.png](Images/Readme_images/Macro_example_result.png)

The objective of this course is to learn the basic of ImageJ Macro language, with the almighty `Recorder` and the basic block of programmation such as `for` loop and `if` condition. At the end, **you** should have the tools and knowledge to be able to write your own macro!

## Requirement
- Have ImageJ or [Fiji](https://fiji.sc/) version 1.53t or later installed on your computer (Help=>Update)
- Download the [repositery](https://github.com/leclercsimon74/2024_Introductory-Course-to-Image-Analysis-in-Life-Science_FiJi/archive/refs/heads/main.zip) to have all images

## The basics
### Hello World!

```Java
// This is a comment. The script starts below.

// Print "Hello World!" to the log window
print("Hello World!");

// Show a dialog box with the message
showMessage("Greetings", "Hello World!");
```

In the code is presented 2️⃣ ways to display the classical `Hello World!`:

- the `print()` function, that will print the content between parenthesis in a log window
- the `showMessage()` that will open an interactive window displaying the message, with a 🆗 button to continue the code


























