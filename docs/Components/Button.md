---
id: button-component
title: Button
sidebar_label: Button
---

## Button Component

The Button component is a customizable button element that can be used in your React applications.

### Props

The Button component accepts the following props:

| Name      | Type                          | Default | Description                                     |
| --------- | ----------------------------- | ------- | ----------------------------------------------- |
| label     | string                        | -       | The label text displayed on the button.         |
| className | string                        | -       | The CSS class name(s) for custom styling.       |
| onClick   | (e: React.MouseEvent) => void | -       | Event handler function for button click events. |
| loader    | boolean                       | false   | Determines whether to show a loader animation.  |

### Usage

To use the Button component, import it into your React component and include it in your JSX markup.

```jsx
import Button from "../path/to/Button";

<Button
  label="Click me"
  className="Primary-Active"
  onClick={handleClick}
  loader={isLoading}
/>;
```
