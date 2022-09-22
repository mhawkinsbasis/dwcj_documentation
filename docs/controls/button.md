---
sidebar_position: 2
---

# Button

### Description

This button control object provides methods for creating and manipulating a button in applications
or webpages. The button's behavior can be modified with the methods below, and is customizable 
with various themes, styles and expanses.

### Methods

| Method Name | Description | Parameters | Returns |
|-------------|-------------|:----------:|:-------:|
| Button() | Constructor for the Button control. May be passed no parameters, or a single String which will display as text on the Button. | `()` OR <br/> `(String text)` | N/A |
| doClick() | Performs a click action - mainly used for testing purposes. | N/A | N/A |
| getDisableOnClick() | Returns whether or not the button will be disabled when clicked on. | N/A | ` boolean` |
| getDisableOnClick() | Sets whether or not the button will be disabled when clicked on. | `(boolean disable)` | `Button` |
| onClick() | Function that registers a click on the button. Needs to take the function signature of a separate function which can be written to handle the click. An example function signiture might be `button.onClick(this::buttonPushHandlerFunction)` where the buttonPushHandlerFunction is later defined in your program. The signature of that function may look something like this: `buttonPushHandlerFunction(ButtonPushEvent ev){ //code inside here }`  | `(Consumer<ButtonPushEvent> callback)` | `Button` |
| setDisableOnClick() | Sets whether or not you want to disable the button when clicked on. | `(boolean disabled)` | `Button` |

### Themes

The following themes are supported for use with the button control: <br/><br/>![various button themes](./_images/button_themes.jpg)

<br/>Theming is supported by use of a built-in enum class. To apply a theme, execute code similar to the following: <br/><br/>

    import org.dwcj.controls.*;                        //Contains the button control
    import org.dwcj.controls.IThemable.Theme;          //Contains the Theme enum object

    Button exampleButton = new Button("Example");      //Creates a new button with the text "example"
    exampleButton.setTheme(Theme.DEFAULT);             //Sets the button's theme to be the default theme.

### Expanses

The following expanses are supported for use with the button control: <br/><br/>![various button expanses](./_images/button_expanses.jpg)

<br/>The various expanses are supported by use of a built-in enum class. To apply an expanse, execute code similar to the following: <br/><br/>

    import org.dwcj.controls.*;                        //Contains the button control
    import org.dwcj.controls.IExpansible.Expanse;      //Contains the Theme enum object

    Button exampleButton = new Button("Example");      //Creates a new button with the text "example"
    exampleButton.setTheme(Expanse.MEDIUM);            //Sets the button's theme to be the default theme.