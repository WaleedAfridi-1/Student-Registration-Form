# Student-Registration-Form
A Student Registration Form built with pure HTML and CSS. This project includes form fields for personal details, validation for phone number and email, and a modern dark-themed UI with hover effects.


# Student Registration Form

A sleek and modern **Student Registration Form** built using pure **HTML & CSS**. This project provides a stylish UI, form validation,  no JavaScript frameworks or external libraries used.

🚀 **Live Demo**:  
[View it on Netlify](https://gorgeous-yeot-035647.netlify.app/)

---

## Table of Contents

- [Features](#features)    
- [Technologies Used](#technologies-used)  
- [Folder Structure](#folder-structure)  
- [Usage](#usage)  
- [Customization](#customization)  
- [Validation](#validation)  
- [Future Improvements](#future-improvements)  
- [Contribution](#contribution)  
- [License](#license)  

---

## Features

- Modern **dark-themed UI** with hover effects  
- Clean layout with consistent styling  
- Form validation for:
  - Phone number: **exactly 11 digits**, only numeric  
  - Email: proper email format  
- Stylish buttons, inputs, and table interactions  
- Pure **HTML + CSS**, no JS frameworks or external CSS libs  

---

## Technologies Used

- **HTML5**  
- **CSS3**  
  - Flexbox / centering  
  - Box shadows, transitions, hover states  
  - Dark UI color palette  

---

## Folder Structure

```
student-registration-form/
├── index.html
├── README.md

```



---

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/WaleedAfridi-1/Student-Registration-Form.git
   ```
2. Enter the project folder:
   ```bash
   cd Student-Registration-Form
   ```
3. Open `index.html` in your browser (double-click or via Live Server).  
4. To view the live version, visit:  
   https://gorgeous-yeot-035647.netlify.app/

---

## Customization

- **Color scheme** — Change the color variables (background, accent, hover) in CSS  
- **Fonts** — Use Google Fonts or custom fonts by importing them  
- **Layout / Responsiveness** — Adjust breakpoints for mobile or tablet  
- **Add JS** — If you ever want dynamic behavior (e.g. input auto-formatting)  

---

## Validation

- **Phone number input** uses attributes:
  ```html
  <input type="tel"
         required
         pattern="[0-9]{11}"
         maxlength="11"
         minlength="11"
         placeholder="03XXXXXXXXX">
  ```
  This ensures exactly **11 numeric digits**.
- **Email input** uses `type="email"` for browser-level validation.

If the input doesn’t match, the browser will show an error and prevent submission.

---

## Future Improvements & To-Do

- Add **JavaScript validation & feedback** (e.g. show inline error messages)  
- Make the form **fully responsive** (optimize mobile layout)  
- Integrate with a backend (PHP / Node.js / Python) to **submit data**  
- Add **accessibility improvements** (ARIA labels, focus styles)  
- Option for **theme switching** (dark / light mode)  

---

## Contribution

Contributions are welcome!  
If you find a bug or want to add a feature, do the following:

1. Fork the repository  
2. Create a new branch: `git checkout -b feature-name`  
3. Make your changes and commit: `git commit -m "Add new feature"`  
4. Push to your fork: `git push origin feature-name`  
5. Create a Pull Request here

---

## License

This project is open-sourced under the **MIT License**. Feel free to use, modify, and distribute it.

---

### Author

Waleed Afridi  
Built with ❤️ using HTML & CSS
