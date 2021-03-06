# 1. Google Chrome

<!-- TOC -->

- [1. Google Chrome](#1-google-chrome)
    - [1.1. Developer Tools](#11-developer-tools)
        - [1.1.1. Preferences](#111-preferences)
            - [1.1.1.1. Device Toolbar](#1111-device-toolbar)
    - [1.2. Extensions](#12-extensions)
        - [1.2.1. JSON Viewer](#121-json-viewer)
        - [1.2.2. CSS Peeper](#122-css-peeper)
        - [1.2.3. Fireshot](#123-fireshot)
        - [1.2.4. Wappalyzer](#124-wappalyzer)
        - [1.2.5. Postman](#125-postman)

<!-- /TOC -->

## 1.1. Developer Tools

### 1.1.1. Preferences

The developer tools come with their own set of advanced settings. To open these settings you can either use the menu button next to the close button, or use the hotkey `F1` while your devtools are open.

- Appearance
  - It is possible to change the color scheme of your developer tools.
    - Light (default)
    - Dark 
- Network
  - Disable cache (while DevTools is open)
    - While developing you often need to refresh your cache to see your changes.
    - This setting auto disables the cache with the devtools open.
  - Preserve log
    - Allows you to save your logs between navigation.
    - Especially useful with auto redirecting javascript pages showing errors!
- Debugger
  - Disable JavaScript
    - With this toggle you can test how your site works without Javascript enabled.
    - This can highlight issues with not being able to visit poor programmed preloaders for example, as without Javascript the overlay will never vanish.

#### 1.1.1.1. Device Toolbar

In the top left of the developer tools you can find a toggle to activate the device toolbar. This interface lets you simulate any website as how it would look on a mobile device. By using this system you won't need to manually rescale your browser screen anymore while working mobile first! In many cases this simulation can also represent the looks of your websites more accurately than manually changing the browser size.

This tool comes with a up-to-date selection of devices to choose from, but it's also possible to enter your custom dimensions.

While testing the load performance of your app, this tool can be extra useful as you can use presets based on different mobile network setups to simulate your website its performance.

## 1.2. Extensions

### 1.2.1. JSON Viewer

A lot of times while working with JSON you might notice that output of scripts and APIs is being minified. This can make it harder to visually read and understand the output of these tools.

JSON Viewer automatically highlights these pages and adds formatting for human reading. The extension also works for formatting php debugging.

### 1.2.2. CSS Peeper

CSS Peeper assists you in getting useful information about the design of webpages. After installation the extension can be accessed from the top right in Google Chrome, after which it opens a new pane. This pane has three tabs at the bottom for navigation.

In the first tab opened by default, you can get a basic overview of the style for the page. The fonts for both the headings and body text are being listed and you can quickly check the loadtime of the present stylesheets.

The second tab is all about colors. In a clean list, you can quickly checkout and copy any of the colors used on the website. This tool will even show the transparency and opacity details of each color if present!

Last but not least the assets tab can reveal all images, used on the webpage.

### 1.2.3. Fireshot

Fireshot can automatically create screenshots of an entire webpage. This behavior can be customised to only screenshot the current content within the canvas or even a custom selection!

### 1.2.3. Fireshot

Fireshot can automatically create screenshots of an entire webpage. This behavior can be customised to only screenshot the current content within the canvas or even a custom selection!

### 1.2.4. Wappalyzer

[Wappalyzer](https://www.wappalyzer.com/) is a cross-platform utility that uncovers the technologies used on websites. It detects content management systems, ecommerce platforms, web frameworks, server software, analytics tools and many more. 

### 1.2.5. Postman

[Postman](https://www.getpostman.com) makes API development faster, easier, and better. The app is available as Chrome app and native app. Postman provides an slick GUI and a large number of tools that support the entire API workflow. API monitoring, debugging with tests/scripts/variables/..., automated testing integrated into your CI/CD pipeline, create and publish web-viewable documentation on the fly,...
