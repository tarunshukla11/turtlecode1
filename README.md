# ⚡ Pikachu Turtle Graphics in Python

A Python Turtle Graphics project that draws Pikachu wearing Ash's Pokémon cap! 

You can run this project locally with standard Python or host it on **GitHub Pages** so anyone with the link can watch it draw in their browser!

---

## 🌐 Live Interactive Demo

> 🔗 **Replace with your link after enabling GitHub Pages:**  
> **[👉 Click Here to Watch Pikachu Draw Live in Your Browser!](https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/)**

- **Instant Drawing**: Starts animating Pikachu the moment the link is opened.
- **Controls**: Includes ⚡ Fast Mode, 🔄 Replay, 📜 View Code, and 💾 Save PNG.
- **Cross-Platform**: Works in any modern web browser (mobile, tablet, desktop) without installing Python.

---

## 💻 Run Locally on Your Computer

Make sure you have Python installed, then run:

```bash
python pikachu.py
```

A turtle graphics window will pop up and start drawing Pikachu.

---

## 🚀 How to Publish on GitHub with a Live Drawing Link

Follow these simple steps to put this project on GitHub and get your shareable link:

### Step 1: Create a New GitHub Repository
1. Log in to [GitHub](https://github.com).
2. Click the **`+`** icon in the top right corner and select **New repository**.
3. Name your repository (for example: `pikachu-turtle`).
4. Set visibility to **Public**.
5. Do **not** check "Add a README file" (we already created one for you).
6. Click **Create repository**.

### Step 2: Push Your Code to GitHub
Open your terminal inside this folder and run:

```bash
# Initialize git repository
git init

# Stage all files (pikachu.py, index.html, README.md)
git add .

# Create your first commit
git commit -m "Initial commit: Pikachu Turtle Art with Web Runner"

# Rename default branch to main
git branch -M main

# Link to your GitHub repository (replace with YOUR repository URL)
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git

# Push code to GitHub
git push -u origin main
```

### Step 3: Enable GitHub Pages (To get the live drawing link!)
1. In your GitHub repository, click on **Settings** (top tab).
2. In the left sidebar, click on **Pages** (under "Code and automation").
3. Under **Build and deployment** -> **Branch**:
   - Change `None` to **`main`**.
   - Leave the folder as **`/ (root)`**.
   - Click **Save**.
4. Wait about 1 minute and refresh the page.
5. GitHub will give you a public URL like:
   ```
   https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/
   ```

### Step 4: Share the Link!
Whenever anyone opens that link, **it will automatically open the web page and start drawing Pikachu stroke-by-stroke**!

---

## 🛠️ How the Web Version Works

- **Engine**: Powered by [Skulpt](https://skulpt.org), an in-browser Python runtime that translates Python Turtle calls directly to an HTML5 `<canvas>`.
- **Zero Server Setup**: Completely static; hosted 100% free on GitHub Pages.
- **Standalone**: `index.html` contains everything needed to render the animation.

---

## 📜 License
Feel free to use, modify, and share this code!
