# alpine-validation

Form validation directive for AlpineJS.

Aims for compatibility with the [built-in form validation](https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Forms/Form_validation#using_built-in_form_validation) of standard [HTML5 input types](https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Forms/HTML5_input_types).
- Sets `novalidate` on the form if JavaScript is supported
- Falls back to built-in form validation if JavaScript is disabled
- Styling with standard CSS pseudo-classes, same as built-in form validation
