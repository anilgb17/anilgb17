# 🚀 Quick Setup Guide: How to Apply Your Animated Profile to GitHub

GitHub has a special feature called the **Profile README**. When you create a public repository with the exact same name as your GitHub username (`anilgb17/anilgb17`), GitHub displays its `README.md` right at the very top of your profile page (`https://github.com/anilgb17`)!

---

## ⚡ Method 1: GitHub Web (Fastest — 60 Seconds)

1. **Create the Special Repository**:
   - Open your browser and go to: **[https://github.com/new](https://github.com/new)**
   - Under **Repository name**, type: `anilgb17`
   - *GitHub will show an easter-egg box: `✨ You found a secret! anilgb17/anilgb17 is a special repository...`*
   - Make sure **Public** is selected.
   - Check the box: **"Add a README file"**.
   - Click **Create repository**.

2. **Paste the Animated README**:
   - Inside your new `anilgb17` repository, open `README.md` and click the **Pencil icon (Edit this file)** in the upper right.
   - Select all text and replace it with the contents of [`README.md`](file:///C:/Users/Anil%20Badiger/.gemini/antigravity-ide/scratch/github-profile-anilgb17/README.md).
   - Click the green **Commit changes...** button.
   - Go to your profile at **[https://github.com/anilgb17](https://github.com/anilgb17)** — your new animated profile is instantly live!

---

## 💻 Method 2: Git Command Line (Recommended if you want the Snake Action included)

If you'd like to push both the `README.md` and the automated contribution snake workflow:

1. Create the repository `anilgb17` at [https://github.com/new](https://github.com/new) without initializing with a README.
2. In your terminal, navigate to this folder and run:
   ```bash
   cd "C:\Users\Anil Badiger\.gemini\antigravity-ide\scratch\github-profile-anilgb17"
   git init
   git add .
   git commit -m "feat: visual animated profile readme & workflows"
   git branch -M main
   git remote add origin https://github.com/anilgb17/anilgb17.git
   git push -u origin main
   ```

---

## 🐍 Enabling the Contribution Snake Animation (GitHub Actions)

Your repository includes `.github/workflows/snake.yml`, which automatically animates a retro snake eating your GitHub contribution graph every night!

To ensure it has permission to publish the snake SVG:
1. Go to your `anilgb17` repository on GitHub.
2. Click **Settings** (top tab) ➔ **Actions** (left sidebar) ➔ **General**.
3. Scroll down to **Workflow permissions**.
4. Select **"Read and write permissions"** and click **Save**.
5. Go to the **Actions** tab on your repository:
   - Click **"Generate Contribution Snake Animation"** on the left.
   - Click **Run workflow** ➔ **Run workflow**.
   - In ~30 seconds, your animated snake SVG will be generated and displayed live on your profile!

---

## 👁️ Previewing Locally

Double-click [`preview.html`](file:///C:/Users/Anil%20Badiger/.gemini/antigravity-ide/scratch/github-profile-anilgb17/preview.html) in your file explorer to open the interactive live preview in your default browser.
