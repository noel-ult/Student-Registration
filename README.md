# Student registration form

A single-page HTML exercise containing a registration form and a sample registered-students table. All markup is in `index.html`.

## Preview

Open `index.html` in a browser, or serve this directory with Python:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Visit http://localhost:8000. There is no package installation or build step.

## Behavior and editing

Edit the form controls and sample table directly in `index.html`. The form has no application submission handler, server endpoint, or persistence. Submitting it does not create a stored student record; the table is static example content.

Check labels, required-field behavior, keyboard navigation, and layout at narrow and wide widths after editing. No automated tests are included. Any static host can serve the file; actual registration requires a separately implemented backend and data model.

## More documentation

- [Source, command, and configuration reference](docs/REFERENCE.md)
- [Contributing](CONTRIBUTING.md)
