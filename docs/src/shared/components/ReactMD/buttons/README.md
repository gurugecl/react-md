There are four types of buttons in react-md:
- flat
- raised
- icon
- floating

All of these types can be styled using the primary, secondary, or theme's colors. `flat` and `icon` buttons
will theme the text color in the button while `raised` and `floating` will theme the background of the button.

You can also create a link with all the styles of the button by providing an `href` prop to any of the buttons.
They will be updated to render as an `<a>` tag instead of a `button`.

When a button is disabled, any theming will be removed and any interactions will be removed.
