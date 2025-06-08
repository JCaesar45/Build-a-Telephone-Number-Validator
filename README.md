```markdown
# 📞 US Telephone Number Validator

A simple web app that checks whether a given string is a valid US phone number. This project fulfills all [FreeCodeCamp Telephone Validator](https://telephone-number-validator.freecodecamp.rocks) user stories and adds a personal, clean UI.

---

## 🔍 Features

- Validates multiple US phone number formats:
  - `555-555-5555`
  - `(555)555-5555`
  - `1 (555) 555-5555`
  - `5555555555`
  - and more
- Country code must be `1` if provided.
- Invalid formats and symbols are rejected.
- Interactive buttons for validation and clearing results.
- Responsive, modern design.

---

## 📂 File Structure

``

project-folder/
│
├── index.html         # Main HTML structure
├── style.css          # Disneyland-themed styling
└── script.js          # JavaScript logic and validation

``

---

## 🚀 Getting Started

To run this project locally:

1. Clone the repository or download the files.
2. Open `index.html` in your browser.

> No build tools, frameworks, or dependencies needed.

---

## ✅ Valid Examples

- `555-555-5555`
- `(555)555-5555`
- `5555555555`
- `1 555 555 5555`
- `1(555)555-5555`

---

## ❌ Invalid Examples

- `555-5555`
- `123**&!!asdf#`
- `11 555-555-5555`
- `(275)76227382`
- `2(757)622-7382`

---

## 📦 Functional Elements

| Element ID      | Purpose                             |
|-----------------|-------------------------------------|
| `user-input`    | Input field for phone number        |
| `check-btn`     | Button to validate the input        |
| `clear-btn`     | Button to clear validation result   |
| `results-div`   | Displays the validation result text |

---

## 🧠 Logic Behind Validation

Uses regular expressions and basic string cleaning:

```js
/^(1\s?)?(\(\d{3}\)|\d{3})([\s-]?)\d{3}([\s-]?)\d{4}$/
``

* Allows optional `1` as the country code.
* Accepts numbers with or without dashes, spaces, or parentheses.
* Rejects extra digits, invalid characters, and misplaced symbols.

---

## 🎨 Styling

* Responsive layout
* Rounded input and buttons
* Soft color palette inspired by Disneyland
* Hover effects for buttons

---

## 📃 License

This project is open-source and free to use.

---

## 🙌 Contributing

Feel free to fork, improve, or suggest features via pull requests or issues!

---

```
