3-Bucket Focus System — PWA
A mobile-installable focus app based on the 3-bucket method.

🚀 Deploy to Vercel in 5 minutes
Step 1 — Install Node.js
Download from https://nodejs.org (LTS version)

Step 2 — Upload to GitHub
Go to https://github.com and create a free account
Click "New repository" → name it three-bucket-app → Create
Upload all these files (drag & drop the whole folder)
Step 3 — Deploy on Vercel
Go to https://vercel.com → Sign up with GitHub
Click "Add New Project"
Import your three-bucket-app repo
Framework preset: Vite
Click Deploy — done in ~60 seconds
Your app will be live at: https://three-bucket-app.vercel.app

📱 Install as App on Phone
iPhone (Safari):
Open your Vercel URL in Safari
Tap the Share button (box with arrow)
Tap "Add to Home Screen"
Tap Add — it appears like a real app!
Android (Chrome):
Open your Vercel URL in Chrome
Tap the 3-dot menu
Tap "Add to Home Screen" or "Install App"
Done!
🛠 Run Locally (optional)
npm install
npm run dev
Then open http://localhost:5173

Project Structure
three-bucket-pwa/
├── index.html          # Entry HTML
├── vite.config.js      # Vite + PWA config
├── package.json        # Dependencies
├── vercel.json         # Vercel routing
├── public/
│   ├── favicon.ico
│   └── icons/
│       ├── icon-192.png
│       └── icon-512.png
└── src/
    ├── main.jsx        # React entry
    └── App.jsx         # Full app
