1. Variables

Used for storing and reusing values, making it easier to maintain consistent styles throughout your project.
Used in config.scss for defining font families and colors.

2. Mixins

Reusable blocks of styles that can be included in other selectors.
Used in header-container.scss for setting the background color and text color, and in header.scss for setting the background color.

3. Functions

Custom functions that can be used to calculate values based on input.
Used in config.scss for set-text-color, which returns a text color based on the lightness of the background color.

4. Placeholder Selectors (% placeholders)

A way to define a set of styles that can be extended (included) by other selectors.
Used in header.scss to define %text-properties, which is then extended by h1, h2, and .small-heading.

5. Nesting

Allows you to nest selectors inside other selectors to create a more structured and organized stylesheet.
Used throughout the files to nest selectors under parent elements.

6. Import

Used to import other SCSS files, making it possible to split your styles into smaller, manageable pieces.
Used in your styles.scss to import various SCSS files.

7. Extend

Allows one selector to inherit the styles of another, useful for keeping your styles DRY (Don't Repeat Yourself).
Used in header.scss to extend the %text-properties placeholder.

8. Interpolation

Used to embed variables or expressions within a selector or property.
Not explicitly used in the provided code, but it's a powerful feature for dynamic selector and property names.

9. For Loop :

Used a @for loop in your header.scss file to create styles for different heading levels (h1, h2, .small-heading).
It's used to set text properties like text-align, font-family, and font-weight for these headings.