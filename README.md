# gatsby-theme-ghost-medium-zoom 👀

> Bring [medium-zoom](https://github.com/francoischalifour/medium-zoom) to gatsby-theme-try-ghost.

## Install

```
yarn add gatsby-theme-ghost-medium-zoom
```

## How to use

```js
// In your gatsby-config.js, under gatsby-transformer-remark plugins

plugins: [
{
  resolve: `gatsby-theme-ghost-medium-zoom`,
}
];
```

## Configuration

All options from [medium zoom](https://github.com/francoischalifour/medium-zoom) are available:

| Property       | Type                                  | Default  | Description                                      |
| -------------- | ------------------------------------- | -------- | ------------------------------------------------ |
| `margin`       | `number`                              | `0`      | The space outside the zoomed image               |
| `background`   | `string`                              | `"#fff"` | The background of the overlay                    |
| `zIndex`       | `number`                              | `42`     | The z-index of the overlay                       |
| `scrollOffset` | `number`                              | `40`     | The number of pixels to scroll to close the zoom |
| `container`    | `string` \| `HTMLElement` \| `object` | `null`   | The viewport to render the zoom in               |
| `template`     | `string` \| `HTMLTemplateElement`     | `null`   | The template element to display on zoom          |
