# Tip Calculator

This is a full tip calculator project implemented in HTML, CSS, and JavaScript. The web application allows users to calculate the tip amount and the total bill amount based on the bill amount and the tip percentage they provide.

## Getting Started

To use the Tip Calculator, simply open the provided HTML file named `index.html` in your web browser. No additional setup or installation is required. The application is designed to be user-friendly and works on modern web browsers.

## How to Use

1. Open the `index.html` file in your web browser.

2. The web page will display a "Tip Calculator" heading and two input fields: one for the "Bill Amount (in dollars)" and another for the "Tip amount (as a %)."

3. Enter the bill amount in dollars (e.g., 25.99) in the first input field.

4. Enter the tip amount as a percentage (e.g., 9) in the second input field.

5. Click the "Calculate Tip and Total Bill" button to see the calculated results.

6. The web page will display the "Total tip" and "Total bill with tip" amounts below the button.

7. The "Total tip" shows the calculated tip amount based on the bill and tip percentage.

8. The "Total bill with tip" shows the grand total, including the original bill amount and the calculated tip.

## Code Details

The implementation uses HTML, CSS, and JavaScript to create an interactive tip calculator.

### HTML and CSS

The HTML file provides the structure of the web page, including the "Tip Calculator" heading, two input fields for bill amount and tip percentage, and the "Calculate Tip and Total Bill" button. Additionally, it defines two empty `<div>` elements with the classes `tip-amount` and `total-with-tip`, where the calculated results will be displayed.

The CSS in the `<style>` section adds some basic styling to the elements, using Bootstrap classes for layout and design.

### JavaScript Logic

The JavaScript code inside the `<script>` tag defines a function `calculate()` responsible for calculating the tip and updating the results on the page.

When the "Calculate Tip and Total Bill" button is clicked, the `calculate()` function is called.

The function retrieves the values entered by the user for the bill amount and tip percentage using `document.getElementById()` and `Number()`. It then calculates the total tip and the total bill with the tip, rounding the results to two decimal places using `.toFixed(2)`.

The calculated tip and total bill amounts are then displayed on the web page by updating the content of the corresponding `<div>` elements using `document.querySelector()` and `innerHTML`.
