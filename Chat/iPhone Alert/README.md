# iPhone Alert
This widget displays an iPhone message alert notification when a user types a message into chat for the first time.

## HOW TO: ADD THIS WIDGET TO YOUR OVERLAY
To add this widget to your overlay, follow these steps:

1. Go to StreamElements, sign in and go to *My Overlays* in the left-hand menu.
2. Click *Edit* on an existing overlay you would like to add this widget to **or** select *Create Blank Overlay* in the top-right.
3. Click the circular *+* button at the bottom of the screen and select *Static / Custom* -> *Custom Widget*
4. Click the new widget that has appeared in your overlay and click *Settings* in the left-hand menu.
5. Click *Open Editor*
6. Replace *all* of the code in the **HTML** tab with the code inside the *iphone.html* file in this repository.
7. Replace *all* of the code in the **CSS** tab with the code inside the *iphone.css* file in this repository.
8. Replace *all* of the code in the **JS** Tab with the code inside the *iphone.js* file in this repository.
9. Replace *all* of the code in the **Fields** tab with the code inside the *iphone.json* file in this repository.
10. Replace *all* of the code inside the **Data** tab with: {}
11. Click *Done* in the bottom-right.

## HOW TO: CUSTOMISE THE WIDGET
This widget can be customised to suit your stream. To do this, click on this widget in your StreamElements Overlay, click **Settings** in the left-hand menu and browse the drop-down menus. In case you are unsure what any of the settings do, here is a glossary:

### App
**Name** - The 'application name' displayed in the header of the notification.

**Icon** - The icon displayed in the header of the notification.

**Alert** - The sound that will be played when the notification is displayed. (Can be left blank if no audio required)

**Volume** - The volume for the alert sound.

**Corner Radius** - The roundness (in pixels) of the notification's corners.

**Top Margin** - The gap (in pixels) that is left above the notification.

### Header
**Background Colour** - Background colour for the notification header.

**Text Colour** - Text colour for the notification header.

**Font** - Font to use for the notification header text.

**Font Size** - Font size to use for the notification header text.

**Height** - Overall height of the header section.

### Body
**Background Colour** - Background colour for the notification body.

**Text Colour** - Text colour for the notification body.

**Font** - Font to use for the notification body text.

**Font Size** - Font size to use for the notification body text.

### Messages
**Ignore Usernames** - List of usernames to ignore so messages are **not** displayed. *(Used mostly to ignore chatbots such as StreamElements, NightBot and StreamLabs).*

**Message Duration** - How long (in seconds) to display the notification for.

**Maximum Message Lines** - The maximum amount of lines to display for a message before trimming with an ellipsis ("..."). This is to prevent very long chat messages taking up a lot of space.

## SIZING
This widget will automatically stretch to fill the *width* of the widget's outline in the overlay, but will **not** stretch to fill the *height* as message-lengths can vary (longer messages will fill more vertical space!). I recommend setting the height of the widget to the same height as your entire overlay to ensure the widget doesn't get cut off.

You can change the widget's width and height by clicking on the Widget in your StreamElements overlay and selecting **Position, size and style** in the left-hand menu.


