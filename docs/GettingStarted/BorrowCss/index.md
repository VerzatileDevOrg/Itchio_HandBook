---
title: Borrow user CSS
layout: default
parent: Getting Started
nav_order: 5
---

# Accessing and borrowing user CSS on itch.io

<br>

To replicate the CSS style of a user's asset and or a game page on [itch.io](https://itch.io/), follow these steps:

<br>

**Find and Locate the Desired Page:**
   - Visit the user page (`user_name.itch.io`) or asset pages (`user_name.itch.io/assetOrGame`) using Browsers such as: **Microsoft Edge, Internet Explorer, or Chrome**.

<!-- Showcasing a user Page -->
<img src="{{ site.baseurl }}/assets/images/editUserTheme.png" alt="Edit User Theme Example" style="width:80%;">

<br>

**Access HTML and CSS Code:**
   - Right-click on the desired page.
   - Choose and select "View Page Source" or use `Ctrl + U` to access a new page displaying the HTML and CSS code of the page.

<!-- Shows how to access and view Page Source -->
<img src="{{ site.baseurl }}/assets/images/viewPageSource.png" alt="View Page Source Example" style="width:80%;">

<br>

**Identify CSS Content:**
   - Look for the user's CSS content, available right after either `<style id="user_defined_style_name">` and `#wrapper`.
   - If these are not present, locate content starting with a period (e.g., ".column.profile_column{}") or text without coloring written in pure white (In an Unmodified browser).
   - Copy the portion starting from "." to "{" until the closing "}".

<!-- Shows example of the Page Source -->

<img src="{{ site.baseurl }}/assets/images/pageSource.png" alt="Page Source Example" style="width:80%;">

<!-- Shows correct content of the page source -->
<img src="{{ site.baseurl }}/assets/images/pageSourceContent.png" alt="Page Source Content" style="width:60%;">

<br>

**Verify Accessibility:**
   - Ensure you have followed the steps in "Accessing CSS for Itch.io" on your own user, asset, or game page.
   - Continue to your page or content `my_user_page.itch.io` and make sure you have read how to enable [CSS editing access](cssaccess.html).

<br>

**Edit Theme:**
   - If logged in and the web page is in its default size, locate an "Edit Theme" button, available on user header [5.UI Header](cssaccess.html).
   - Click "Edit Theme" to open a side panel to the left.

<!-- Shows "Edit Theme" Side Panel -->
<img src="{{ site.baseurl }}/assets/images/themeSidePanel.png" alt="Theme Side Panel Example" style="width:80%;">

<br>

**Navigate to "Custom CSS" in "Misc" Section:**
   - Scroll down to the "Misc" section.
   - Inside, there is a section called "Custom CSS" click on the associated field.

<!-- Shows "Edit Theme" section of content -->
<img src="{{ site.baseurl }}/assets/images/customCssField.png" alt="Custom Css Field Example" style="width:30%;">


<br>

**Paste Borrowed CSS:**
   - The box is where you can use the "CSS that was borrowed" or your own text.
   - Paste the copied CSS into the box.
   - Click "save"

<!-- Shows "Edit Theme" section of content CSS field -->
<img src="{{ site.baseurl }}/assets/images/editCssBox.png" alt="Edit Css Box Example" style="width:60%;">

<br>

**Preview Changes:**
   - Review and ensure the desired content was affected.
   - (Make sure to Save the content).
   
<br>

**Final State:**

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