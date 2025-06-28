# Quote Generation App

A modern, multi-language quote generator built with Next.js, React, and Tailwind CSS. Instantly get motivational quotes in English, Russian, or Armenian, with beautiful dynamic backgrounds. Save your favorite quotes, switch languages, and enjoy a clean, responsive UI.

---

## 🚀 Features

- 🌍 **Multi-language**: English 🇺🇸, Russian 🇷🇺, Armenian 🇦🇲
- 🖼️ **Dynamic Backgrounds**: Random mountain/ocean/landscape images for every quote
- 💾 **Quote Saving**: Save, view, and delete your favorite quotes
- 🗑️ **Quote Management**: Remove individual or all saved quotes
- 📱 **Responsive Design**: Works perfectly on all devices
- ⚡ **Fast & Modern**: Built with Next.js 14, React 18, and Tailwind CSS

---

## ✨ Demo

[Live on Vercel](https://your-vercel-app-url.vercel.app) <!-- Replace with your actual deployed URL -->

---

## 🛠️ Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/LauraVibe/quote-generation.git
cd quote-generation
```

### 2. Install dependencies
```bash
npm install
```

### 3. Run locally
```bash
npm run dev
```
Visit [http://localhost:3000](http://localhost:3000)

---

## 🌐 Language Support
- Click a flag to instantly switch between English, Russian, and Armenian quotes
- Each saved quote remembers its language

---

## 🖼️ Background Images
- Uses [Picsum Photos](https://picsum.photos/) for random landscapes by default
- For higher quality, set up an Unsplash API key:
  1. Get a free key at [Unsplash Developers](https://unsplash.com/developers)
  2. Add `UNSPLASH_ACCESS_KEY=your_key` to your Vercel/production environment

---

## 🏗️ Project Structure

```
app/
  api/quotes/           # API routes for quotes
  api/quotes/saved/     # API routes for saved quotes
  globals.css           # Tailwind global styles
  layout.tsx            # App layout
  page.tsx              # Main page
hooks/
  useQuotes.ts          # Custom React hook for quote logic
lib/
  quoteStore.ts         # In-memory quote store
next.config.js          # Next.js config
vercel.json             # Vercel deployment config
```

---

## 🧑‍💻 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

[MIT](LICENSE)

---

## 🙏 Acknowledgments
- [Quotable API](https://api.quotable.io/) for English quotes
- [Picsum Photos](https://picsum.photos/) and [Unsplash](https://unsplash.com/) for images
- Next.js, React, and Tailwind CSS communities

---

## 💡 Inspiration

This project was built to inspire users with motivational quotes in their native language, with a beautiful and modern UI. Enjoy and share positivity!