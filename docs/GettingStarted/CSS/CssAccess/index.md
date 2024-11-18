---
title: Access to CSS
description: Article talks about on how to gain access to itch.io's CSS content on Itch.io. Read more here!..
layout: default
parent: Getting Started
nav_order: 1
parent: CSS
---

{{ page.title }}
======================

<br>

{: .note title="Itch.io's CSS"}
Offers costumization to user-generated content, modifying the [itch.io](https://itch.io/)'s core style.  <br> <br>
Information on [CSS Use-Cases](../UseCasesCss). <br>
Read the official [CSS Customization Guide By Itch.io](https://itch.io/docs/creators/css-guide).

<br>

## Guidelines

<br>

### 1. Project Requirements:

- User page must showcase a minimum of (2) projects, either Game(s), Asset(s), Tool(s) or combined.
- Content must be downloadable and or purchasable.

<br>


### 2. Access Request Details:

- Provide a reason(s) for requesting access to CSS.
- Include a detailed description on how you intend to use and apply (CSS) on the user or content page(s).

<br>


### 3. CSS Modification Conditions:

- Do not alter or compromise the fundamental structure of [itch.io](https://itch.io/)'s core (CSS) functionality.
- Ensure that your page's content remains accessible, operable, and readable.
- Apply a `#wrapper` and `<style>` at the start of your custom (CSS), which overwrites the core content of itch.io (CSS).
- Ending it with `</style>`.

<br>

{: .code title="An Example"}
The content must start/open with a `#wrapper` condition, specified with a `<style>` element, which is uniquely identified with an `ID` attribute such as `myAwesomeNewStyle` or an alternative of your choosing. Each `<style>` tag should be initiated with `<style id="myAwesomeNewStyle">` and concluded with `</style>`.
```c
#wrapper
    <style id="myAwesomeNewStyle">
        // Two forward slashes indicate a "CSS" style comment.
        // Code must be written Inside of <style> and </style>

    </style>
```

<br>

### 4. UI Modification Restrictions:

- Do not alter itch.io's built-in UI, including global borders such as the header, which includes: `Edit Project`, `Edit Profile`, `Dashboard`, `Itch.io Logo`, `Edit Theme`, etc.
- Do not modify the footer of the page, including links like `itch.io` and `Community Profile`.

<br>


**Header**

<img src="{{ site.baseurl }}/assets/images/cssHeaderExample.png" alt="Header Example" style="width:100%;">

**Footer**

<img src="{{ site.baseurl }}/assets/images/cssFooterExample.png" alt="Footer Example" style="width:100%;">

<br>

## How to Request access?

<br>

{: .note }
Read the [Css Creator Guide](https://itch.io/docs/creators/css-guide) or link to the website of itch.io CSS `(https://itch.io/docs/creators/css-guide)` locate the "Contact us" form. 

### Access Contact form:

1. Locate the website's Contact form for Itch.io on -> `(https://itch.io/support)`, with a button called ` e-mail " Support@itch.io " `.
    
2. There will be two options, either through an outlook pop-up or do it manually by sending an e-letter to ` Support@itch.io `.

<br>

{: .important }
You must use the same (E-Mail) Address as your account that you are requesting accces to!

<br>

{: .note }
Subject: "CSS access Request - your_Username "<br>
Field: Be respectful, provide a section of the intended changes.

<br>

### Field Example:

<br>

1. Centre Text.
2. Justify Text.
3. Change Mouse Icon (In a way that your website remains accessible for others).
4. Modify .gamecell content (Centring its text contents).


- Keep it simple, provide the basic outline for the intended changes on the website, which are not available by their default "Theme Editor" functionality.

<br>

{: .important}
At the end of the e-mail, mention that you have read and understood the [terms and conditions of using CSS on Itch.io](https://itch.io/docs/creators/css-guide).

{: .note title="After E-Mail"}
Expect to be notified in approximently 1 - 2 weeks, on the Accepted or Denied response.


---

#### Author: VerzatileDev
#### Published: 10/01/2024