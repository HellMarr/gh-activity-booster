# 📈 GitHub Activity Booster
Tired of people judging developers by their green squares?
This repo generates fake but real commits every day to boost your GitHub activity chart.

# 🧠 Recruiters, take note: This is your reminder that contribution graphs are not a measure of skill. This repo is living proof.

# ⚙️ How It Works
A simple GitHub Action runs daily, making a random number of commits (1–20) to this repo, keeping your contribution graph nice and green 🌿.

# 🚀 How to Use It
Fork this repo to your own GitHub account.

Go to
Your fork → Settings → Actions → General, and:

Set Workflow permissions to Read and write permissions
Enable ✅ Allow GitHub Actions to create and approve pull requests
In
Settings → Secrets and variables → Actions, add your GitHub email:

Name: USER_EMAIL
Value: your actual GitHub email (visible in your GitHub email settings)
(Optional) Edit .github/workflows/commit-booster.yml to change:

Commit frequency (cron)
Max number of commits per run
Commit message style
# 🧪 Want to Test It Immediately?
You don’t need to wait until tomorrow.
Head to your fork → Actions → Daily Commits → Run workflow → Run workflow ✅

# 🤖 What This Proves
Green squares are easy to fake.
Instead of judging by graphs, check real projects, code quality, and communication.

Let your work speak louder than your squares.
