# الفتوحات المكية | Al-Futuhat al-Makkiyya

**The Meccan Revelations** by Shaykh al-Akbar Muhyi al-Din Ibn Arabi (560-638 AH / 1165-1240 CE)

A multi-language digital edition featuring the complete 561 chapters in Arabic, English, Urdu, and Farsi.

## 🌐 Live Website

Visit: [https://taha23hasnain.github.io/futuhat-e-makkiyya](https://taha23hasnain.github.io/futuhat-e-makkiyya)

## 📖 Features

- **4 Languages**: Arabic (original), English, Urdu, and Farsi translations
- **561 Chapters**: Complete text of Al-Futuhat al-Makkiyya
- **Lazy Loading**: Only loads content when needed for fast performance
- **Responsive Design**: Works on desktop and mobile devices
- **Keyboard Navigation**: Use arrow keys to navigate between chapters
- **URL Sharing**: Direct links to any chapter in any language
- **Offline Capable**: Once loaded, works without internet

## 🚀 Deployment to GitHub Pages

1. Create a new GitHub repository (e.g., `futuhat-e-makkiyya`)

2. Push the repository contents:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/taha23hasnain/futuhat-e-makkiyya.git
   git push -u origin main
   ```

3. Enable GitHub Pages:
   - Go to repository Settings → Pages
   - Source: Deploy from a branch
   - Branch: `main` / `root`
   - Click Save

4. Your site will be live at `https://taha23hasnain.github.io/futuhat-e-makkiyya`

## 📁 Structure

```
futuhat-e-makkiyya/
├── index.html          # Main HTML file with the reader application
├── README.md           # This documentation file
└── data/
    ├── index.json      # Chapter index (titles only)
    └── baab_XXX.json   # Individual chapter files (baab_000.json to baab_560.json)
```

### Data Files

- **index.json**: Contains the chapter index with titles in all four languages
- **baab_XXX.json**: 561 individual chapter files (numbered 000-560), each containing:
  - Chapter ID
  - Title in Arabic, English, Urdu, and Farsi
  - Full content in all four languages (with Arabic as the original text)

## ⚠️ Disclaimer

Translations are AI-generated for scholarly and educational purposes. They should not be considered authoritative religious texts. Always refer to the original Arabic for authentic understanding.

## 📜 About the Text

**Al-Futuhat al-Makkiyya** (الفتوحات المكية) - "The Meccan Revelations" - is the magnum opus of the great Sufi master Ibn Arabi. Written over a period of 30 years, it is one of the most comprehensive works on Islamic mysticism ever composed, spanning topics from metaphysics and cosmology to ethics and spiritual practice.

## 📄 License

This project is for educational and non-commercial use only.
