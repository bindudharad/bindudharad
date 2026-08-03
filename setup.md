# 🚀 GitHub Profile Setup & Deployment Guide

Welcome to your new **Ultra-Premium, Cyber-AI GitHub Profile Repository**! This repository has been handcrafted with high-precision SVG graphics, custom GitHub Actions workflows, glassmorphism cards, dynamic stats widgets, and a luxury futuristic design language inspired by Apple, OpenAI, Linear, Vercel, and Tesla.

---

## 📋 Table of Contents
1. [Prerequisites](#-prerequisites)
2. [Step-by-step Deployment to GitHub](#-step-by-step-deployment-to-github)
3. [Configuring GitHub Actions Workflows](#-configuring-github-actions-workflows)
4. [Customizing Secrets & Tokens](#-customizing-secrets--tokens)
5. [Customizing Content & Links](#-customizing-content--links)
6. [Updating Animated SVGs & Graphics](#-updating-animated-svgs--graphics)
7. [Troubleshooting & FAQs](#-troubleshooting--faqs)

---

## ⚡ Prerequisites

To create a **Special Profile Repository** on GitHub (which renders on your public profile page `https://github.com/bindudharad`), your repository name **MUST** match your GitHub username exactly:

- **GitHub Username:** `bindudharad`
- **Repository Name:** `bindudharad`
- **Visibility:** `Public`
- **Initialize with README:** Checked (or push this complete project repository)

---

## 🛠️ Step-by-Step Deployment to GitHub

### Method A: Uploading directly via Git CLI (Recommended)

1. Extract the downloaded `bindudharad-profile.zip` (or use the repository directory).
2. Open a terminal in the folder containing `README.md`.
3. Run the following commands:

```bash
# 1. Initialize git repo
git init

# 2. Add all production files
git add .

# 3. Commit files
git commit -m "feat: initial release of ultra-premium github profile"

# 4. Rename default branch to main
git branch -M main

# 5. Add your remote repository URL (Replace if using SSH)
git remote add origin https://github.com/bindudharad/bindudharad.git

# 6. Push to GitHub
git push -u origin main --force
```

---

### Method B: Uploading via GitHub Web Interface

1. Go to [GitHub New Repository](https://github.com/new).
2. Set Repository Name to `bindudharad`.
3. Set Visibility to **Public**.
4. Click **Create Repository**.
5. Click **Uploading an existing file** link, drag and drop all files from this project (including `.github/`, `assets/`, `README_IMAGES/`, `README.md`, `LICENSE`, `setup.md`), and commit!

---

## ⚙️ Configuring GitHub Actions Workflows

This repository comes pre-configured with two automated GitHub Actions workflows inside `.github/workflows/`:

1. **`snake.yml`**: Generates an animated GitHub contribution grid snake eating your contribution dots every 24 hours.
2. **`metrics.yml`**: Generates complex GitHub profile metrics, language percentages, and activity graphs every 12 hours.

### Enabling Workflow Permissions on GitHub:

1. Navigate to your repository on GitHub: `https://github.com/bindudharad/bindudharad`
2. Go to **Settings** → **Actions** → **General**.
3. Scroll down to **Workflow permissions**.
4. Select **Read and write permissions**.
5. Check **Allow GitHub Actions to create and approve pull requests**.
6. Click **Save**.

### Triggering Workflows Manually for Immediate Generation:

1. Go to the **Actions** tab in your repository.
2. Select **Generate GitHub Contribution Snake Animation** on the left menu.
3. Click **Run workflow** → **Run workflow**.
4. Next, select **Generate GitHub Profile Metrics**.
5. Click **Run workflow** → **Run workflow**.

---

## 🔑 Customizing Secrets & Tokens (Optional)

### Setting up `METRICS_TOKEN` (For detailed private repo metrics or extended limits)
By default, the metrics workflow will use the built-in `${{ secrets.GITHUB_TOKEN }}`. If you want even richer metrics (including private repository activity or organization stats):

1. Go to [GitHub Developer Settings → Personal Access Tokens → Tokens (classic)](https://github.com/settings/tokens).
2. Click **Generate new token (classic)**.
3. Name: `METRICS_TOKEN`.
4. Scopes to check:
   - `repo` (Full control of private repositories)
   - `read:user` (Read user profile data)
   - `read:org` (Read org data)
5. Copy the generated token.
6. In your profile repo (`bindudharad/bindudharad`), go to **Settings** → **Secrets and variables** → **Actions**.
7. Click **New repository secret**.
8. Name: `METRICS_TOKEN`, Value: `<pasted_token>`.
9. Click **Add secret**.

---

## 🎨 Customizing Content & Links

### Customizing Links & Social Handles in `README.md`
Open `README.md` and update placeholder URLs:
- **Email:** Replace `bindudharad@gmail.com` with your active email address.
- **LinkedIn:** Replace `https://linkedin.com/in/bindudharad` with your LinkedIn profile URL.
- **Twitter/X:** Replace `https://twitter.com/bindudharad` with your Twitter handle.
- **Portfolio / Website:** Replace `https://bindudharad.dev` with your portfolio website URL.

---

## 🖼️ SVGs & Graphics Overview

| Asset Path | Description |
| :--- | :--- |
| `assets/banner.svg` | Hero header SVG with cyber grid background, floating neural constellation, and active status indicator. |
| `assets/footer.svg` | Luxury cyberpunk glowing footer banner with custom core emblem. |
| `assets/divider.svg` | Glowing cyan & purple gradient divider line with embedded diamond node. |
| `assets/background.svg` | Deep space cyber particle mesh SVG background. |
| `assets/projects/atlas-ai.svg` | Custom card visual for ATLAS AI (Desktop Automation Platform). |
| `assets/projects/idea-authenticity.svg` | Custom card visual for AI Idea Authenticity Platform. |
| `assets/projects/sheguard-ai.svg` | Custom card visual for SheGuard AI. |
| `assets/projects/trust-harvest.svg` | Custom card visual for Trust Harvest. |
| `assets/icons/*.svg` | Icon badges for AI Brain, Neural Network, Cyber Shield, and Blockchain. |

---

## ❓ Troubleshooting & FAQs

#### Q: The Snake animation image shows a broken image link.
**Answer:** The snake SVG is generated by GitHub Actions. Make sure you have enabled **Read and write permissions** under Repository Settings → Actions → General, and manually run the `Generate GitHub Contribution Snake Animation` workflow once under the Actions tab!

#### Q: The Visitor Counter badge is not showing up or showing zero.
**Answer:** The badge automatically initializes upon the first hit to your public profile page! Once pushed to `bindudharad/bindudharad`, refresh your profile page once to initialize the counter.

#### Q: How do I edit the project cards?
**Answer:** You can edit the text inside `assets/projects/*.svg` directly or update the HTML cards inside `README.md`!

---

<div align="center">
  <sub>Handcrafted for <b>Bindudhara D</b> • Built with 💙 and ⚡</sub>
</div>
