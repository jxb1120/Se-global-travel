# SE Global Travel — CTM Portal

A corporate travel management portal with integrated personal trip planner (Wanderly).

---

## 🚀 Deploy to Vercel (Easiest — Free)

### Step 1: Install Node.js
Download from https://nodejs.org (choose the LTS version)

### Step 2: Create a GitHub Account
Go to https://github.com and sign up (free)

### Step 3: Upload This Project to GitHub
1. Go to https://github.com/new
2. Name it `se-global-travel`
3. Click **Create repository**
4. On your computer, open Terminal (Mac) or Command Prompt (Windows)
5. Run these commands:
   ```
   cd se-global-travel
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/se-global-travel.git
   git push -u origin main
   ```

### Step 4: Deploy on Vercel
1. Go to https://vercel.com and sign up with your GitHub account
2. Click **"Add New Project"**
3. Select your `se-global-travel` repo
4. Click **Deploy**
5. ✅ You're live! You'll get a URL like `se-global-travel.vercel.app`

---

## 🤖 Enable AI Features

The AI features (itinerary generator, packing suggestions, etc.) need an Anthropic API key.

1. Get a free API key at https://console.anthropic.com
2. In Vercel → your project → **Settings** → **Environment Variables**
3. Add: `REACT_APP_ANTHROPIC_KEY` = your key

> Note: For production, you should move API calls to a backend so your key stays private.

---

## 💻 Run Locally

```bash
npm install
npm start
```

Then open http://localhost:3000

---

## 📁 Project Structure

```
se-global-travel/
├── public/
│   └── index.html
├── src/
│   ├── App.js        ← All app code
│   └── index.js      ← React entry point
├── package.json
├── vercel.json
└── README.md
```

---

## ✨ Features

**Corporate (SE Global Travel)**
- Flight search with policy compliance
- Hotel search with rate limits
- Booking with PNR generation
- Itinerary manager
- Expense reports (Concur/SAP export)

**Personal (Wanderly)**
- Multi-trip planner
- Interactive map with location pins
- Day-by-day itinerary builder
- Packing list tracker
- Budget tracker
- Travel journal with mood tags
- AI-powered suggestions throughout
