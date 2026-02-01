# Git Branching Demo: Multi-Page Website

Welcome! This repository serves as a hands-on laboratory for understanding **Git Branching**. Instead of just looking at a finished product, you can "time travel" through the development of a mockup website by switching between different branches.

---

## 💡 The Concept

Each branch represents a specific milestone in the development of this site. We follow a **Start/Finish** pattern:
* **`-start`**: The "scaffolding" or empty state of a feature.
* **`-finish`**: The polished, final version of that feature.

This allows you to see not just the final code, but the *process* of building it.

---

## 🚀 How to Use This Repository

You can jump to any point in the development history by checking out a specific branch. Use the `git switch` command (for modern Git versions) or `git checkout`.

```bash
# Example: Switch to the starting point for the 'team' page
git switch team-start

# Or, using the older command:
git checkout team-start
```

To see the final version of the team page, you would then switch to `team-finish`.

---

## 📍 Branch Map

| Branch | Stage | Description |
| :--- | :--- | :--- |
| `main` | 🏁 **Final** | The complete, combined website with all pages linked. |
| `home-start` | 🏗️ **Start** | A basic `index.html` file with a title. |
| `home-finish` | ✅ **Finish** | A complete, styled home page with header, showcase, and content sections. |
| `about-start` | 🏗️ **Start** | An empty `about.html` file. |
| `about-finish` | ✅ **Finish** | A complete "About Us" page with shared navigation and styling. |
| `team-start` | 🏗️ **Start** | A basic `team.html` file with placeholder text. |
| `team-finish` | ✅ **Finish** | A styled team page with profile cards and shared navigation. |
| `contact-start` | 🏗️ **Start** | An empty `contact.html` file. |
| `contact-finish` | ✅ **Finish** | A complete contact page with a form, contact details, and shared navigation. |

---
