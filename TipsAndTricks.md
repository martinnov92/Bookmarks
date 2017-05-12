# Tips and tricks

**Index**

1. [Set focus on `<div>` with JS](#set-focus-on-div-with-js)
2. [Buffering HTML5 video with JS](#buffering-html5-video-with-js)
3. [How to make simple typing file](#how-to-make-simple-typing-file)
4. [How to make NPM package](#how-to-make-npm-package)
5. [Support Hot Reload in React](#support-hot-reload-in-react)

---------

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

## How to make simple typing file

// todo

## How to make NPM package

// todo

## Support Hot Reload in React

Add 

```js
    if (module.hot) {
    module.hot.accept();
    }
```

in index.tsx

## JS notes

self === window - always, unless reassigned