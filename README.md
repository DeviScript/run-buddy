# Project Documentation

## HTML Notes

### Doctype Declaration

- **`<!DOCTYPE html>`**: Informs the web browser about the type and version of HTML used.

### Root Element

- **`<html lang="en">`**: The root element of the HTML document.
  - **Attribute**: `lang` with value `en` (English).

### Head Tag

- **`<head>`**: Contains meta-information about the document.

### Meta Tag

- **`<meta charset="UTF-8" />`**: Metadata element.
  - **Attribute**: `charset` with value `UTF-8`.

### Title Tag

- **`<title>Run Buddy</title>`**: Specifies the title of the document.

### Link Tag

- **`<link rel="stylesheet" href="./assets/css/style.css" />`**: Used to link external resources.
  - **Attributes**:
    - `rel` with value `stylesheet`.
    - `href` with the path to the CSS file.

## Definition of an HTML Attribute

An attribute in HTML is a modifier of an HTML element that provides additional information about the element. It is incorporated within the opening tag of the element and typically consists of a name and a value pair, formatted as `name="value"`. Attributes play a crucial role in HTML, serving various purposes such as specifying source URLs for images, setting actions for forms, defining styles, and more. They enhance the functionality and define the behavior of HTML elements.

For instance, consider the HTML tag `<img src="image.jpg" alt="Description">`. In this example, `src` and `alt` are attributes. The `src` attribute specifies the path of the image, while the `alt` attribute provides an alternative text description of the image, which is particularly useful for accessibility and in situations where the image cannot be displayed.

## CSS Notes

### CSS Syntax Explanation

```css
/* CSS Rule: 
   The entire block below is a CSS rule, which defines the styles for the elements selected by the selector. */

body {
  /* Selector: 
       The part before the curly braces ('body') is the selector.
       It identifies the HTML elements to which the CSS rule applies.
       In this case, it targets the <body> tag of the HTML document. */

  /* Declaration 1: */
  color: #39a6b2; /* Property: 'color'
                       Refers to a predefined style characteristic of the element.
                       Property Value: '#39a6b2'
                       Specifies the color value in hexadecimal format for the text of the body element. */

  /* Declaration 2: */
  font-family: Helvetica, Arial, sans-serif; /* Property: 'font-family'
                                                  Refers to a predefined style characteristic of the element.
                                                  Property Value: 'Helvetica, Arial, sans-serif'
                                                  Specifies the font family for text in the body element. */
}
```

_CSS Box Model Visualization:_
![CSS Box Model Diagram](assets/images/103-box-model.jpg "CSS Box Model")
_A diagram showing nested boxes labeled Margin, Border, Padding, and Content (from outside to inside)._

### Additional Notes on CSS Box Model

**CSS Box Model:** 
- All HTML elements can be represented by a rectangular box, known as the CSS box.
- The CSS Box Model visually represents the properties of the CSS box, which include content, padding, border, and margins, layered like an onion.

**Content:**
- The innermost box inside the CSS box that contains text and nested elements.
- Its size is determined by the 'height' and 'width' properties.

**Padding:**
- Inside margin of the CSS box, surrounding the content.
- The size of padding can be specified for each of the four sides.

**Border:**
- Surrounds the padding and lies between the margin's inner edge.
- Sides, size, and styles can be modified (e.g., border-bottom, border-style, border-top-color).
- Requires line weight, style, and color for rendering.

**Margin:**
- Similar to padding but outside the box.
- Creates space outside the box, affecting nearby HTML elements.
- Specified using top, right, bottom, left values.

