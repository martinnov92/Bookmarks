# Tips and tricks

**Index**

1. [Set focus on `<div>` with JS](#set-focus-on-div-with-js)
2. [Buffering HTML5 video with JS](#buffering-html5-video-with-js)

## Set focus on `<div>` with JS

To make div focusable with JS we have to set tabindex on HTML element,
then we can focus and blur div with JS.

**Example:**

```js
    // focus element
    htmlElement.focus();

    // blur element
    htmlElement.blur();
```

## Buffering HTML5 video with JS

[Article about this topic on MDN](https://developer.mozilla.org/en-US/Apps/Fundamentals/Audio_and_video_delivery/buffering_seeking_time_ranges)