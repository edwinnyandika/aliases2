<div align="center">

<!-- ANIMATED HEADER -->
<img src="https://capsule-render.vercel.app/api?type=wave&color=0:0d1117,50:1a7f37,100:39d353&height=280&section=header&text=aliases2&fontSize=90&fontColor=ffffff&fontAlignY=42&desc=⚡%20KRAM%27s%20Ultimate%20Git%20Bash%20%26%20CLI%20Alias%20Collection&descAlignY=62&descSize=16&animation=fadeIn&stroke=39d353&strokeWidth=2" width="100%"/>

<br/>

<!-- PROFILE VIEWS + STARS -->
![Profile Views](https://komarev.com/ghpvc/?username=edwinnyandika&color=39d353&style=for-the-badge&label=README+VIEWS)
[![GitHub stars](https://img.shields.io/github/stars/edwinnyandika/aliases2?style=for-the-badge&color=39d353&logo=github)](https://github.com/edwinnyandika/aliases2/stargazers)

<br/>

<!-- TECH BADGES -->
![Shell](https://img.shields.io/badge/Shell-Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Git](https://img.shields.io/badge/Git-11%20Aliases-F05032?style=for-the-badge&logo=git&logoColor=white)
![npm](https://img.shields.io/badge/npm-10%20Aliases-CB3837?style=for-the-badge&logo=npm&logoColor=white)
![pnpm](https://img.shields.io/badge/pnpm-9%20Aliases-F69220?style=for-the-badge&logo=pnpm&logoColor=white)
![Platform](https://img.shields.io/badge/Windows-Git%20Bash-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

<br/>

<!-- TYPING ANIMATION -->
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=24&duration=1800&pause=600&color=39D353&center=true&vCenter=true&repeat=true&width=700&height=60&lines=gs+%E2%86%92+git+status+%E2%9A%A1;gaa+%E2%86%92+git+add+.+%F0%9F%93%A6;gc+%22msg%22+%E2%86%92+git+commit+-m+%22msg%22+%F0%9F%92%BE;gpom+%E2%86%92+git+push+-u+origin+main+%F0%9F%9A%80;nrd+%E2%86%92+npm+run+dev+%F0%9F%94%A5;pnrb+%E2%86%92+pnpm+run+build+%F0%9F%8F%97%EF%B8%8F" alt="Typing SVG" />

<br/>

<!-- HERO QUOTE -->
```
╔══════════════════════════════════════════════════════════════╗
║  "The best command is the one you never have to fully type"  ║
║                                          — Every Developer   ║
╚══════════════════════════════════════════════════════════════╝
```

</div>

---

## 📋 Table of Contents

| | Section | Description |
|---|---------|-------------|
| 🗺️ | [What Are Aliases?](#-what-are-aliases) | Understand the concept visually |
| ⚡ | [Before vs After](#-before-vs-after) | See the time savings |
| 🚀 | [Quick Start](#-quick-start) | Get running in 60 seconds |
| 🔶 | [Git Aliases](#-git-aliases) | 11 git shortcuts |
| 🔴 | [npm Aliases](#-npm-aliases) | 10 npm shortcuts |
| 🟠 | [pnpm Aliases](#-pnpm-aliases) | 9 pnpm shortcuts |
| 🟣 | [Utility Aliases](#-utility-aliases) | Shell tools & editors |
| 🔵 | [Navigation Aliases](#-navigation-aliases) | Jump between folders |
| 🗺️ | [Alias Map](#-complete-alias-map) | Full visual overview |
| 🔁 | [Workflows](#-real-world-workflows) | Real dev scenarios |
| ⚙️ | [Installation](#-installation) | Step by step setup |
| 🖥️ | [Custom Prompt](#-custom-prompt) | Colorized Git Bash PS1 |
| 🎮 | [Test Yourself](#-test-yourself) | Quiz & challenges |
| 🏆 | [Skill Tree](#-skill-tree) | Track your alias mastery |
| ⚠️ | [Important Note](#-important-note) | Read before copy-pasting |

---

## 🗺️ What Are Aliases?

> An **alias** is a shortcut — a short word you define that expands into a full command when typed in the terminal.

```
You type:    gs
Shell runs:  git status
```

Think of it like autocomplete you build yourself. Once set up, your fingers barely have to move.

### How It Works Under The Hood

```
┌─────────────────────────────────────────────────────────────────┐
│                     YOUR TERMINAL SESSION                       │
│                                                                 │
│   You type: gpom                                                │
│       │                                                         │
│       ▼                                                         │
│   ┌─────────────┐    looks up    ┌──────────────────────────┐  │
│   │   ~/.bashrc  │ ─────────────▶│  gpom = git push -u      │  │
│   │  (alias map) │               │         origin main       │  │
│   └─────────────┘                └──────────────────────────┘  │
│       │                                          │              │
│       │              expands to                  │              │
│       └──────────────────────────────────────────┘              │
│                          │                                      │
│                          ▼                                      │
│              git push -u origin main  ✅ runs!                  │
└─────────────────────────────────────────────────────────────────┘
```

### Where Aliases Live

```
HOME DIRECTORY
└── ~/.bashrc                 ← your aliases live here
      ├── alias gs='git status'
      ├── alias gaa='git add .'
      ├── alias gpom='git push -u origin main'
      └── ... 40 more aliases
```

> 💡 **After editing `.bashrc`**, run `sb` (which is `source ~/.bashrc`) to reload it instantly — no need to restart your terminal!

---

## ⚡ Before vs After

See how much typing aliases save you every single day:

```
BEFORE aliases                        AFTER aliases
──────────────────────────────────    ──────────────────────────
$ git status                          $ gs
$ git add .                           $ gaa
$ git commit -m "feat: navbar"        $ gc "feat: navbar"
$ git push -u origin main             $ gpom
──────────────────────────────────    ──────────────────────────
  74 characters typed                   22 characters typed
                                        70% LESS TYPING ⚡
```

### ⏱️ Time Saved Per Day

Assuming you run these commands ~20 times a day:

```
Command              Saved chars    × 20/day    Per year (250 days)
───────────────────────────────────────────────────────────────────
git status        →  8 chars        160/day     40,000 keystrokes
git add .         →  7 chars        140/day     35,000 keystrokes
git commit -m     →  11 chars       220/day     55,000 keystrokes
git push          →  4 chars        80/day      20,000 keystrokes
npm run dev       →  8 chars        160/day     40,000 keystrokes
───────────────────────────────────────────────────────────────────
TOTAL SAVED:  ~190,000 keystrokes per year 🎉
```

---

## 🚀 Quick Start

```bash
# ① Clone the repo
git clone https://github.com/edwinnyandika/aliases2.git

# ② Append aliases to your .bashrc
cat aliases2/.bashrc >> ~/.bashrc

# ③ Reload shell instantly
source ~/.bashrc

# ④ Verify it worked
alias | grep "^alias g"

# ✅ You should see all git aliases listed!
```

### ✅ Success Checklist

```
[ ] Cloned the repo
[ ] Copied .bashrc content
[ ] Ran source ~/.bashrc  (or: sb)
[ ] Tested gs → shows git status output
[ ] Tested nrd → starts dev server
[ ] Customized personal paths (cdp, cdg, cdo)
```

---

## 🔶 Git Aliases

> Master git without memorizing full commands.

<details>
<summary><b>🖼️ Visual Flow — Click to expand</b></summary>

<br/>

```
GIT ALIAS VISUAL MAP
═════════════════════════════════════════════════════════════

  SETUP PHASE
  ┌──────────────────────────────────────────────────────┐
  │  gi      →  git init                                 │
  │  grao    →  git remote add origin <url>              │
  └──────────────────────────────────────────────────────┘
              ↓

  DAILY WORK LOOP
  ┌──────────────────────────────────────────────────────┐
  │                                                      │
  │   gs   →  git status   (check what changed)         │
  │    ↓                                                 │
  │   ga   →  git add <file>   OR                       │
  │   gaa  →  git add .        (stage everything)       │
  │    ↓                                                 │
  │   gc   →  git commit -m "message"                   │
  │    ↓                                                 │
  │   gp   →  git push                                  │
  │                                                      │
  └──────────────────────────────────────────────────────┘
              ↓

  REMOTE MANAGEMENT
  ┌──────────────────────────────────────────────────────┐
  │  grv   →  git remote -v      (see remote URLs)      │
  │  gpl   →  git pull           (get latest)           │
  │  gpo   →  git push -u origin (set upstream)         │
  │  gpom  →  git push -u origin main (→ main branch)  │
  └──────────────────────────────────────────────────────┘
```

</details>

<details>
<summary><b>📖 Full Alias Table — Click to expand</b></summary>

<br/>

| Alias | Full Command | When To Use |
|-------|-------------|-------------|
| `gi` | `git init` | Starting a brand new local repo |
| `gs` | `git status` | **Most used** — check what's changed |
| `ga` | `git add` | Stage a specific file: `ga index.js` |
| `gaa` | `git add .` | Stage **everything** at once |
| `gc` | `git commit -m` | Commit: `gc "fix: nav bug"` |
| `gp` | `git push` | Push to already-tracked remote |
| `gpl` | `git pull` | Pull latest from remote |
| `grao` | `git remote add origin` | Link local repo to GitHub |
| `grv` | `git remote -v` | Verify remote URL is correct |
| `gpo` | `git push -u origin` | Push + set upstream: `gpo feature-branch` |
| `gpom` | `git push -u origin main` | First push to main branch |

</details>

<details>
<summary><b>⚡ Git Workflows — Click to see examples</b></summary>

<br/>

**🆕 Starting a new project:**
```bash
mkdir my-app && cd my-app
gi                                    # git init
grao https://github.com/you/my-app   # link to GitHub
gaa                                   # git add .
gc "init: project setup"              # first commit
gpom                                  # push to main
```

**📅 Daily development loop:**
```bash
gpl                        # pull latest changes first
# ... write code ...
gs                         # check what changed
gaa                        # stage everything
gc "feat: add dark mode"   # commit with message
gp                         # push to remote
```

**🔍 Checking remote:**
```bash
grv   # shows: origin  https://github.com/you/repo.git (fetch)
      #        origin  https://github.com/you/repo.git (push)
```

</details>

---

## 🔴 npm Aliases

> npm scripts in half the keystrokes.

<details>
<summary><b>🖼️ Visual Map — Click to expand</b></summary>

<br/>

```
npm ALIAS DECISION TREE
══════════════════════════════════════════════════════════════

  Starting a project?
  ┌────────────────────────────────────────────────────────┐
  │  ni   →  npm install         (install everything)      │
  │  nid  →  npm install -D      (dev dependency)          │
  │  nig  →  npm install -g      (global tool)             │
  └────────────────────────────────────────────────────────┘

  Running scripts?
  ┌────────────────────────────────────────────────────────┐
  │  nrd  →  npm run dev         ← most used daily!        │
  │  nrb  →  npm run build       (production build)        │
  │  nrw  →  npm run watch       (file watcher)            │
  │  ns   →  npm start           (start server)            │
  │  nr   →  npm run <script>    (any custom script)       │
  └────────────────────────────────────────────────────────┘

  Special:
  ┌────────────────────────────────────────────────────────┐
  │  nrr  →  npm run reset && nrd   (reset + restart dev)  │
  │  lise →  live-server            (browser auto-reload)  │
  └────────────────────────────────────────────────────────┘
```

</details>

<details>
<summary><b>📖 Full Alias Table — Click to expand</b></summary>

<br/>

| Alias | Full Command | Use Case |
|-------|-------------|----------|
| `ni` | `npm install` | Fresh install of all packages |
| `nid` | `npm install -D` | Add dev dependency: `nid eslint` |
| `nig` | `npm install -g` | Global tools: `nig live-server` |
| `nr` | `npm run` | Any script: `nr lint` |
| `nrd` | `npm run dev` | Start Vite / Next / etc. |
| `nrw` | `npm run watch` | Watch & rebuild on change |
| `nrb` | `npm run build` | Production build |
| `ns` | `npm start` | Start production server |
| `nrr` | `npm run reset && nrd` | Nuke state and restart dev |
| `lise` | `live-server` | Static file dev with hot reload |

</details>

<details>
<summary><b>⚡ npm Workflows — Click to see examples</b></summary>

<br/>

**🆕 Setting up a new npm project:**
```bash
ni                         # install all dependencies
nrd                        # start dev server
```

**📦 Adding packages:**
```bash
nid tailwindcss            # npm install -D tailwindcss
nig vercel                 # npm install -g vercel
```

**🏗️ Building for production:**
```bash
nrb                        # npm run build
ns                         # npm start (serve production build)
```

**🔄 When things break:**
```bash
nrr   # npm run reset && npm run dev  (nuclear option 💥)
```

</details>

---

## 🟠 pnpm Aliases

> All the npm aliases, but for pnpm — faster installs, disk-efficient.

<details>
<summary><b>🖼️ npm vs pnpm — Click to see comparison</b></summary>

<br/>

```
npm  alias    pnpm alias    What it does
──────────────────────────────────────────────────
ni            pni           install all packages
nid           pnid          install dev dependency
nig           pnig          install globally
nrd           pnrd          run dev server
nrb           pnrb          run build
nrw           pnrw          run watch
ns            pns           start
nr            pnr           run any script
nrr           pnrr          reset + dev

Pattern: just add "p" prefix for pnpm! 🧠
```

</details>

<details>
<summary><b>📖 Full Alias Table — Click to expand</b></summary>

<br/>

| Alias | Full Command | Notes |
|-------|-------------|-------|
| `pni` | `pnpm install` | Faster than npm install |
| `pnid` | `pnpm install -D` | Dev dependency |
| `pnig` | `pnpm install -g` | Global package |
| `pnr` | `pnpm run` | Run any script |
| `pnrd` | `pnpm run dev` | Dev server |
| `pnrw` | `pnpm run watch` | Watch mode |
| `pnrb` | `pnpm run build` | Production build |
| `pns` | `pnpm start` | Start server |
| `pnrr` | `pnpm run reset && nrd` | Reset + restart |

</details>

---

## 🟣 Utility Aliases

> Control your shell environment like a pro.

<details>
<summary><b>🖼️ Visual Guide — Click to expand</b></summary>

<br/>

```
UTILITY ALIAS GUIDE
══════════════════════════════════════════════════════════════

  EDITING YOUR SHELL CONFIG
  ┌──────────────────────────────────────────────────────────┐
  │                                                          │
  │   nnb  ─────▶  nano ~/.bashrc   ─────▶  edit aliases    │
  │    │                                                     │
  │    └── save file ──▶  sb  ──▶  source ~/.bashrc         │
  │                       ↑                                  │
  │                  reload instantly!                       │
  │                  no restart needed ✅                    │
  └──────────────────────────────────────────────────────────┘

  BACKUP YOUR CONFIG
  ┌──────────────────────────────────────────────────────────┐
  │   cpb  →  copies ~/.bashrc to repo + git push           │
  │           (keeps your config backed up on GitHub!)       │
  └──────────────────────────────────────────────────────────┘

  LAUNCHING TOOLS
  ┌──────────────────────────────────────────────────────────┐
  │   cs    →  cursor          (Cursor AI editor)            │
  │   qd    →  qoder           (Qoder app)                   │
  │   lise  →  live-server     (browser live-reload)         │
  │   ntt   →  wt -w 0 nt -d  (new Windows Terminal tab)    │
  │   cls   →  clear           (clean terminal screen)       │
  └──────────────────────────────────────────────────────────┘
```

</details>

<details>
<summary><b>📖 Full Alias Table — Click to expand</b></summary>

<br/>

| Alias | Full Command | What It Does |
|-------|-------------|--------------|
| `nnb` | `nano ~/.bashrc` | Open `.bashrc` in nano to edit aliases |
| `sb` | `source ~/.bashrc` | **Reload aliases** without restarting terminal |
| `cpb` | `cd .../cp ~/.bashrc && git push` | Backup `.bashrc` to this GitHub repo |
| `cls` | `clear` | Clear the terminal screen |
| `ntt` | `wt -w 0 nt -d` | New Windows Terminal tab in a given folder |
| `cs` | `cursor` | Launch the Cursor AI editor |
| `qd` | `qoder` | Launch the Qoder app |
| `lise` | `live-server` | Start live-server with auto-reload |

</details>

<details>
<summary><b>💡 Pro Tips — Click to expand</b></summary>

<br/>

**Adding a new alias:**
```bash
nnb                              # open ~/.bashrc in nano
# add your line:
# alias myalias='some long command'
# save with Ctrl+O, exit with Ctrl+X
sb                               # reload instantly!
myalias                          # test it works ✅
```

**Backing up your config:**
```bash
cpb   # one command → copies .bashrc → commits → pushes to GitHub
```

**Opening a project in Cursor from terminal:**
```bash
cdp              # jump to /d/Projects
cd my-app        # enter project
cs .             # open current folder in Cursor
```

</details>

---

## 🔵 Navigation Aliases

> Teleport between your most-visited folders instantly.

<details>
<summary><b>🖼️ Directory Map — Click to expand</b></summary>

<br/>

```
D: DRIVE STRUCTURE (KRAM's Machine)
══════════════════════════════════════════════════════════════

  cdd  ──▶  /d/                        (D: drive root)
             │
             ├── cdp ──▶ /d/Projects/  (all your projects)
             │            ├── my-app/
             │            ├── portfolio/
             │            └── aliases2/   ← you are here
             │
             ├── cdg ──▶ /d/GOMYCODE/  (bootcamp work)
             │            ├── week1/
             │            └── week2/
             │
             └── cdo ──▶ /d/OVES/      (OVES projects)


  💡 Customize these paths to match YOUR machine! See ⚠️ note below.
```

</details>

<details>
<summary><b>📖 Full Alias Table — Click to expand</b></summary>

<br/>

| Alias | Expands To | Goes To |
|-------|-----------|---------|
| `cdp` | `cd /d/Projects` | 📁 Main projects folder |
| `cdg` | `cd /d/GOMYCODE` | 📁 GOMYCODE bootcamp folder |
| `cdo` | `cd /d/OVES` | 📁 OVES folder |
| `cdd` | `cd /d` | 📁 D: drive root |

</details>

<details>
<summary><b>🛠️ Customize for YOUR machine — Click to expand</b></summary>

<br/>

```bash
# Open your bashrc
nnb

# Find the navigation section and update paths:

# BEFORE (KRAM's paths):
alias cdp='cd /d/Projects'
alias cdg='cd /d/GOMYCODE'

# AFTER (your paths):
alias cdp='cd ~/projects'
alias cdw='cd ~/work'
alias cdc='cd ~/code'

# Reload
sb
```

**Common path patterns by OS:**

| System | Home | Example |
|--------|------|---------|
| Windows (Git Bash) | `/c/Users/YourName` | `alias cdp='cd /c/Users/John/Projects'` |
| macOS / Linux | `~` or `/home/name` | `alias cdp='cd ~/projects'` |
| WSL | `/mnt/c/Users/...` | `alias cdp='cd /mnt/c/Users/John/Dev'` |

</details>

---

## 🗺️ Complete Alias Map

> Every alias at a glance — your complete terminal cheat sheet.

```
╔══════════════════════════════════════════════════════════════════════╗
║                    ALIASES2  —  FULL CHEAT SHEET                    ║
╠══════════════════════════════════════════════════════════════════════╣
║  GIT                          │  NPM                                 ║
║  ────────────────────────     │  ────────────────────────            ║
║  gi    →  git init            │  ni    →  npm install                ║
║  gs    →  git status          │  nid   →  npm install -D             ║
║  ga    →  git add             │  nig   →  npm install -g             ║
║  gaa   →  git add .           │  nr    →  npm run                    ║
║  gc    →  git commit -m       │  nrd   →  npm run dev                ║
║  gp    →  git push            │  nrw   →  npm run watch              ║
║  gpl   →  git pull            │  nrb   →  npm run build              ║
║  grao  →  git remote add org  │  ns    →  npm start                  ║
║  grv   →  git remote -v       │  nrr   →  npm run reset && nrd       ║
║  gpo   →  git push -u origin  │  lise  →  live-server                ║
║  gpom  →  git push -u org main│                                      ║
╠═══════════════════════════════╪══════════════════════════════════════╣
║  PNPM                         │  UTILITIES                           ║
║  ────────────────────────     │  ────────────────────────            ║
║  pni   →  pnpm install        │  nnb   →  nano ~/.bashrc             ║
║  pnid  →  pnpm install -D     │  sb    →  source ~/.bashrc           ║
║  pnig  →  pnpm install -g     │  cpb   →  backup bashrc to git       ║
║  pnr   →  pnpm run            │  cls   →  clear                      ║
║  pnrd  →  pnpm run dev        │  ntt   →  new terminal tab           ║
║  pnrw  →  pnpm run watch      │  cs    →  cursor                     ║
║  pnrb  →  pnpm run build      │  qd    →  qoder                      ║
║  pns   →  pnpm start          │                                      ║
║  pnrr  →  pnpm run reset+dev  │  NAVIGATION                          ║
║                               │  ────────────────────────            ║
║                               │  cdp   →  cd /d/Projects             ║
║                               │  cdg   →  cd /d/GOMYCODE             ║
║                               │  cdo   →  cd /d/OVES                 ║
║                               │  cdd   →  cd /d                      ║
╚══════════════════════════════════════════════════════════════════════╝
```

---

## 🔁 Real-World Workflows

> Copy-paste these complete workflows for your daily tasks.

<details>
<summary><b>🆕 Workflow 1: Starting a Fresh Project — Click to expand</b></summary>

<br/>

```bash
# ─────────────────────────────────────────────
# SCENARIO: Starting a new React app from scratch
# ─────────────────────────────────────────────

cdp                                    # cd /d/Projects
npx create-react-app my-app            # scaffold the app
cd my-app

gi                                     # git init (already done by CRA, but good habit)
grao https://github.com/you/my-app    # connect to GitHub
gaa                                    # stage everything
gc "init: create react app"            # first commit
gpom                                   # push to main ✅

ni                                     # install deps
nrd                                    # start dev server 🚀
```

</details>

<details>
<summary><b>📅 Workflow 2: Daily Development Loop — Click to expand</b></summary>

<br/>

```bash
# ─────────────────────────────────────────────
# SCENARIO: Working on a feature each morning
# ─────────────────────────────────────────────

cdp                         # jump to Projects
cd my-app                   # enter project folder
gpl                         # pull latest from teammates
nrd                         # start dev server

# ... write code for a few hours ...

gs                          # see what you changed
gaa                         # stage all changes
gc "feat: add user profile" # descriptive commit
gp                          # push to remote 🚀

# Done for the day!
```

</details>

<details>
<summary><b>🐛 Workflow 3: Hotfix on Production — Click to expand</b></summary>

<br/>

```bash
# ─────────────────────────────────────────────
# SCENARIO: Bug found, fix it fast!
# ─────────────────────────────────────────────

cdp && cd my-app            # get to the project fast
gpl                         # pull latest
gs                          # check status

# ... fix the bug ...

gaa                         # stage the fix
gc "fix: resolve null crash on login"   # clear commit message
gpom                        # push directly to main
nrb                         # rebuild for production
```

</details>

<details>
<summary><b>⚙️ Workflow 4: Updating Your Aliases — Click to expand</b></summary>

<br/>

```bash
# ─────────────────────────────────────────────
# SCENARIO: Adding a new alias to your config
# ─────────────────────────────────────────────

nnb                         # open ~/.bashrc in nano

# Add your new alias at the bottom:
# alias myalias='some long command here'

# Save: Ctrl+O → Enter → Ctrl+X

sb                          # reload shell instantly
myalias                     # test it works ✅
cpb                         # backup to GitHub 🔒
```

</details>

---

## ⚙️ Installation

### Option 1 — Clone & Source (Recommended)

```bash
# Clone the repo
git clone https://github.com/edwinnyandika/aliases2.git

# Append to your existing .bashrc (safe — doesn't overwrite)
cat aliases2/.bashrc >> ~/.bashrc

# Reload
source ~/.bashrc

# Test
gs   # should run: git status
```

### Option 2 — One-liner via curl

```bash
curl -sL https://raw.githubusercontent.com/edwinnyandika/aliases2/main/.bashrc >> ~/.bashrc && source ~/.bashrc
```

### Option 3 — Manual (Pick What You Want)

```bash
# Open your .bashrc
nano ~/.bashrc

# Paste only the aliases you want, e.g.:
alias gs='git status'
alias gaa='git add .'
alias gc='git commit -m'
alias gpom='git push -u origin main'
alias nrd='npm run dev'

# Save → Ctrl+O, Exit → Ctrl+X

# Reload
source ~/.bashrc
```

### ✅ Verify Everything Loaded

```bash
# Check all git aliases loaded:
alias | grep "^alias g"

# Check npm aliases:
alias | grep "^alias n"

# Check a specific one:
type gs   # should output: gs is aliased to 'git status'
```

---

## 🖥️ Custom Prompt

> This `.bashrc` replaces your default prompt with a colorized, git-aware version.

<details>
<summary><b>🖼️ Prompt Anatomy — Click to expand</b></summary>

<br/>

```
What you see in your terminal:

KRAM@DESKTOP MINGW64 ~/Projects/my-app (main)
$

  │       │       │         │              │
  │       │       │         │              └── 🔵 git branch
  │       │       │         └─────────────── 🟡 current directory
  │       │       └───────────────────────── 🟣 MSYSTEM (MINGW64)
  │       └───────────────────────────────── 🟢 machine hostname
  └───────────────────────────────────────── 🟢 your username


COLOR LEGEND:
  🟢 Green   →  KRAM@DESKTOP  (you + machine)
  🟣 Magenta →  MINGW64       (environment)
  🟡 Yellow  →  ~/Projects    (where you are)
  🔵 Cyan    →  (main)        (git branch)
  ⬜ White   →  $             (prompt symbol)
```

</details>

**The PS1 code in `.bashrc`:**
```bash
export PS1='\[\033]0;$TITLEPREFIX:$PWD\007\]\n\
\[\033[32m\]KRAM@\h \
\[\033[35m\]$MSYSTEM \
\[\033[33m\]\w\
\[\033[36m\]`__git_ps1`\
\[\033[0m\]\n$ '
```

**Customize your username:**
```bash
# Change KRAM to your name
export PS1='\[\033[32m\]YOURNAME@\h \[\033[35m\]$MSYSTEM \[\033[33m\]\w\[\033[36m\]`__git_ps1`\[\033[0m\]\n$ '
```

---

## 🎮 Test Yourself

> How well do you know the aliases? Work through these challenges! 👇

<details>
<summary><b>🧠 Quiz 1 — Alias to Command (Beginner)</b></summary>

<br/>

For each alias, think of the full command it runs. Then reveal the answer!

| Alias | Full Command |
|-------|-------------|
| `gs` | <details><summary>👁️ Reveal</summary>**`git status`** — shows what files changed</details> |
| `gaa` | <details><summary>👁️ Reveal</summary>**`git add .`** — stages all files</details> |
| `gc` | <details><summary>👁️ Reveal</summary>**`git commit -m`** — commit with message: `gc "msg"`</details> |
| `gpom` | <details><summary>👁️ Reveal</summary>**`git push -u origin main`** — first push to main</details> |
| `nrd` | <details><summary>👁️ Reveal</summary>**`npm run dev`** — start the dev server</details> |
| `sb` | <details><summary>👁️ Reveal</summary>**`source ~/.bashrc`** — reload shell config</details> |
| `cls` | <details><summary>👁️ Reveal</summary>**`clear`** — clear the terminal</details> |
| `cdp` | <details><summary>👁️ Reveal</summary>**`cd /d/Projects`** — jump to projects folder</details> |

</details>

<details>
<summary><b>🧠 Quiz 2 — Command to Alias (Intermediate)</b></summary>

<br/>

You see a full command — what's the alias?

| Full Command | Alias |
|-------------|-------|
| `git init` | <details><summary>👁️ Reveal</summary>**`gi`**</details> |
| `git remote add origin` | <details><summary>👁️ Reveal</summary>**`grao`**</details> |
| `git remote -v` | <details><summary>👁️ Reveal</summary>**`grv`**</details> |
| `npm install -D` | <details><summary>👁️ Reveal</summary>**`nid`**</details> |
| `npm install -g` | <details><summary>👁️ Reveal</summary>**`nig`**</details> |
| `pnpm run build` | <details><summary>👁️ Reveal</summary>**`pnrb`**</details> |
| `nano ~/.bashrc` | <details><summary>👁️ Reveal</summary>**`nnb`**</details> |
| `live-server` | <details><summary>👁️ Reveal</summary>**`lise`**</details> |

</details>

<details>
<summary><b>🧠 Quiz 3 — Fill In The Workflow (Advanced)</b></summary>

<br/>

Complete this real workflow using ONLY aliases:

```bash
# Scenario: You just created a new project folder.
# Fill in the blanks!

___                                    # 1. Initialize git
___ https://github.com/you/app.git    # 2. Add remote origin
___                                    # 3. Stage everything
___ "init: project setup"             # 4. First commit
___                                    # 5. Push to main
___                                    # 6. Install npm packages
___                                    # 7. Start the dev server
```

<details>
<summary>✅ Reveal All Answers</summary>

```bash
gi                                     # git init
grao https://github.com/you/app.git   # git remote add origin
gaa                                    # git add .
gc "init: project setup"              # git commit -m
gpom                                   # git push -u origin main
ni                                     # npm install
nrd                                    # npm run dev
```

**Score yourself:**
- 7/7 → 🏆 Alias Master
- 5-6/7 → 🥈 Getting there!
- 3-4/7 → 🥉 Keep practicing
- 0-2/7 → 📖 Study the cheat sheet above

</details>

</details>

<details>
<summary><b>🧠 Quiz 4 — npm vs pnpm (Expert)</b></summary>

<br/>

Match the npm alias to its pnpm equivalent:

| npm alias | pnpm alias |
|-----------|-----------|
| `ni` | <details><summary>👁️ Reveal</summary>**`pni`**</details> |
| `nrd` | <details><summary>👁️ Reveal</summary>**`pnrd`**</details> |
| `nrb` | <details><summary>👁️ Reveal</summary>**`pnrb`**</details> |
| `nid` | <details><summary>👁️ Reveal</summary>**`pnid`**</details> |
| `nig` | <details><summary>👁️ Reveal</summary>**`pnig`**</details> |

> 💡 **Pattern:** All pnpm aliases = `pn` prefix + rest of npm alias. Easy!

</details>

---

## 🏆 Skill Tree

> Track your alias mastery. Check off each skill as you learn it!

<details>
<summary><b>🌱 Level 1 — Beginner (click to see)</b></summary>

<br/>

```
BEGINNER ALIASES
═══════════════════════════════════════════

  [ ] gs    →  git status          ← start here!
  [ ] gaa   →  git add .
  [ ] gc    →  git commit -m
  [ ] gp    →  git push
  [ ] ni    →  npm install
  [ ] nrd   →  npm run dev
  [ ] cls   →  clear
  [ ] sb    →  source ~/.bashrc

Complete all 8 → unlock Level 2! 🔓
```

</details>

<details>
<summary><b>⚡ Level 2 — Intermediate (click to see)</b></summary>

<br/>

```
INTERMEDIATE ALIASES
═══════════════════════════════════════════

  [ ] gi    →  git init
  [ ] gpl   →  git pull
  [ ] gpom  →  git push -u origin main
  [ ] grao  →  git remote add origin
  [ ] nid   →  npm install -D
  [ ] nrb   →  npm run build
  [ ] cdp   →  cd /d/Projects
  [ ] nnb   →  nano ~/.bashrc

Complete all 8 → unlock Level 3! 🔓
```

</details>

<details>
<summary><b>🏆 Level 3 — Advanced (click to see)</b></summary>

<br/>

```
ADVANCED ALIASES
═══════════════════════════════════════════

  [ ] grv   →  git remote -v
  [ ] gpo   →  git push -u origin
  [ ] nig   →  npm install -g
  [ ] nrr   →  npm run reset && nrd
  [ ] pnrd  →  pnpm run dev
  [ ] pnrb  →  pnpm run build
  [ ] cpb   →  backup bashrc to GitHub
  [ ] lise  →  live-server

Complete all 8 → you're an ALIAS MASTER! 🏆
```

</details>

---

## ⚠️ Important Note

> 🚨 **KRAM's personal paths — do not blindly copy-paste!**

Some aliases reference **specific directories on KRAM's Windows machine**. Before using them, update these paths to match your system:

```bash
# ❌ KRAM's paths (won't work on your machine):
alias cdp='cd /d/Projects'
alias cdg='cd /d/GOMYCODE'
alias cdo='cd /d/OVES'
alias cpb='cd /d/Projects/Aliases && ...'

# ✅ Update to YOUR paths:
alias cdp='cd ~/projects'         # macOS / Linux
alias cdp='cd /c/Users/You/Dev'   # Windows Git Bash
```

Also, these tools must be installed for their aliases to work:

| Alias | Requires |
|-------|---------|
| `lise` | `npm install -g live-server` |
| `cs` | [Cursor editor](https://cursor.sh) installed |
| `qd` | Qoder installed |
| `ntt` | Windows Terminal installed |

---

<div align="center">

## 📊 Stats At A Glance

![Git](https://img.shields.io/badge/Git%20Aliases-11-F05032?style=flat-square&logo=git&logoColor=white)
![npm](https://img.shields.io/badge/npm%20Aliases-10-CB3837?style=flat-square&logo=npm&logoColor=white)
![pnpm](https://img.shields.io/badge/pnpm%20Aliases-9-F69220?style=flat-square&logo=pnpm&logoColor=white)
![Util](https://img.shields.io/badge/Utility%20Aliases-8-8B5CF6?style=flat-square)
![Nav](https://img.shields.io/badge/Nav%20Aliases-4-3B82F6?style=flat-square)
![Total](https://img.shields.io/badge/Total-42%20Aliases-39d353?style=flat-square)

<br/>

```
Made with ❤️ by KRAM
Fork it. Customize it. Make it yours.
```

[![Fork](https://img.shields.io/badge/Fork%20This%20Repo-39d353?style=for-the-badge&logo=github&logoColor=white)](https://github.com/edwinnyandika/aliases2/fork)

<br/>

<img src="https://capsule-render.vercel.app/api?type=wave&color=0:39d353,100:1a7f37&height=120&section=footer&animation=fadeIn" width="100%"/>

</div>
