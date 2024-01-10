---
title: Access to CSS
layout: default
parent: Getting Started
nav_order: 1
---

{{ page.title }}
======================

<br>

Offers costumization to user-generated content, modifying the [itch.io](https://itch.io/)'s core style to the user's own preference. More information found here: [CSS Use-Cases](usecases.html).

Additionally it is recommended to read the official  [CSS Customization Guide By Itch.io](https://itch.io/docs/creators/css-guide).

<br>

## Guidelines for Requesting Access to [itch.io](https://itch.io/) CSS
<br>

### 1. Project Requirements:

- User page must showcase a minimum of (two) projects, which can be either games / assets or both.
- Content must be downloadable and or purchasable.

<br>


### 2. Access Request Details:

- Provide a reason(s) for requesting access to CSS.
- Include a detailed description on how you intend to use and apply (CSS) on the user or content page(s).

<br>


### 3. CSS Modification Conditions:

- Do not alter or compromise the fundamental structure of [itch.io](https://itch.io/)'s core (CSS) functionality.
- Ensure that your page's content remains accessible, operable, and readable.
- Apply a `#wrapper` at the start of your custom (CSS), which overwrites the core content of itch.io (CSS).

For instance, it is required that the content is open with a `#wrapper`condition, further specified with a `<style>` element, which is uniquely identified with an `ID` attribute such as `myAwesomeNewStyle` or an alternative of your choosing. Each `<style>` tag should be initiated with `<style id="myAwesomeNewStyle">` and concluded with `</style>`.

{: .example }
```c
    #wrapper
        <style id="myAwesomeNewStyle">
            // two forward slashes indicate a "CSS" style comment.

        </style>
```

<br>

### 4. UI Modification Restrictions:

- Do not alter itch.io's built-in UI, including global borders such as the header, which includes: `Edit Project`, `Edit Profile`, `Dashboard`, `Itch.io Logo`, `Edit Theme`, etc.
- Do not modify the footer of the page, including links like `itch.io` and `Community Profile`.

<br>


**Header**

![Header](/Assets/images/headerExample.png)

**Footer**
![Footer](/Assets/images/footerExample.png)

<br>

## How to Request access

- First and foremost make sure you have read the rules and conditions for requesting access to use CSS functionalities.
- Then [click me](https://itch.io/docs/creators/css-guide) or link to the website of itch.io CSS (https://itch.io/docs/creators/css-guide) locate the "Contact us" form. 

- On the "Contact Itch..io" (https://itch.io/support) website locate the button called e-mail " Support@itch.io " on which you are given a choice to use outlook / gmail or any available e-mail (Note that in contacting Itch.io you must use the same e-mail provided by your account and the account you are requesting access of).

- Give a meaninglful Subject: "CSS access Request - your_Username
- In the field you need to be respectful and provide a section of the intended changes that you are aiming to make.

As an example:

1. Centre Text.
2. Justify Text.
3. Change Mouse Icon (In a way that your website remains accessible for others).
4. Modify .gamecell content (Centring its text contents).

Please aim to keep it simple and provide the general basic outline for what you wish to modify on the website and which is not available with their default "theme Editor"

At the end of the e-mail, mention that you have indeed read and understood the [terms and conditions of using CSS on Itch.io](https://itch.io/docs/creators/css-guide).
After the e-mail has been sent expect to be notified no less than a week or more of writing the form if it was successfully accepted or denied.

