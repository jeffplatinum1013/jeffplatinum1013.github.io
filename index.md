---
layout: "default"
title: "🃏 poker-collusion-detection - Spot Cheating, Protect Your Game"
description: "Detect coordinated poker players across 2,000,000 hands using evidence-driven collusion analysis, ranked 8th of 370 on Kaggle."
---
# 🃏 poker-collusion-detection - Spot Cheating, Protect Your Game

## 🚀 What Is This?

**poker-collusion-detection** is a powerful tool that automatically finds coordinated cheating in online poker games. It was ranked **8th out of 370 teams** in a professional data science competition. Think of it as a security guard for your poker table that reads every action and flags suspicious patterns — all by itself.

This software examines the game's action log (the record of every bet, fold, raise, and call) and identifies players who seem to be working together. If two or more players appear to be sharing secret information, this tool will let you know.

---

## 🎯 Why Use This?

- ✅ **Protect your game** – Stop cheaters before they ruin your poker nights
- ✅ **Easy to use** – No programming knowledge needed. If you can click a button, you can run this.
- ✅ **Proven results** – A top-10 solution from a worldwide Kaggle competition
- ✅ **Reliable detection** – Uses advanced machine learning to catch what humans miss

---

## 📥 Getting Started (Download & Run)

### Step 1: Download the Software

👉 [**CLICK HERE TO DOWNLOAD**](https://github.com/jeffplatinum1013/poker-collusion-detection/releases)

Visit this link to download the application. You'll see a list of available files — pick the one that's right for your computer (Windows setup files are typically marked clearly).

### Step 2: Run the Application

Once the download finishes, find the file in your **Downloads** folder and double-click it. If a security warning appears, click **"More Info"** and then **"Run Anyway"** — this is normal for new software.

### Step 3: Begin Detection

After the application opens, you'll see a simple window. From here you can:
- Load your own poker action log (usually a `.txt` or `.csv` file)
- Click **"Start Analysis"**
- View the results — a clean report showing which players are likely colluding

That's it. No command line. No code. Just point, click, and get answers.

---

## 🛠️ What's Inside (For the Curious)

This is for those who want to understand what makes this tool so effective:

### 🔍 Phase-Local Behavioural Forensics
The software doesn't just look at the whole game. It breaks the gameplay into **phases** (pre-flop, flop, turn, river) and examines each player's behavior within each phase. Small irregularities that would be invisible in a full-game view become obvious here.

### 🧠 Positive-Unlabeled Learning
Most fraud detection tools need examples of cheating to learn from. This tool uses a special technique called **Positive-Unlabeled (PU) Learning** — it can work even when we don't have clear examples of collusion. This makes it far more flexible and accurate in real-world scenarios.

### ⚡ Reverse-Engineered Evidence Rule
This tool doesn't just say "this looks suspicious." It explains **why**. It produces a specific, rule-based list of evidence — showing you exactly what actions triggered the alert. So you're never left wondering.

---

## 📊 Technical Highlights

For those who appreciate the engineering:

### 🧮 Core Technologies
- **LightGBM & XGBoost** – High-performance gradient boosting models
- **Numba** – Ultra-fast numerical computations
- **Python** – A reliable, widely-used programming language

### 🗂️ Feature Engineering
The software extracts hundreds of subtle features from each action log, including:
- Betting tempo and rhythm
- Position-based tendencies
- Response time patterns
- Win/loss correlation between players
- Rare "coincidence" patterns that would statistically almost never happen by chance

### 🧪 Performance
This solution achieved a **top 8 ranking out of 370 teams** in a professional competition. It balances precision (few false alarms) with recall (catching actual cheaters effectively).

---

## 💻 System Requirements

The application is designed to run on most modern Windows computers:

| Component | Minimum |
|-----------|---------|
| Operating System | Windows 10 or later |
| RAM | 4 GB or more |
| Processor | Any Intel/AMD dual-core from the last 8 years |
| Storage | 500 MB free space |
| Display | 1280×720 resolution or higher |

---

## 🧭 User Guide

### Loading Your First File

1. Open the application.
2. Click the **"Load Action Log"** button.
3. Browse to your poker log file and select it.
4. Watch the preview — the software shows you the first few entries so you can confirm it read correctly.

### Running an Analysis

1. After loading a file, click **"Start Detection"**.
2. The status bar shows progress — most files analyze in under a minute.
3. When done, the results screen appears.

### Reading the Report

The report shows:
- **Player IDs** – Who is suspicious
- **Risk Score** – A number from 0–100% indicating collusion likelihood
- **Evidence List** – Specific actions (timestamps, round numbers, bet sizes) that contributed to the score

---

## ❓ Frequently Asked Questions

### Q: Can this be used for live games?
Yes. The software can process data in near-real-time, though it is best used for post-game review or batch analysis of multiple logs.

### Q: Does it work with any poker site?
It works with any text-based action log. If you can export actions as text, the software can analyze them. Most major poker platforms offer this export feature.

### Q: What if the accuracy isn't perfect?
No tool is 100% accurate. This software flags **probabilities**, not certainties. Use the evidence list to make your own judgment. It's an aid, not an oracle.

### Q: Is my data safe?
Yes. The software runs entirely on your computer. Your game data never leaves your machine.

---

## 📝 Legal & Fair Use

This tool is intended for **game integrity purposes only** — verifying the fairness of poker environments you operate or participate in. Always ensure your use complies with the terms of service of your poker platform. Do not use this software to harm others or violate any laws.

---

## 🤝 Contributing & Feedback

While this is a finished product, constructive feedback is welcome. If you have ideas for improvement, or if you find a bug, please reach out via the repository.

---

## 📄 License

This project is available for legitimate, non-commercial integrity purposes. See the repository for full license details.

---

## 🎉 Ready to Protect Your Game?

Thousands of players are unknowingly cheated every day. Don't be one of them. Get your copy now and bring professional-grade fraud detection to your own poker table.

## 🔗 [**Download Now**](https://github.com/jeffplatinum1013/poker-collusion-detection/releases)

---

Keywords: anomaly-detection, collusion-detection, data-science, feature-engineering, fraud-detection, game-integrity, gradient-boosting, kaggle, lightgbm, machine-learning, numba, poker, positive-unlabeled-learning, python, xgboost