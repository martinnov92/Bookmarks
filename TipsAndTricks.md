# Tips and tricks

**Index**

1. [Set focus on `<div>` with JS](#focusDivWithJS)

## Set focus on `<div>` with JS {#focusDivWithJS}

To make div focusable with JS we have to set tabindex on HTML element,
then we can focus and blur div with JS.

**Example:**

```js
    // focus element
    htmlElement.focus();

    // blur element
    htmlElement.blur();
```