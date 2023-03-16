# Getting Started

You need to have a somewhat recent NodeJS version installed.

```shell
$ yarn install
$ yarn dev
```

Then open `http://localhost:5173/` in your browser. You should see an autocomplete box.

# The Problem

1. Click on the input field, the suggestions should pop up at the bottom
2. Hover the mouse over "Pulp Fiction", or any other suggestion value
3. Hit enter
4. You should now see what was "submitted", which is the suggestion you hovered over

I want to only submit the following values:
* Select a suggestion and press enter
* Click a suggestion
* Type in the input field, press enter

In other words, never submit a suggestion that was only hovered over.

All other default behavior of the component should be preserved.
