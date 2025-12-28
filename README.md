# الفتوحات المكية | Al-Futuhat al-Makkiyya

**The Meccan Revelations** by Shaykh al-Akbar Muhyi al-Din Ibn Arabi (560-638 AH / 1165-1240 CE)

A multi-language digital edition featuring the complete 561 chapters in Arabic, English, Urdu, and Farsi.

## 🌐 Live Website

Visit: [https://taha23hasnain.github.io/futuhat-makkiyya](https://taha23hasnain.github.io/futuhat-makkiyya)

## 📖 Features

- **4 Languages**: Arabic (original), English, Urdu, and Farsi translations
- **561 Chapters**: Complete text of Al-Futuhat al-Makkiyya
- **Lazy Loading**: Only loads content when needed for fast performance
- **Responsive Design**: Works on desktop and mobile devices
- **Keyboard Navigation**: Use arrow keys to navigate between chapters
- **URL Sharing**: Direct links to any chapter in any language
- **Offline Capable**: Once loaded, works without internet

## 🚀 Deployment to GitHub Pages

1. Create a new GitHub repository (e.g., `futuhat-makkiyya`)

2. Push the `website` folder contents:
   ```bash
   cd website
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/futuhat-makkiyya.git
   git push -u origin main
   ```

3. Enable GitHub Pages:
   - Go to repository Settings → Pages
   - Source: Deploy from a branch
   - Branch: `main` / `root`
   - Click Save

4. Your site will be live at `https://YOUR_USERNAME.github.io/futuhat-makkiyya`

## 📁 Structure

```
website/
├── index.html          # Main HTML file
├── data/
│   ├── index.json      # Chapter index (titles only)
│   └── baab_XXX.json   # Individual chapter files (0-560)
└── export_to_json.py   # Script to regenerate JSON from SQLite
```

## 🔄 Updating Translations

If you update the SQLite database, regenerate the JSON files:

```bash
cd website
python export_to_json.py
```

## ⚠️ Disclaimer

Translations are AI-generated for scholarly and educational purposes. They should not be considered authoritative religious texts. Always refer to the original Arabic for authentic understanding.

## 📜 About the Text

**Al-Futuhat al-Makkiyya** (الفتوحات المكية) - "The Meccan Revelations" - is the magnum opus of the great Sufi master Ibn Arabi. Written over a period of 30 years, it is one of the most comprehensive works on Islamic mysticism ever composed, spanning topics from metaphysics and cosmology to ethics and spiritual practice.

## 📄 License

This project is for educational and non-commercial use only.
