Lab M5.04 - Branch Protection & PR Automation

Cloud Engineering Bootcamp - Week 5, Day 2
Module: Cloud Automation & CI/CD

Start Here: Fork, Clone, and Submit

You will complete this lab by working in your own fork of the lab repository and submitting a Pull Request (PR).

Fork the lab repository to your GitHub account.

Clone your fork locally:

git clone https://github.com/MaryaAhmadi/ce-lab-branch-protection-automation.git
cd ce-lab-branch-protection-automation

Follow all instructions below and save your work in this repo (files, screenshots, and notes).

When finished, submit your work:

git add . → git commit -m "Complete Lab M5.04" → git push

Open a Pull Request from your fork back to the original lab repo

Copy the PR URL and paste it into the Lab Submission field in the Student Portal

📋 Lab Overview

Configure branch protection rules and automated PR workflows to enforce code quality, security, and review standards before merging changes.

🎯 Learning Objectives

Configure branch protection rules on the main branch

Implement automated PR checks using GitHub Actions

Set up a CODEOWNERS file for automatic reviewer assignment

Configure required status checks and merge requirements

Implement automated PR labeling and assignment

📁 Repository Structure

ce-lab-branch-protection-automation/
├── .github/
│   ├── workflows/
│   │   ├── pr-checks.yml
│   │   ├── pr-labeler.yml
│   │   └── auto-assign.yml
│   ├── CODEOWNERS
│   └── pull_request_template.md
├── src/
├── README.md
└── .gitignore


✅ Submission Requirements

Branch Protection Configuration

Protection rules configured for main branch

Required status checks enforced (e.g., Validate Terraform)

Minimum review requirements set

PR Automation Workflows

Automated PR checks (CI workflows)

Auto-labeling based on file changes

Auto-assignment using CODEOWNERS

CODEOWNERS File

Team-based ownership rules

Automatic reviewer assignment

Documentation

Branch protection strategy documented

PR workflow explained