---
title: Get Access to Css
layout: default
parent: Getting Started
---

{{ page.title }}
======================

<br>

### What is itch.io's CSS?

<br>

Offers costumization to user-generated content and modifications to [itch.io](https://itch.io/)
core content available on and more information about [CSS use cases](usecases.html). 

Additionally read the official [CSS Customization Guide By Itch.io](https://itch.io/docs/creators/css-guide).

<br>

### Getting Access to CSS

<br>

In order to get access and use [itch.io](https://itch.io/) CSS, it is required that you meet the following criteria:

* The user's page should feature a minimum of two or more projects, which can be either games or assets.
* The user should give reasons on why they are requesting access to CSS, along with a detailed description of their intended application of it on their content pages.

* The user commits to refrain from altering or compromising the fundamental CSS structure of [itch.io](https://itch.io/) by imposing a `#wrapper` condition on every part of CSS that is overwritten or accessed.

For example, the content must be enclosed within a `#wrapper` and additionally defined within a `<style>` element with a specific identifier `id`, such as `myAwesomeNewStyle` or a chosen alternative. Each `<style>` tag is initiated with `<style id="User_Given_Name">` and concluded with `</style>`.

```c
    #wrapper
        <style id="myAwesomeNewStyle">
            // This is a Comment After this is where Content is written

        </style>
```

* The user must keep their pages content accessible, operable and readable.

* The user must not alter [itch.io's](https://itch.io/) built in UI (Such as the global Borders such as the `header`, which includes: `Edit Project`, `Edit Profile`, `Dashboard`, `Itch.io Logo`, `Edit Theme`, etc. Additionally the footer of the page should not be altered such as the links listed below: (`itch.io` and `Community Profile`)).



<br>


<br>