# خناثة — KHANATHA

**WARDOGS Mortar & Artillery Calculator**  
**Created by H1SoK4**

حاسبة غير رسمية للعبة WARDOGS، تدعم العربية والإنكليزية، وتعمل مباشرة من المتصفح.

An unofficial, bilingual (Arabic / English) WARDOGS mortar and artillery calculator.

## Features / المميزات

- Arabic and English interface, with RTL support.
- L81 mortar and SPH-2 artillery support.
- Distance, compass bearing, and elevation calculations.
- Live results, relative target plot, and shareable links.
- Static website: no backend, database, or API.

## Run / التشغيل

Open `index.html` in your browser. No installation or build step is required.

افتح ملف `index.html` بالمتصفح مباشرة، بدون تثبيت أي برامج.

## Upload to GitHub / الرفع على GitHub

1. Create an empty public repository at https://github.com/new named `khanatha`.
2. Extract `khanatha-github.zip`.
3. In your new repository, choose **uploading an existing file** (or **Add file → Upload files**).
4. Upload **the extracted files**, not the ZIP itself.
5. Commit the changes to `main`.

## Deploy to Vercel / النشر على Vercel

1. Open https://vercel.com/new and connect GitHub.
2. Import your `khanatha` repository.
3. Choose **Other** as the Framework Preset (if prompted).
4. Use the repository root (`./`) and do not add a build command.
5. Deploy. Future updates pushed to `main` deploy automatically.

## Credits / الحقوق

- **Project and interface: H1SoK4**
- Firing table source: [apollyon-sys/wardogs-calculator](https://github.com/apollyon-sys/wardogs-calculator) — MIT attribution in `THIRD_PARTY_LICENSE.txt`.
- Not affiliated with BULKHEAD or Team17.
- Data is community-measured and assumes level ground; check in-game accuracy.

## Project structure

```text
khanatha/
├── index.html
├── README.md
├── THIRD_PARTY_LICENSE.txt
└── .gitignore
```
