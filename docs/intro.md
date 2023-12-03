---
sidebar_position: 1
---

# Quick Start

After you install the extension, it's recommended to pin it as it will be easier to 
create shortcuts.

Create custom shortcuts in the web. What does that mean? and How to exactly do that?


Here, let's start with a practical tutorial.

## Creating a new Shortcut

:point_right: Open the Popup

:point_right: Click on the Create Shortcut (+) button OR use the quick shortcut CTRL + SHIFT + Q.

:point_right: An Element Selector will open in the bottom right of the window


:::warning Bugs in Creating a new shortcut
Due to some bugs, you might face a few issues in the starting or once in a while when you create a new shortcut using the button in the Popup. You **may need the button to click twice** and sometimes **multiple Element Selectors may open**, you can drag one of them to see if there's another one behind it. But this will not happen most of the times, and you can simply reload the tab and create a new shortcut again to solve this issue.
:::



:::note Note

Only websites (http://\*, https://\*) are supported currently

:::

## Selecting an Element :computer_mouse:

You can notice that whichever element of the website your mouse is hovering on is having a red border around it. It's a visual cue that you are selecting that Element. You will also see the [tagName](https://developer.mozilla.org/en-US/docs/Web/API/Element/tagName) of that Element in the Element Selector's Selected Element area.


:::note Note
Currently in `v1.0.0`, we only have the option to select a Single Element, but in the future versions will have the ability to select multiple elements and on multiple conditions. This will extend its functionality and will be much more useful.
:::
 
### 3 methods to select an Element
There are actually three methods by which you can select an element.


1. Click on the Element, or, 
2. Hover over the Element, and press `Enter` key, or, 
3. Hover over the Element, and press `CTRL` key, this will pause Element Selection temporarily and a Confirm Selection button will appear in the Element Selector. You can move your cursor now (notice that the Selected Element is not changed, because Element Selection is paused.) and click on the Confirm Selection button.

## Shortcut Key Selection and Other Properties :keyboard:
After successfully selecting an Element, the Key Selector dialog will open where you can set your desired shortcut key for that Element, and other important properties.


:point_right: Press the character key you want to use as the shortcut key. You can click on Edit Shortcut button to change it.

:::note Note
Character keys are, a-z, A-Z, 0-9, and other special characters (@, #, /, `. ~. \*, brackets, punctuations, etc.).
:::

:point_right: Give the Shortcut a short & concise name to remember it easily. 
:::note Note
There can't be more than 20 characters in a shortcut name. 
:::
:::tip Tip
Try to name the Shortcut such that it gives you the correct idea of its purpose. For example if there's a button which opens Notifications Page/Popup, you can name it 'Notifications', or if it opens a sidebar, name it 'Sidebar'.
:::

:point_right: You can keep the "Set the shortcut for" option as it is. If you have some specific needs, you can read more about URL Types.

:point_right: Set your desired Action. If you want to click on the Element, which is mostly the case, keep the `Click` option selected, but if you want to focus on the Element instead, select the `Focus` option.
:::tip Tip
If you're selecting an Input element, then it is recommended to set the Focus Action as it will make the input focused on shortcut key press and the cursor will come in it. Click action may also work but it's usually not reliable for Inputs.
:::

:::note Note
There will be more Actions in the future, you can already see the Coming Soon options :wink:.
:::

:point_right: Click on the Confirm Selection button once you are done. 


After Confirming, the Key Selector will close, but the Element Selector will remain open, this is to let you create multiple shortcuts without opening the Popup again and again to create a new Shortcut.



:::important Important
It is recommended to Reload the page once you are done with shortcut creation. This is to ensure it works. If it's not working even after reloading, try closing and opening the tab again.
:::


