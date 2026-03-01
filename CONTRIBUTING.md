> [!IMPORTANT]
> This guide does not include Linux users. If you manage to use Linux, you can probably figure out how to edit a markdown file. (Trust me bro, I daily-drive Arch btw)

# Contributing to The Kolasab (CoLa-SoB)

Thank you for your interest in contributing to **The Kolasab**! Contributions come in two flavors: **Development** and **Writing**. Pick whichever floats your boat, or both.  

Please ensure compliance with [Tone Guide](./TONEGUIDE.md) and [Style Guide](./STYLEGUIDE.md) (applies to writing and code!).  
***Read carefully! Some instructions can be dangerous if typed wrong, followed incorrectly or done out of sequence!!***

---

## Prerequisites for All Contributions
- Know how to write in a neutral dialect of English (American English preferred). When in doubt, check [Dictionary.com](https://dictionary.com).
  - For writing, commit messages and Pull Requests.
- A GitHub account.
  - For Contributing 
- Semi-professional commit messages. Avoid vague commits like `"lol"`.
  - I CANNOT READ A TEN-THOUSAND LINE PULL REQUEST WITH THE ONLY COMMIT MESSAGE BEING "Fixes all errors"!!!

---

## 🖊 Writing Contributions

**Prerequisites:**  
- Basic Markdown knowledge (or know how to convert a Google Doc to Markdown).  
- Good sense of witty humor.

**Scope:**  
- All laws `/src/lib/laws/`and `/src/lib/articles/`)

### Getting Started

#### Editing an Existing Law or Article
1. Open the GitHub web UI and navigate to `/src/lib/laws/` or `/src/lib/articles/`.  
2. Click the file you want to edit.  
3. Click the pencil icon in the top-right corner.  
4. Edit the file.  
5. Add a descriptive commit message (GitHub Copilot usually suggests one).  
6. Select the option to make a fork.  
7. Once your fork is ready, go back to this repository and click ==> `Pull Requests` ==> `New Pull Request`.  
8. Add details about your edits and submit. It will be reviewed (usually within a week if the repo isn’t abandoned).

#### Adding a New Law or Artical

> TIP:
> See /templates/law.md or /templates.artical.md for templates, sentence srarters etc...

1. Navigate to `/src/lib/laws/`.
2. Create a new Markdown file following the existing naming/formatting conventions.  
3. Include:
   - Unique law name/title 
   - Description  
   - example(s)  
4. Commit, fork, and submit a Pull Request as above.

---

## 💻 Development Contributions

**Prerequisites:**  
- Comfortable with terminal/command-line tools (PowerShell, Bash, SH, etc.).  
- Knowledge of HTML, CSS, JavaScript/TypeScript, Svelte, and SvelteKit.

**Scope:**  
- All JavaScript, UI, tooling, and app-level improvements. Examples:  
  - UI/UX improvements, components, pages  
  - Svelte/SvelteKit features  
  - NPM packages or build scripts  
  - Bug fixes and performance improvements

### Getting Started (Advanced)
1. Install Git, Node, and NPM on your machine if not already installed.  
2. Clone the repository:
   ```bash
   git clone https://github.com/Gargleblaster-RMBK/The-Common-Laws-of-Social-Behavior.git
    ```

3. Run:

   ```bash
   npm install
   npm run dev
   ```
4. Open [http://localhost:5173](http://localhost:5173).

   > Tip: `npm run dev -- --open` will auto-launch the browser.

Your edits will automatically update in the browser when you save files.

### Getting Started (Beginner)

1. Install [Node.js](https://nodejs.org/en/download/) for your OS (version 24+ recommended).

   * MacOS: Use Homebrew
   * Windows: Use Chocolatey

2. Install Git ([https://git-scm.com/install/](https://git-scm.com/install/)) and verify:

   ```bash
   git --version
   ```

3. Install [VS Code](https://code.visualstudio.com/).

   * Link your GitHub account via the profile icon → “Link GitHub Account”.
   * Clone the repo using the Git URL:
     `https://github.com/Gargleblaster-RMBK/The-Common-Laws-of-Social-Behavior.git`
   * Install recommended extensions.

4. Open the terminal (`Ctrl+~` / `Command+~`) and run:

   ```bash
   npm install
   npm run dev
   ```

   > `npm run dev` – runs locally, does not open browser
   > `npm run dev -- --open` – runs locally, opens browser

5. 🎉 Start coding!

   * Files you edit will automatically update in the browser when saved.

---

## ⚠️ Notes

* Respect the dual licenses: GPL for code, CC BY-SA for content.
* Ask questions in the Issues tab if unsure.
* Keep PRs small and focused where possible.

Happy contributing! 🚀
