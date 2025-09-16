# Vite-template-React

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.


---

### Windows (`PowerShell`) uchun:
```powershell
@"
# ⚡ Vite + React Template

Minimal va tezkor **React** + **Vite** starter loyihasi 🚀.
Ushbu template HMR (Hot Module Replacement) va `ESLint` qoidalari bilan birga keladi.

---

## 📦 Texnologiyalar

- ⚛️ **React 18**
- ⚡ **Vite**
- 🛠 **ESLint** (kod sifati uchun)
- 🎨 **CSS / SCSS** (yoki xohlagan styling kutubxonangiz)
- 🔥 HMR (Hot Module Replacement)

---

## 🚀 Loyihani ishga tushirish

\`\`\`bash
# 1. Loyihani klonlash
git clone https://github.com/username/vite-template-react.git

# 2. Loyihaga kirish
cd vite-template-react

# 3. Kerakli paketlarni o‘rnatish
npm install

# 4. Development serverni ishga tushirish
npm run dev
\`\`\`

Brauzerda: 👉 [http://localhost:5173](http://localhost:5173)

---

## 🛠 Scripts

- \`npm run dev\` – development rejimida ishga tushirish
- \`npm run build\` – production uchun build yaratish
- \`npm run preview\` – build qilingan loyihani preview qilish
- \`npm run lint\` – ESLint orqali kodni tekshirish

---

## 📂 Papka tuzilmasi

\`\`\`
vite-template-react/
├── node_modules/
├── public/           # Statik fayllar
├── src/
│   ├── assets/       # Rasm, ikonka, style va h.k.
│   ├── components/   # React komponentlari
│   ├── App.jsx       # Asosiy App komponenti
│   ├── main.jsx      # Entry point
├── .eslintrc.cjs     # ESLint konfiguratsiyasi
├── index.html        # HTML template
├── package.json
└── vite.config.js    # Vite konfiguratsiyasi
\`\`\`

---

## ⚙️ Rasmiy React plaginlari

Hozircha ikkita rasmiy plugin mavjud:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react) → **Babel** orqali Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) → **SWC** orqali Fast Refresh

---

## 📘 TypeScript qo‘llab-quvvatlashi

Agar siz **production** darajadagi ilova ishlab chiqmoqchi bo‘lsangiz,
**TypeScript** va \`typescript-eslint\` dan foydalanishni tavsiya qilamiz.

👉 [React + TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts)

---

## 📝 Litsenziya

MIT litsenziyasi ostida tarqatiladi.
"@ | Set-Content -Path README.md
