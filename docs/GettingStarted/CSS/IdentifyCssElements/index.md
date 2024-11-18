---
title: Identify CSS elements
layout: default
parent: Getting Started
nav_order: 3
parent: CSS
---

{{ page.title }}
======================

{: .note}
Nearly Everything seen on the user page or content page can be changed by Itch.io as long as you follow the rules outlined in [Itch.io's Guidelines](../CssAccess/) <br> <br>
Though keep in mind, not everything requires or needs changing, aim to keep it at a minimal or as close to possible.

In order to get started in identifying CSS content, which can be changed an option is to take a look at [External video on borrowing CSS](https://www.youtube.com/watch?v=77QR5JAvmXE) or to follow the listed guide.


The simplest way to any browser such as `Edge, Chrome, Opera, Firefox` and many others, first start with an inspect element. In order to access it most commonly is by a shortcut key `Ctrl + u` or by right clicking the mouse and locating `Inspect` or `Inspector`.

A new panel with `Element, Console, Source, etc`, is going to open on the side of the browser make sure its on `Element`, where a color coded code can be seen. In this guide we are interested in `Class=" "`, this is the core to what we are aiming to locate and modify, though keep in mind not each class can be modified and may require modification in other classes to work properly.

<br>

Areas that can be changed:

1. ```<div class= " "> ```
2. ```<section class= " ">```
3. Some do not have classes such as `<h>`, meaning header element. Which uses a global specification to set its size color and other elements, for such cases it is best to change it with just the `<h1>` elements that range from `h1 - h5` or by identifying an element by its title.


{: .code title="Example"}
```c
    <div class="column profile_column"> </div>
    
or

    <div class="inner_column profile_content"> </div>

etc..
    
```

{: .note}
The following elements can be modified through `Edit Theme` and under the `Misc` section `Custom CSS`. <br> <br>
Elements should be inside a `#wrapper` and inside `<section>` and suggested in [Css Modification Conditions](../CssAccess/)

Additionally upon clicking each element in the `Element` section a `styles` tab should be under it, where it shows the HTML's code to the CSS.
As seen each element uses a `.` infront of the name such as for example `.side-bar`, keep it in mind as to access each class we require a `.` and now spacing can be in the class name, in case there is also use a `.`. For Example `class="column game_column"` is a collection of two seperate classes, which you can use by `.column` and `.game_column`, Though it is recommended that you access it in such manner as `.column.game_column`.

As you have now identified the elements, we need to modify its elements in order to do it, we need to use another indication such as `{ }`, inbetween these is where we write our modified code for example the previous `.column.game_column` we can modify by `.column.game_column {  }`

{: .code}
```c
.column{}.game_column
{
    // Your code after the comment

}

or 

h2 {
    font-weight: bold;
    color: #fff;
    font-size: 25px;
    width: 100%;
    text-align:center !important;
    text-decoration: underline;
    
}

or 

.game_cell:hover 
{
    transform: scale(0.95,0.95) !important;
    transition: 0.33s ease;
    border-color: #2ce8f4;
    background: linear-gradient(0deg, #000030, purple);
    padding: 5px;
} 
```

As noticed the previous element used `{}` as well, the reason for it is that you can add code to that element and it makes sure that the `.game_column` is accessed correctly.

{: .code title="Preview Code"}
```c
#wrapper
<style id="costum_css" type="text/css">

.column{}.game_column
{
    // Your code modification after the comment

}

</style>
```

There are wide areas that can be changed and not every one of them can be mentioned here, though I recommend reading into resources such as [CSS Introduction by W3School](https://www.w3schools.com/css/), which sets you to the path of how to use the `CSS` with tips and suggestions. Additionally you may notice that the website does not use a `.`, as this is specified differently for certain websites and methods of how it is programmed, though for Itch.io we use a `.` before the class element.


---

#### Author: VerzatileDev
#### Published: 18/11/2024