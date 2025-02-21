# alpine-validation

Form validation directive for Alpine.js

Compatible with [built-in form validation](https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Forms/Form_validation#using_built-in_form_validation).

Use the same validation attributes as built-in validation
- **required**: Specifies whether a form field is required
- **minlength and maxlength**: Min and max length of textual data (strings)
- **min, max, and step**: Min and max values of numerical inputs, and the step (increment)
- **type**: Can be a number, an email address, or other preset types
- **pattern**: Regular expression specifies a pattern that the data must match

Still works when JavaScript is disabled
- Sets `novalidate` on the form if JavaScript is supported
- Falls back to built-in validation if JavaScript is disabled
- Styling with standard CSS pseudo-classes, same as built-in validation

Supports all standard [HTML5 input types](https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Forms/HTML5_input_types)


## Examples

**TODO** Serve examples with deno

`deno.json` is the deno config file is 

Run the program
```bash
deno run main.ts
```

Run and watch for file changes
```bash
deno task dev
```


## Testing

**TODO** Create tests

Run the tests
```bash
deno test
```


## Package

The package is hosted on [JSR](https://jsr.io/docs/introduction): *"a modern package registry for JavaScript and TypeScript. JSR works with many runtimes (Node.js, Deno, Bun, browsers, and more) and is backwards compatible with npm"*

`jsr.json` is the JSR config file. Using a separate file instead of just setting the properties in deno.json

Publish module to JSR
```bash
deno publish
```

