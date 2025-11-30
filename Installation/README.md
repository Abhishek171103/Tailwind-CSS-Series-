# ✅ Installation Process  
**How to Install Tailwind CSS in Create React App?**

---

## 1️⃣ Create React App Install karo
```bash
npx create-react-app my-app
cd my-app
```

## 2️⃣ Tailwind + Required Packages Install karo
```bash
npm install -D tailwindcss postcss autoprefixer
```

## 3️⃣ Tailwind Config Initialize karo
```bash
npx tailwindcss init -p
```

## ✔️ Ye command 2 files banayegi:

- tailwind.config.js
- postcss.config.js

## 4️⃣ Tailwind ko project ke paths batana
tailwind.config.js file me ye content rakho:

```js
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    "*",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

## 5️⃣ Tailwind CSS ko import karo
src/index.css open kar ke sab delete karo aur ye add karo:

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```
## 6️⃣ App run karo
```bash
npm start
```