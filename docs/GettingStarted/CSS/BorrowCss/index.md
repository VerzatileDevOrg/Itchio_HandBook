---
title: Borrow user CSS
description: Article talks about on how to borrow itch.io's CSS content on other creators's Itch.io creator or content page(s). Read more here!..
layout: default
parent: CSS
nav_order: 4
---

{{ page.title }}
======================

<br>

{: .note }
In the following section, gives a possibility to take other creators CSS and use it on your own projects or user page. <br> <br>
Strcture of the guide is on [Identifying CSS Elements](../IdentifyCssElements/) and using them <br>
Make sure to request [Access to CSS](../CssAccess/) before following the guide.

<br>

## Guidelines

<br>

1. **Find and Locate the Desired Page Resource:**
   - Visit another creators (`user_name.itch.io`) page or (`user_name.itch.io/assetOrGame`) asset pages using Browsers such as: **Microsoft Edge, Internet Explorer, or Chrome**. <br><br>
   <img src="{{ site.baseurl }}/assets/images/editUserTheme.png" alt="Edit User Theme Example" style="width:100%;"> <br><br>

2. **Locate the CSS Code:**
   - Right-click on the desired page.
   - Choose and select `View Page Source` or use `Ctrl + U` to access a new page displaying both the HTML and CSS code of the page.
   - For the following we are only interested in `CSS`. <br><br>
   <img src="{{ site.baseurl }}/assets/images/viewPageSource.png" alt="View Page Source Example" style="width:100%;"> <br><br>

3. **Identify CSS Content:**
   - Look for the user's CSS content, available right after either `<style id="user_defined_style_name">` and `#wrapper`.
   - If these are not present, locate content starting with a `.` as for example `(e.g., ".column.profile_column{}")` or text without coloring written in pure white (In an Unmodified browser).
   - Copy the portion starting from `.` to `{" until the closing "}` opening and closing brackets. <br><br>
   <img src="{{ site.baseurl }}/assets/images/pageSource.png" alt="Page Source Example" style="width:100%;"> <br><br>
   <img src="{{ site.baseurl }}/assets/images/pageSourceContent.png" alt="Page Source Content" style="width:60%;"> <br><br>

4. **Assure Accessibility:**
   - Ensure to follow the steps in [Accessing CSS](../CssAccess/) for your content and or userpage.
   - Continue to your page or content `my_user_page.itch.io`. <br><br>

5. **Edit Theme:**
   - If (Logged in) and the web page is in its default size, locate an `Edit Theme` button, available on user header [4.UI Modification Restrictions for Header section](../CssAccess/).
   - Click `Edit Theme` to open a side panel to the left. <br><br>
   <img src="{{ site.baseurl }}/assets/images/themeSidePanel.png" alt="Theme Side Panel Example" style="width:80%;"> <br><br>

6. **Navigate to "Custom CSS" in "Misc" Section:**
   - Scroll down to the `Misc` section.
   - Inside, there is a section called `Custom CSS` click on the associated field. <br><br>
   <img src="{{ site.baseurl }}/assets/images/customCssField.png" alt="Custom Css Field Example" style="width:40%;"> <br><br>

7. **Paste Borrowed CSS:**
   - The box is where you can use the `CSS that was borrowed` or your own text.
   - Paste the copied CSS into the box.
   - Click `save` <br><br>
   <img src="{{ site.baseurl }}/assets/images/editCssBox.png" alt="Edit Css Box Example" style="width:60%;"> <br><br>

8. **Preview Changes:**
   - Review and ensure the desired content was affected.
   - (Make sure to `Save` after modifications). <br><br>

{: .example }
```css
#wrapper <style id="userContent">
      
   .someCopiedSection {
   /* Your style content here */
   }

   /* Your access part here */

   .someCopiedSection2 {
   /* Your style content here */
   }
</style>
 ```

---

#### Author: VerzatileDev
#### Published: 10/01/2024