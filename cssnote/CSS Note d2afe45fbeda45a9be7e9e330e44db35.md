# CSS Note

CSS (Cascading Style Sheets) is a stylesheet language used for describing the look and formatting of a document written in HTML. It allows developers to control the visual appearance of elements on a webpage, such as colors, fonts, layout, and more.

In the provided list, you can find some commonly used CSS selectors that help target specific elements and apply styles to them. CSS selectors are used to specify which elements in an HTML document should be styled.

If you want to apply CSS styles to your webpage, you can use these selectors along with various CSS properties to achieve the desired visual effects.

Remember, CSS is a powerful tool that adds style and enhances the presentation of your webpages, making them more visually appealing and user-friendly.

## Css Element

1. Selector: `` - Selects all elements on the page
2. Selector: `element` - Selects all elements of a specific type (e.g., `div`, `p`, `h1`, etc.)
3. Selector: `.class` - Selects all elements with a specific class
4. Selector: `#id` - Selects an element with a specific ID

<aside>
💡 CSS selectors

1. Selector: `:nth-child(odd)` - Selects odd-numbered child elements
2. Selector: `:nth-child(even)` - Selects even-numbered child elements
3. Selector: `:nth-child(2n)` - Selects every second child element
4. Selector: `:nth-child(2n+1)` - Selects every odd-numbered child element
5. Selector: `:nth-child(3n)` - Selects every third child element
6. Selector: `:nth-child(3n+1)` - Selects every element that leaves a remainder of 1 when divided by 3
7. Selector: `:nth-child(3n+2)` - Selects every element that leaves a remainder of 2 when divided by 3

These additional CSS selectors allow for more precise targeting of elements and offer more flexibility in applying styles to your webpages.

</aside>

1. Selector: `element.class` - Selects all elements of a specific type with a specific class
2. Selector: `element, element` - Selects multiple elements
3. Selector: `element > element` - Selects direct child elements
4. Selector: `element + element` - Selects the next sibling element
5. Selector: `element ~ element` - Selects all sibling elements
6. Selector: `:hover` - Selects an element when the user hovers over it
7. Selector: `:active` - Selects an element when it is being activated (e.g., clicked)
8. Selector: `:visited` - Selects a link that has been visited by the user
9. Selector: `:focus` - Selects an element when it has focus
10. Selector: `:first-child` - Selects the first child element of its parent
11. Selector: `:last-child` - Selects the last child element of its parent
12. Selector: `:nth-child(n)` - Selects the nth child element of its parent
13. Selector: `:nth-last-child(n)` - Selects the nth child element counting from the last child
14. Selector: `:nth-of-type(n)` - Selects the nth element of its type
15. Selector: `:nth-last-of-type(n)` - Selects the nth element of its type counting from the last element
16. Selector: `:first-of-type` - Selects the first element of its type
17. Selector: `:last-of-type` - Selects the last element of its type
18. Selector: `:only-child` - Selects an element that is the only child of its parent
19. Selector: `:only-of-type` - Selects an element that is the only element of its type
20. Selector: `:empty` - Selects an element that has no children
21. Selector: `:not(selector)` - Selects all elements that do not match the given selector

These are just a few examples of CSS selectors. There are many more available to target specific elements and create custom styles for your webpages.

## Difference between Margin and Padding in CSS

Margin and padding are two important concepts in CSS that define the spacing around elements on a webpage. Here is the difference between them:

- **Margin**: Margin is the space outside an element. It creates space between the element and adjacent elements. Margins do not have a background color and are transparent. Margins can be set using properties like `margin-top`, `margin-bottom`, `margin-left`, and `margin-right`.
- **Padding**: Padding is the space inside an element. It creates space between the element's content and its border. Padding can have a background color and is visible within the element. Padding can be set using properties like `padding-top`, `padding-bottom`, `padding-left`, and `padding-right`.

In summary, margins create space outside an element, while padding creates space inside an element.

## **CSS Combinators**

A CSS selector can contain more than one simple selector. Between the simple selectors, we can include a combinator.

There are four different combinators in CSS:

- descendant selector (space)
- child selector (>)
- adjacent sibling selector (+)
- general sibling selector (~)

## **CSS Pseudo-elements**

A CSS pseudo-element is used to style specified parts of an element.

For example, it can be used to:

- Style the first letter, or line, of an element
- Insert content before, or after, the content of an element

Here is a list of some commonly used CSS pseudo-elements:

- ::first-letter: Styles the first letter of an element
- ::first-line: Styles the first line of an element
- ::before: Inserts content before the content of an element
- ::after: Inserts content after the content of an element

These pseudo-elements can be used to apply specific styles to certain parts of an element and enhance the visual appearance of your webpage.

```jsx
<!-- inline styleing -->

<li><bdi style="background-color: green;" class="name">الرجل القوي إيان</bdi>: arabic name</li>

<!-- internal styling -->

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1 {
            background-color: tomato;
           /* margin: 30px;
            padding: 30px; */
            margin-top: 30px;
            margin-left: 30px;
            margin-right: 30px;
            margin-bottom: 30px;
            padding-left: 30px;
            padding-right: 30px;
            padding-top: 30px;
            padding-bottom: 30px;
        }
aside::before {
            content: "";
            padding: 50px;
            background-color: red;
        }
    </style>
</head>
<body>

    <aside>
        <h1>This is heading text in aside Tag</h1>
        <p>This is paragraph text in aside Tag</p>
    </aside>
</body>

</html>

```