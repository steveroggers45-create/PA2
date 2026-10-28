# Northstar Buildathon

A responsive, single-page landing page for a proposed Northstar Campus student hackathon. It introduces the event, suggests project themes, outlines a sample schedule, and provides a registration-interest form preview.

> **Draft:** Event dates, schedule, prizes, eligibility, contact details, and registration information are proposed examples. Confirm them with the organizers before publishing or using this page for the event.

## Project contents

- `hack.html` — the Buildathon landing page, with its styles and preview-form behavior included in the file.
- `README.md` — project overview and usage notes.
- `LICENSE` — MIT License.

## Run locally

No build step, package installation, or framework is required. Open `hack.html` in a browser, or serve the project directory locally:

```bash
python -m http.server 8000
```

Then visit <http://localhost:8000/hack.html>.

## Registration form

The form is a front-end preview only. It validates required fields in the browser, but does not send or store submissions. Connect an approved registration service before accepting sign-ups.

## License

This project is distributed under the MIT License. See [`LICENSE`](./LICENSE) for the full text.
