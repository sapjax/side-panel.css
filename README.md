# side-panel.css

CSS variables for extension page in Chrome side panel

### Why

Chrome introduce [chrome.sidePanel](https://developer.chrome.com/docs/extensions/reference/sidePanel/) in version 114, extension page can be opened in the side panel, but the style of extension page is basically not consistent with Chrome's default style.
This css file is to provide some CSS variables for developers to make extension page look like Chrome's **default** style.

### What about other Themes

The **default** means the style of Chrome's default theme, if users use other [themes](https://chromewebstore.google.com/category/themes?hl=en), the colors in CSS variables may not be suitable for them.

There is a [Theme API](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/API/theme/getCurrent) in Firefox, but Chrome doesn't have it yet.

Once Chrome implements the theme API, we can use Javascript to get theme colors and set these CSS variables dynamically.

### How to use

Now, Just <kbd>Ctrl</kbd> + <kbd>C</kbd> it.
