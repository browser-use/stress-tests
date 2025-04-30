# Browser-Use Stress Test

<img width="1972" alt="image" src="https://github.com/user-attachments/assets/da0f3d41-af7b-41dd-a134-3c1b0f019dfd" />

## Included Form Libraries

1. **Vanilla HTML + JS** - Basic HTML5 form elements with JavaScript validation
2. **jQuery + Bootstrap + Select2** - Classic form stack with enhanced select inputs
3. **AngularJS (v1)** - Angular 1.x form implementation with ng-model bindings
4. **Angular (v2+)** - Modern Angular reactive forms
5. **React Hook Form** - React-based form library using hooks
6. **TanStack Form** - Modern React form state management library
7. **Formik** - Popular form state management for React
8. **React Final Form** - High-performance React form state management
9. **Svelte Forms Lib** - Svelte-based form validation library
10. **Ember (ember-changeset-validations)** - Ember.js form implementation
11. **Vue.js (Vuelidate)** - Vue form validation library
12. **Material UI Forms** - Material Design styled form components
13. **Wufoo-style** - Intentionally difficult for autofill with unusual naming patterns

## Features

Each form includes:

- All standard HTML form input types
- Date and time pickers
- Character-restricted fields (alphanumeric only)
- Disabled fields
- Red herring modal buttons (opens a modal instead of submitting)
- Form validation
- Submit buttons

## Special Testing Cases

The Wufoo-style form is specifically designed to challenge autofill systems with:
- Unusual field naming conventions
- Nested form structures
- Non-standard input patterns
- Split fields (separate month/day/year selects)
- Honeypot fields
- Fields with prefixes/suffixes

## Usage

1. Open `index.html` in a browser
2. Test your autofill browser extension against each form
3. Check for proper field recognition and filling

## Development

This is a purely frontend project with no build steps required. All forms are self-contained in their respective HTML files.

## License

MIT
