# Case-Sensitive innerHTML Access in HTML

This example demonstrates a common, yet easily overlooked, error in HTML JavaScript interaction. The issue stems from a case-sensitive error when accessing the `innerHTML` property of a div element using JavaScript.

## The Bug

The `innerHtml` property is often incorrectly written as `innerHtml` (lowercase 'h'). This code will not produce an error but will not modify the div's content because the property does not exist.   The correct property is `innerHTML` (uppercase 'H').

## Solution

The solution involves using the correct casing for the `innerHTML` property.