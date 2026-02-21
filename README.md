# Ryota Takaki - Academic Portfolio

This is a modern, static, and completely free portfolio website designed for scientific researchers. Built with pure HTML, CSS, and JavaScript.

## Local Development

To view the website locally, you can use any local web server. For example, if you have Python installed, you can run the following command in this directory:

```bash
python3 -m http.server 8000
```

Then, open your browser and navigate to `http://localhost:8000`.

## Deployment to GitHub Pages (Free Hosting)

Since this site uses pure HTML/CSS/JS with no build steps, deploying it to GitHub Pages is incredibly simple.

### Step 1: Create a GitHub Repository
1. Go to [GitHub](https://github.com/) and log in (or create an account).
2. Click the `+` icon in the top right corner and select **New repository**.
3. Name the repository `ryota-takaki.github.io` (or any name you prefer, but using `[username].github.io` will make it your default user site).
4. Make the repository **Public**.
5. Do not initialize with a README, just click **Create repository**.

### Step 2: Push Your Code
Open your terminal, navigate to this `HomePage` directory, and run the following commands (replace `[username]` and `[repo]` with your actual GitHub username and repository name):

```bash
cd /Users/ryota/Documents/HomePage
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/[username]/[repo].git
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. On your GitHub repository page, go to **Settings**.
2. On the left sidebar, click **Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Under **Branch**, select `main` (or `master`) and keep the `/(root)` folder selected.
5. Click **Save**.

Your website will be live at `https://[username].github.io` within a few minutes!

## Maintenance

To update your publications, CV, or research simply edit the respective `.html` files in this directory, save them, and push the changes to GitHub:

```bash
git add .
git commit -m "Update publication list"
git push
```
