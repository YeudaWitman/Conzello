Conzello
========

Conzello is a JavaScript library designed to bring style and customization to `console.log` output in browser developer tools. With Conzello, you can enhance your debugging experience by adding colors, custom formatting, and other creative touches to your console logs.

Features
--------

*   **Colorful Logs**: Add a splash of color to your console output to make important information stand out.
*   **Custom Formatting**: Apply unique styles, symbols, or layout changes to create a more readable log structure.
*   **Enhanced Debugging**: Use custom styles to differentiate between different log types or to highlight specific information.

Use Cases
---------

*   **Debugging**: Make debugging easier by distinguishing between different log levels or highlighting key messages.
*   **Development Tools**: Create a more engaging console experience for developers and development teams.
*   **Logging Frameworks**: Integrate Conzello with your existing logging framework to add extra style and functionality.

Installation
------------

To install Conzello in your project, you can use npm or yarn:

bash

Copy code

`# Using npm npm install conzello  # Using yarn yarn add conzello`

Usage
-----

After installing Conzello, you can import and use it to customize your console logs:

javascript

Copy code

`import { styleLog } from 'conzello';  // Example of a styled console log styleLog('Hello, Conzello!', { color: 'blue', fontWeight: 'bold' });  // Using a preset style styleLog('This is an important message!', 'alert');`

Contributing
------------

We welcome contributions to Conzello! If you'd like to contribute, please follow our [contribution guidelines](CONTRIBUTING.md) and check out our [code of conduct](CODE_OF_CONDUCT.md).

License
-------

Conzello is licensed under the MIT License. For more information, see the LICENSE file.
