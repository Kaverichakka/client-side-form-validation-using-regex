# 🔐 Login Page with Bootstrap & JavaScript Validation

A responsive login form built using **HTML5**, **Bootstrap 5**, and **JavaScript**, featuring real-time form validation using **Regular Expressions (Regex)** and dynamic UI feedback.

## 🚀 Features

- 🎨 Modern and responsive UI using Bootstrap 5
- ✅ Real-time input validation using JavaScript
- 🧠 Validations using regex for:
  - Username (alphanumeric, 3–16 characters)
  - Gmail only (`@gmail.com`)
  - Password (min 6 chars, includes uppercase, lowercase, digit)
  - Confirm password (matches original password)
  - Phone number (10 digits, starts with 6–9)
- 🧪 Optional phone number field
- 🔴 Highlights invalid fields with red border
- 🔵 Highlights focused fields with blue border
- 🧼 Form resets and displays alert on successful submission

## 📂 File Structure

```
project-folder/
├── index.html         # Main HTML page with embedded CSS and JS
├── README.md          # Project documentation (this file)
```

## 🖥️ Technologies Used

- HTML5
- CSS3
- Bootstrap 5 (via CDN)
- Vanilla JavaScript (no external libraries)

## 📸 Preview

> Add a screenshot here if available (optional)

## ✅ Validation Rules

| Field               | Rule                                                                 |
|--------------------|----------------------------------------------------------------------|
| Username           | Alphanumeric, 3–16 characters                                        |
| Gmail              | Must be a valid Gmail ID ending with `@gmail.com`                   |
| Password           | At least 6 characters, includes uppercase, lowercase, and number     |
| Confirm Password   | Must match the password field                                        |
| Phone Number       | Must be 10 digits and start with 6, 7, 8, or 9                        |

## 📦 How to Use

1. Clone the repository or download the `index.html` file.
2. Open `index.html` in a modern web browser.
3. Fill the form fields. Real-time validation will guide you.
4. Submit the form and get a success alert if all inputs are valid.

```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
open index.html
```

## 🛠️ Customization

- You can expand this form to include backend integration using PHP, Node.js, or any backend framework of your choice.
- Add features like "Remember Me", password visibility toggle, or CAPTCHA for improved security.

