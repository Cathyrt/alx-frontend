# 0x01. Developer Tools

Developer Tools are a set of built-in tools in web browsers that aid developers in debugging, optimizing, and analyzing web pages. They provide valuable insights into the structure, performance, and behavior of web applications. The following sections explain how to access and utilize Developer Tools in popular browsers.

## Opening Developer Tools

### Chrome

To open Developer Tools in Google Chrome, follow these steps:

1. Right-click anywhere on a webpage.
2. Select "Inspect" or "Inspect Element" from the context menu.
3. Alternatively, you can use the keyboard shortcut:
   - Windows/Linux: `Ctrl + Shift + I`
   - macOS: `Command + Option + I`

### Firefox

To open Developer Tools in Mozilla Firefox, follow these steps:

1. Right-click anywhere on a webpage.
2. Select "Inspect Element" from the context menu.
3. Alternatively, you can use the keyboard shortcut:
   - Windows/Linux: `Ctrl + Shift + I`
   - macOS: `Command + Option + I`

### Safari

To open Developer Tools in Safari, follow these steps:

1. Go to Safari Preferences.
2. Click on the "Advanced" tab.
3. Check the box that says "Show Develop menu in menu bar."
4. Close the Preferences window.
5. In the menu bar, click on "Develop" and select "Show Web Inspector."
6. Alternatively, you can use the keyboard shortcut:
   - macOS: `Command + Option + I`

### Edge

To open Developer Tools in Microsoft Edge, follow these steps:

1. Right-click anywhere on a webpage.
2. Select "Inspect Element" from the context menu.
3. Alternatively, you can use the keyboard shortcut:
   - Windows: `Ctrl + Shift + I`

## Using the Elements Tab to Edit HTML and CSS

Once you have Developer Tools open, you can use the Elements tab to inspect and edit the HTML and CSS of a web page. Here's how you can do it:

1. Open Developer Tools in your preferred browser.
2. Navigate to the Elements tab.
3. To inspect an element, click on it in the rendered page or locate it in the HTML structure.
4. To edit the HTML, double-click on an element's content and make changes.
5. To modify CSS properties, locate the Styles pane on the right and edit the values.
6. Changes made through the Elements tab are temporary and won't persist after a page refresh.

## Auditing a Page with Lighthouse

Lighthouse is a tool built into Developer Tools that helps audit web pages for performance, accessibility, best practices, and more. To run an audit using Lighthouse:

1. Open Developer Tools in your browser.
2. Navigate to the Lighthouse tab.
3. Click on the "Generate report" or "Run audit" button.
4. Select the desired categories to audit (e.g., Performance, Accessibility, SEO).
5. Click on "Generate report" or "Run audit" to start the analysis.
6. Once completed, Lighthouse provides a detailed report with suggestions for improvement.

## Creating and Running Snippets

Snippets are small pieces of JavaScript code that can be created, saved, and executed within Developer Tools. To create and run snippets:

1. Open Developer Tools in your browser.
2. Navigate to the Sources or Snippets tab (varies by browser).
3. Click on "New snippet" or a similar button to create a new snippet.
4. Write your JavaScript code in the editor.
5. To run the snippet, either click the "Run" button or use the keyboard shortcut:
   - Windows/Linux: `Ctrl + Enter`
   - macOS: `Command + Enter`

## Getting Information about Files and Server Configurations

Developer Tools allow you to gather information about files loaded by a webpage and server configurations. Here's how you can do it:

1. Open Developer Tools in your browser.
2. Navigate to the Network tab.
3. Reload the page to capture network requests.
4. The Network tab displays various files, including HTML, CSS, JavaScript, images, and more.
5. Click on a file to view detailed information such as headers, response data, and timing.

## Blocking Requests

You can use Developer Tools to block specific requests made by a webpage. Follow these steps to block requests:

1. Open Developer Tools in your browser.
2. Navigate to the Network tab.
3. Locate the request you want to block.
4. Right-click on the request and select "Block Request URL" or a similar option.
5. The request will be blocked, and you can observe the effects on the webpage.

## Determining JavaScript and CSS Usage

To determine the amount of JavaScript or CSS used on a webpage, you can utilize Developer Tools:

1. Open Developer Tools in your browser.
2. Navigate to the Coverage tab (available in some browsers).
3. Click on "Start instrumenting coverage" or a similar button.
4. Perform the desired actions on the webpage.
5. Once finished, the Coverage tab will display a breakdown of JavaScript and CSS usage.

## Detecting 404 Issues

To detect 404 issues (missing resources) on a webpage, Developer Tools can be useful:

1. Open Developer Tools in your browser.
2. Navigate to the Network tab.
3. Reload the page to capture network requests.
4. Look for any requests that return a 404 status code (not found).
5. These requests indicate missing resources, such as images, scripts, or stylesheets.

## Moving Elements on a Webpage

Developer Tools allow you to manipulate elements on a webpage, including moving them around. Here's how you can move elements:

1. Open Developer Tools in your browser.
2. Navigate to the Elements tab.
3. Locate the element you want to move.
4. Right-click on the element and select "Edit as HTML" or a similar option.
5. Modify the HTML structure to move the element within the page.
6. Press Enter or click outside the edit area to apply the changes.

---
