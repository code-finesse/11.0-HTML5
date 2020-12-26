In HTML, the `<form></form>` element represents a document section containing interactive controls for submitting information.

- Any button without a type attribute, or any button or input element with the an attribute of `type="submit"` will cause a submit event to be fired.
- By default, when forms are submitted they will cause the page to reload in HTML.
- In order to prevent the page from reloading, you should listen for the submit event using JavaScript and make sure to call the preventDefault method on the event.

```html
    <form>
    <!-- Connect every field to a label using the `for` attribute -->
    <!-- The `id` of the input uniquely connects the label and input -->
      <label for="email">Email:</label>
      <input id="email" type="email" />
      <label for="password">Password:</label>
      <input id="password" type="password" />
    </form>
```