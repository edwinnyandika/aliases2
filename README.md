<div align="center">

<img src="https://capsule-render.vercel.app/api?type=wave&color=0:39d353,100:1a7f37&height=200&section=header&text=aliases2&fontSize=72&fontColor=ffffff&fontAlignY=38&desc=KRAM%27s%20Git%20Bash%20%26%20CLI%20Aliases&descAlignY=58&descSize=18&animation=fadeIn" width="100%"/>

<br/>

![Shell](https://img.shields.io/badge/Shell-Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Git](https://img.shields.io/badge/Git-Aliases-F05032?style=for-the-badge&logo=git&logoColor=white)
![npm](https://img.shields.io/badge/npm-Aliases-CB3837?style=for-the-badge&logo=npm&logoColor=white)
![pnpm](https://img.shields.io/badge/pnpm-Aliases-F69220?style=for-the-badge&logo=pnpm&logoColor=white)
![Aliases](https://img.shields.io/badge/Total%20Aliases-40%2B-blueviolet?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Git%20Bash%20%7C%20WSL-blue?style=for-the-badge&logo=windows&logoColor=white)

<br/>

> **⚡ Supercharge your terminal.** Stop typing long commands — let short aliases do the heavy lifting.
>
> `git push -u origin main` → just type **`gpom`**

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=2000&pause=800&color=39D353&center=true&vCenter=true&multiline=true&repeat=true&width=600&height=80&lines=gs+%E2%86%92+git+status;gaa+%E2%86%92+git+add+.;gpom+%E2%86%92+git+push+-u+origin+main;nrd+%E2%86%92+npm+run+dev;pnrb+%E2%86%92+pnpm+run+build" alt="Typing SVG" />

<br/><br/>

</div>

---

## 📋 Table of Contents

- [🚀 Quick Start](#-quick-start)
- [🔶 Git Aliases](#-git-aliases)
- [🔴 npm Aliases](#-npm-aliases)
- [🟠 pnpm Aliases](#-pnpm-aliases)
- [🟣 Utility Aliases](#-utility-aliases)
- [🔵 Navigation Aliases](#-navigation-aliases)
- [⚙️ Installation](#️-installation)
- [🎮 Test Yourself](#-test-yourself)
- [🖥️ Custom Prompt](#️-custom-prompt)
- [⚠️ Important Note](#️-important-note)

---

## 🚀 Quick Start

```bash
# 1. Clone the repo
git clone https://github.com/edwinnyandika/aliases2.git

# 2. Copy .bashrc to your home directory
cp aliases2/.bashrc ~/.bashrc

# 3. Reload your shell
source ~/.bashrc

# 4. You're done! Try it:
gs        # → git status
gaa       # → git add .
gc "init" # → git commit -m "init"
gpom      # → git push -u origin main
```

---

## 🔶 Git Aliases

> Shorten your most-used git commands to lightning-fast keystrokes.

<details>
<summary><b>📖 Click to expand — All Git Aliases</b></summary>

<br/>

| Alias | Expands To | What It Does |
|-------|-----------|--------------|
| `gi` | `git init` | Initialize a new git repository |
| `gs` | `git status` | Show the working tree status |
| `ga` | `git add` | Stage specific file(s) |
| `gaa` | `git add .` | Stage **all** changed files |
| `gc` | `git commit -m` | Commit with a message |
| `gp` | `git push` | Push commits to remote |
| `gpl` | `git pull` | Pull latest changes from remote |
| `grao` | `git remote add origin` | Connect repo to a remote URL |
| `grv` | `git remote -v` | List all remote connections |
| `gpo` | `git push -u origin` | Push & set upstream tracking |
| `gpom` | `git push -u origin main` | Push to origin/main & track |

</details>

### ⚡ Typical Git Workflow

```bash
gi                        # git init
grao https://...          # git remote add origin https://...
gaa                       # git add .
gc "first commit"         # git commit -m "first commit"
gpom                      # git push -u origin main

# Later on...
gs                        # git status
ga src/index.js           # git add src/index.js
gc "fix: button styles"   # git commit -m "fix: button styles"
gp                        # git push
```

---

## 🔴 npm Aliases

> Every `npm` command, faster.

<details>
<summary><b>📖 Click to expand — All npm Aliases</b></summary>

<br/>

| Alias | Expands To | What It Does |
|-------|-----------|--------------|
| `ni` | `npm install` | Install all dependencies |
| `nid` | `npm install -D` | Install as dev dependency |
| `nig` | `npm install -g` | Install package globally |
| `nr` | `npm run` | Run an npm script |
| `nrd` | `npm run dev` | Start the dev server |
| `nrw` | `npm run watch` | Run in watch mode |
| `nrb` | `npm run build` | Build for production |
| `ns` | `npm start` | Start the app |
| `nrr` | `npm run reset && nrd` | Reset then start dev server |
| `lise` | `live-server` | Launch live-server |

</details>

### ⚡ Typical npm Workflow

```bash
ni              # npm install
nrd             # npm run dev
nrb             # npm run build
```

---

## 🟠 pnpm Aliases

> Same speed boost, but for `pnpm` users.

<details>
<summary><b>📖 Click to expand — All pnpm Aliases</b></summary>

<br/>

| Alias | Expands To | What It Does |
|-------|-----------|--------------|
| `pni` | `pnpm install` | Install all dependencies |
| `pnid` | `pnpm install -D` | Install as dev dependency |
| `pnig` | `pnpm install -g` | Install package globally |
| `pnr` | `pnpm run` | Run a pnpm script |
| `pnrd` | `pnpm run dev` | Start the dev server |
| `pnrw` | `pnpm run watch` | Run in watch mode |
| `pnrb` | `pnpm run build` | Build for production |
| `pns` | `pnpm start` | Start the app |
| `pnrr` | `pnpm run reset && nrd` | Reset then start dev server |

</details>

---

## 🟣 Utility Aliases

> Manage your shell config and launch tools instantly.

<details>
<summary><b>📖 Click to expand — All Utility Aliases</b></summary>

<br/>

| Alias | Expands To | What It Does |
|-------|-----------|--------------|
| `nnb` | `nano ~/.bashrc` | Edit your `.bashrc` in nano |
| `sb` | `source ~/.bashrc` | Reload `.bashrc` without restarting |
| `cpb` | `cd .../cp ~/.bashrc ... push` | Backup bashrc & push to repo |
| `cls` | `clear` | Clear the terminal screen |
| `ntt` | `wt -w 0 nt -d` | Open new terminal tab in specified folder |
| `cs` | `cursor` | Open the Cursor editor |
| `qd` | `qoder` | Open the Qoder app |
| `lise` | `live-server` | Start live-server |

</details>

---

## 🔵 Navigation Aliases

> Jump between your most-used project folders in one keystroke.

<details>
<summary><b>📖 Click to expand — All Navigation Aliases</b></summary>

<br/>

| Alias | Expands To | Goes To |
|-------|-----------|---------|
| `cdp` | `cd /d/Projects` | 📁 Your main projects folder |
| `cdg` | `cd /d/GOMYCODE` | 📁 GOMYCODE folder |
| `cdo` | `cd /d/OVES` | 📁 OVES folder |
| `cdd` | `cd /d` | 📁 D: drive root |

</details>

---

## ⚙️ Installation

### Option 1 — Clone & Copy (Recommended)

```bash
git clone https://github.com/edwinnyandika/aliases2.git
cp aliases2/.bashrc ~/.bashrc
source ~/.bashrc
```

### Option 2 — Append to existing `.bashrc`

```bash
curl -sL https://raw.githubusercontent.com/edwinnyandika/aliases2/main/.bashrc >> ~/.bashrc
source ~/.bashrc
```

### Option 3 — Manual

1. Open your `.bashrc`:
   ```bash
   nano ~/.bashrc
   ```
2. Paste in the aliases you want from `.bashrc`
3. Save and reload:
   ```bash
   source ~/.bashrc
   ```

### ✅ Verify Installation

```bash
# Run this to check aliases loaded correctly
alias | grep "gs\|gaa\|gc\|nrd"
```

Expected output:
```
alias gaa='git add .'
alias gc='git commit -m'
alias gs='git status'
alias nrd='npm run dev'
```

---

## 🎮 Test Yourself

Think you know the aliases? Try this quick challenge! 👇

<details>
<summary><b>🧠 Round 1 — What does the alias expand to?</b></summary>

<br/>

| # | Alias | Answer |
|---|-------|--------|
| 1 | `gaa` | <details><summary>Reveal</summary>`git add .`</details> |
| 2 | `gpom` | <details><summary>Reveal</summary>`git push -u origin main`</details> |
| 3 | `nrd` | <details><summary>Reveal</summary>`npm run dev`</details> |
| 4 | `sb` | <details><summary>Reveal</summary>`source ~/.bashrc`</details> |
| 5 | `pnrb` | <details><summary>Reveal</summary>`pnpm run build`</details> |

</details>

<details>
<summary><b>🧠 Round 2 — What alias runs this command?</b></summary>

<br/>

| # | Command | Answer |
|---|---------|--------|
| 1 | `git status` | <details><summary>Reveal</summary>`gs`</details> |
| 2 | `npm install -D` | <details><summary>Reveal</summary>`nid`</details> |
| 3 | `git remote add origin` | <details><summary>Reveal</summary>`grao`</details> |
| 4 | `cd /d/Projects` | <details><summary>Reveal</summary>`cdp`</details> |
| 5 | `clear` | <details><summary>Reveal</summary>`cls`</details> |

</details>

<details>
<summary><b>🧠 Round 3 — Complete the workflow</b></summary>

<br/>

Fill in the aliases to complete this typical project setup:

```bash
# 1. Initialize git              → ___
# 2. Connect remote origin       → ___ https://github.com/you/repo.git
# 3. Install dependencies        → ___
# 4. Start dev server            → ___
# 5. Stage all changes           → ___
# 6. Commit                      → ___ "feat: add homepage"
# 7. Push to main                → ___
```

<details>
<summary>✅ Reveal Answers</summary>

```bash
gi
grao https://github.com/you/repo.git
ni
nrd
gaa
gc "feat: add homepage"
gpom
```

</details>

</details>

---

## 🖥️ Custom Prompt

This `.bashrc` also sets up a custom **colorized Git Bash prompt** showing:

- 🟢 Username and machine name
- 🟣 Current MSYSTEM (e.g. MINGW64)
- 🟡 Current working directory
- 🔵 Active git branch (via `__git_ps1`)

**Preview:**
```
KRAM@DESKTOP MINGW64 ~/Projects/my-app (main)
$
```

Activate it by running:
```bash
source ~/.bashrc
```

---

## ⚠️ Important Note

> **🚨 Some aliases are personal to KRAM.**
>
> Aliases like `cpb`, `cdp`, `cdg`, `cdo` point to **specific paths on KRAM's machine** (e.g. `/d/Projects`, `/d/OVES`).
> **Do not blindly copy-paste** — update the paths to match your own directory structure.

```bash
# Change this:
alias cdp='cd /d/Projects'

# To match YOUR setup:
alias cdp='cd ~/my-projects'
```

---

<div align="center">

## 📊 Alias Stats

![Git](https://img.shields.io/badge/Git%20Aliases-11-F05032?style=flat-square&logo=git)
![npm](https://img.shields.io/badge/npm%20Aliases-10-CB3837?style=flat-square&logo=npm)
![pnpm](https://img.shields.io/badge/pnpm%20Aliases-9-F69220?style=flat-square&logo=pnpm)
![Util](https://img.shields.io/badge/Utility%20Aliases-8-blueviolet?style=flat-square)
![Nav](https://img.shields.io/badge/Nav%20Aliases-4-blue?style=flat-square)

<br/>

**Maintained by [KRAM](https://github.com/edwinnyandika)** · Feel free to fork and customize for your own workflow!

<br/>

<img src="https://capsule-render.vercel.app/api?type=wave&color=0:39d353,100:1a7f37&height=100&section=footer" width="100%"/>

</div>
