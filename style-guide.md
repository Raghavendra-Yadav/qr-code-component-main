# Frontend Style Guide – QR Code Component

---

## 📐 Layout

- **Mobile width:** 375px
- **Desktop width:** 1440px

---

## 🎨 Colors

| Purpose                | Color Code           |
| ---------------------- | -------------------- |
| Background (Slate 300) | `hsl(212, 45%, 89%)` |
| Card (White)           | `hsl(0, 0%, 100%)`   |
| Title Text (Slate 900) | `hsl(218, 44%, 22%)` |
| Body Text (Slate 500)  | `hsl(216, 15%, 48%)` |

---

## 📦 Component Dimensions

### 🔹 Card Container

- **Responsive Behavior:** Hug contents (dynamic height and width)
- **Max Width:** `320px`
- **Width:** `100%` (allows scaling on small screens)
- **Height:** Auto (grows based on content)
- **Padding:** `16px` (top, left, right), `40px` (bottom)
- **Border Radius:** `20px`
- **Background Color:** White (`hsl(0, 0%, 100%)`)
- **Text Alignment:** Center

### 🔹 QR Code Image

- **Border Radius:** `10px`

### 🔹 Text Area

- **Horizontal Padding:** `16px`
- **Text Alignment:** Center

---

### Font

- **Font Family:** [Outfit](https://fonts.google.com/specimen/Outfit), sans-serif
- **Font Weights:** `400` (regular), `700` (bold)

### Body Copy

- **Paragraph Font Size:** `15px`

---

## ✅ Development Notes

- Follow **mobile-first** design approach
- Ensure elements are **centered and aligned** vertically
- Use **semantic HTML** tags (`<main>`, `<section>`, `<h1>`, `<p>`)
- Keep CSS clean and modular
- Maintain **accessibility** (alt tags, contrast, etc.)

---

## 📁 File Summary

- `index.html`: Main structure
- `style.css`: Styling
- `image-qr-code.png`: QR image asset
- `README.md`: Project description
- `style-guide.md`: This file (design specs)

---
