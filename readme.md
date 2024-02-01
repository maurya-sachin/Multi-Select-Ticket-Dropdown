# Autocomplete Component

This project provides a customizable autocomplete component implemented in HTML, CSS, and JavaScript. It allows users to select multiple options from a dropdown menu with autocomplete suggestions.

# Demo

[View Demo](https://maurya-sachin.github.io/Multi-Select-Ticket-Dropdown/)

## Features

- **Autocomplete Suggestions**: As the user types in the input field, the component provides autocomplete suggestions based on the available options.
- **Multiple Selection**: Users can select multiple options by either typing in the input field or selecting from the autocomplete suggestions.
- **Dynamic Option Loading**: Options can be loaded dynamically from an external JSON file or an API endpoint.
- **Custom Styling**: The component's appearance can be customized using CSS to match the design requirements of your application.

## Usage

1. **HTML Structure**: Include the provided HTML code in your project's HTML file. Replace the `<select>` element with the desired options or load options dynamically using JavaScript.

2. **Initialization**: Call the `init()` function in your JavaScript code to initialize the autocomplete component. Pass the `<select>` element and the options as parameters to the function.

3. **Customization**: Customize the component's appearance and behavior by modifying the CSS styles and JavaScript code according to your requirements.

4. **Dynamic Option Loading (Optional)**: If you want to load options dynamically, uncomment the relevant code in the JavaScript section. You can fetch options from a JSON file or an API endpoint.

5. **Event Handling**: Customize event handling as needed for your application. For example, you can handle click events outside the component to close the dropdown menu.

## Dependencies

This project has no external dependencies. It utilizes HTML, CSS, and vanilla JavaScript to provide the autocomplete functionality.

## Compatibility

The autocomplete component is designed to work on modern web browsers that support HTML5, CSS3, and ECMAScript 6 (ES6) features. It may require polyfills or adjustments for compatibility with older browsers.

## License

This project is licensed under the [MIT License](LICENSE).
