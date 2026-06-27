# CarPick — Smart Car Tracker

Track used cars you're considering and use Claude AI to compare them and analyze listings.

## Features
- Add/edit/delete cars with full details (price, mileage, condition, etc.)
- AI-powered comparison — Claude ranks your cars and recommends the best one
- AI listing analysis — paste any listing and get a full buyer's assessment
- Data saved in your browser (localStorage)
- Mobile friendly

## Deploy to Vercel (Free) — 5 minutes

### Step 1: Create GitHub repo
1. Go to https://github.com/new
2. Create a new repository called `car-tracker` (public or private)
3. Upload both files: `index.html` and `vercel.json`

### Step 2: Deploy on Vercel
1. Go to https://vercel.com and sign up with GitHub (free)
2. Click **"Add New Project"**
3. Import your `car-tracker` repo
4. Leave all settings as default — click **Deploy**
5. Done! You'll get a URL like `car-tracker-abc123.vercel.app`

### Step 3: Set your API Key
1. Open your deployed site
2. Click **"Set API Key"** in the top right
3. Enter your Anthropic API key (get one free at https://console.anthropic.com)
4. Your key is stored only in your browser — never sent anywhere except Anthropic

## Local Use (no deployment needed)
Just open `index.html` directly in your browser — it works offline for the tracker,
and uses your API key for AI features.

## Notes
- Your car data is saved in your browser's localStorage
- API key is stored in localStorage — never leaves your device except to Anthropic
- Free Anthropic account gives $5 credit which is plenty for car shopping
