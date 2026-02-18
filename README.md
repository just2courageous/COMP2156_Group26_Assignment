# COMP2156 Group 26 Assignment 1

## 👥 Group Members
- Courage Erhabor (101060853)
- Khan Hurmat (101326352)
- Apurba Masrafi (101468860)

## 📌 Project Description
This repository is for COMP2156 Group Assignment 1.  
It demonstrates a team Git workflow using branches, commits, pull requests, and CI/CD automation.

## 📁 Required Files
Each member creates 3 files:
- STUDENTID_gb.txt
- STUDENTID_devops.txt
- STUDENTID_sdlc.txt

## 🌿 Branching Strategy
- Main branch: `main`
- Each member works on their own branch using this format:
  - `STUDENTID-Name`
Examples:
- `101060853-Courage`
- `101468860-Masrafi`
- `101326352-Hurmat`

## ✅ CI/CD (Continuous Integration and Continuous Delivery)
This repository uses **GitHub Actions** for CI checks.
- Workflow file: `.github/workflows/ci.yml`
- Triggers:
  - Runs on **push**
  - Runs on **pull_request**
- Purpose:
  - Confirms required files exist
  - Confirms README exists
  - Provides automated checks before merging

## ▶️ Setup Instructions
1. Clone the repo:
   ```bash
   git clone https://github.com/just2courageous/COMP2156_Group26_Assignment.git
   cd COMP2156_Group26_Assignment
