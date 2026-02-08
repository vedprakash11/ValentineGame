# Ask Out Your Valentine

A playful, interactive Valentine's page (based on [CodeKageHQ/Ask-out-your-Valentine](https://github.com/CodeKageHQ/Ask-out-your-Valentine)) with GIFs and dynamic Yes/No buttons. Built with HTML, Tailwind CSS, and JavaScript.

## Deploy on GitHub Pages (github.io)

### Option A: Deploy this repo (recommended)

1. **Create a new repository on GitHub**
   - Go to [github.com/new](https://github.com/new).
   - Name it anything (e.g. `ValentineGame` or `Ask-out-your-Valentine`).
   - Choose **Public**, do **not** add a README (you already have one).
   - Click **Create repository**.

2. **Push this folder to GitHub**
   ```powershell
   cd "c:\Users\vedpr\Downloads\ValentineGame"
   git init
   git add .
   git commit -m "Initial commit - Valentine page"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```
   Replace `YOUR_USERNAME` and `YOUR_REPO_NAME` with your GitHub username and repo name.

3. **Enable GitHub Pages**
   - Open your repo on GitHub → **Settings** → **Pages** (left sidebar).
   - Under **Build and deployment**:
     - **Source**: Deploy from a branch
     - **Branch**: `main` (or `master`) → **/ (root)** → **Save**.
   - Wait 1–2 minutes. Your site will be at:
     - **https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/**

### Option B: Fork the original repo

1. Go to [github.com/CodeKageHQ/Ask-out-your-Valentine](https://github.com/CodeKageHQ/Ask-out-your-Valentine).
2. Click **Fork** (top right).
3. In your fork: **Settings** → **Pages** → Source: **Deploy from branch** → Branch: **main** → **/ (root)** → **Save**.
4. Site URL: **https://YOUR_USERNAME.github.io/Ask-out-your-Valentine/**

## Run locally

Open `index.html` in a browser, or use a simple server:

```powershell
cd "c:\Users\vedpr\Downloads\ValentineGame"
python -m http.server 8000
```

Then visit **http://localhost:8000**.

## License

Original project: MIT (CodeKageHQ/Ask-out-your-Valentine).
