# QR Code Generator

This project is an **interactive web application** that allows users to **generate QR codes** for any URL directly in the browser.  
It aims to provide a **simple and fast QR code generator** without any backend.

---

## Live Demo

You can view the live version of the project here:  
[Live Demo Link](#) 

---

## Features

- **Generate QR Code** — Users can enter any **valid URL** to generate a QR code.  
- **Instant Display** — QR codes appear immediately after clicking the **Generate** button.  
- **Responsive Design** — Works across desktop, tablet, and mobile devices.  
- **Simple & Lightweight** — No backend or database required.

---

## Technologies Used

- **HTML5** — Page structure and form input.  
- **CSS3** — Styling and layout.  
- **Tailwind CSS** — Modern, responsive design.  
- **JavaScript (ES6)** — Handles QR code generation and display.  
- **QRCode.js** — Library used to create QR codes in the browser.

---

## Project Structure

```
QR-Code-Generator/
│
├── css/style.css
├── js/script.js
└── index.html
```

---

## How It Works

1. The user enters a **URL** in the input field.  
2. Clicking the **Generate QR Code** button triggers the `generateQRCode()` function.  
3. JavaScript uses **QRCode.js** to create a QR code and display it in the page.  
4. The generated QR code is displayed instantly without reloading the page.

---

## Getting Started

1. **Clone or download** this repository.  
2. Open `index.html` in your browser.  
3. Enter a **URL** in the input field.  
4. Click **Generate QR Code** to see the QR code appear.

---

## Folder Details

| File / Folder | Description |
|----------------|--------------|
| `index.html` | The main webpage structure |
| `css/style.css` | Contains all styles and layout |
| `js/script.js` | Handles QR code generation and display |

---

## Future Improvements

- Add **download option** for the generated QR code.  
- Support **custom QR code size and colors**.  
- Include **scan history** for previously generated QR codes.  
- Add **mobile-friendly enhancements** for easier scanning.

---

## License

This project is **open-source** and free to use, modify, or share for educational and non-commercial purposes.  
Developed by **Shorouk Khaled**.

