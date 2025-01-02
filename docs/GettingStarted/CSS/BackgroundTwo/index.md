---
title: Change Background 2
description: Article talks about on how to change background image two on itch.io content page, read more about it here..
layout: default
parent: CSS
nav_order: 5
---

{{ page.title }}
======================

<br>

{: .note }
The following section covers each step in changing the middle panel of your content page area, which is called background 2, before following the guide make sure to have [Access to CSS](../CssAccess/) and an understanding in [Identifying CSS Elements](../IdentifyCssElements/).

{: .important }
For video guidance see the following [Itch.io - Change Background Image 2](https://www.youtube.com/watch?v=zLjYkT_0HAU).

<br>


## Guidelines

<br>

1. **Find and Locate the Desired Page Resource:**
   - Visit your content page change the `username` and `project name` and use the following link (`user_name.itch.io/assetOrGame`) asset pages using Browsers such as: **Microsoft Edge, Internet Explorer, or Chrome**. <br><br>


2. **Open inspect element and locate Background 2 class:**
    - Right click on Chrome or Edge and use `Inspect` or `Inspect element` a new panel opens.
    - In the panel locate `select and view element` option or use `Ctrl + Shift + C` shortcut to use it.
    - Click on the desiered area such as in this example " Background 2 " which is under the element class `inner_column size_large family_lato` and under ID `inner_column`
    - Now locate the main class of the previous, which is called `game_page_primary_column` <br><br>

3. **Open "Edit Theme"**
    - For the following use this method [How to Add edit css](https://verzatiledevorg.github.io/Itchio_HandBook/docs/GettingStarted/CSS/BorrowCss/#guidelines)
    - Click `Edit Theme` on top left of the project page panel.
    - A new panel opens up, now in that panel locate `Custom CSS`. <br><br>

4. **Edit Css and reference the main class:**
    - Read about [Css modification conditions](https://verzatiledevorg.github.io/Itchio_HandBook/docs/GettingStarted/CSS/CssAccess/#3-css-modification-conditions) and use the same formating.
    - Inside the `<style> and </style> ` use the following `.game_page_primary_column{}.inner_column { }`
    - Add inside the brackets`{ }` the following `background-image: url(" ");` and in the `(" ")` add your href or location of the image you wish to use in your page. <br><br>

{: .example }
```css
#wrapper
<style id = "NewStyle"> 

.game_page_primary_column{}.inner_column
{

  background-image: url(" ");
}
</style>
```