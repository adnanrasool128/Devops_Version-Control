# 🚀 DevOps: Version Control

![Version Control](https://img.shields.io/badge/Version%20Control-SVN%20%7C%20Mercurial-blue.svg)
![GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-orange.svg)

---

## 📌 Overview
This repository provides an in-depth guide to **Subversion (SVN)** and **Mercurial (Hg)**, two version control systems, as part of a **DevOps workflow**.

### ✨ Features
✅ **Step-by-step setup for SVN and Mercurial**  
✅ **Commonly used commands with explanations**  
✅ **Branching, merging, and conflict resolution**  
✅ **Security configurations and authentication management**  
✅ **Comparison between SVN and Mercurial**  
✅ **Best practices for version control in DevOps**  

---

## 🎯 Subversion (SVN) — *Centralized Version Control*
### 🔹 **Installation**
#### 🖥️ Linux (Ubuntu/Debian)
```bash
sudo apt update
sudo apt install subversion
```

### 🔹 **Common SVN Commands**
| Task | Command |
|---|---|
| 🏗 Initialize Repository | `svnadmin create /var/svn/repos/myrepo` |
| 📥 Checkout Repository | `svn checkout svn://localhost/myrepo --username alice` |
| 📄 Add & Commit Files | `svn add file.txt && svn commit -m "Added file.txt"` |
| 🔀 Create & Switch Branches | `svn copy` & `svn switch` |
| 🔄 Merge & Resolve Conflicts | `svn merge` & `svn resolve --accept working file.txt` |
| 🗑 Delete a File | `svn delete file.txt && svn commit -m "Deleted file.txt"` |

---

## 🛠 Mercurial (Hg) — *Distributed Version Control*
### 🔹 **Installation**
#### 🖥️ Linux (Ubuntu/Debian)
```bash
sudo apt install mercurial
```

### 🔹 **Common Mercurial Commands**
| Task | Command |
|---|---|
| 🏗 Initialize Repository | `hg init my_project` |
| 📄 Add & Commit Files | `hg add file.txt && hg commit -m "Initial commit"` |
| 🔁 Clone Repository | `hg clone https://www.mercurial-scm.org/repo/hello` |
| 🚀 Push Changes | `hg push` |

---

## 🌐 Hosting on GitHub Pages
1. **Initialize a Git Repository**
```bash
git init
git add .
git commit -m "Initial commit"
```
2. **Push to GitHub**
```bash
git remote add origin https://github.com/yourusername/devops_version_control.git
git branch -M main
git push -u origin main
```
3. **Enable GitHub Pages**
   - Navigate to **Settings > Pages** in your GitHub repository.
   - Select the **main** branch and save.

🔗 **Your GitHub Pages URL:**  
```
https://yourusername.github.io/devops_version_control/
```

---

## 🎨 Visual Comparison
| Feature | SVN | Mercurial |
|---|---|---|
| **Architecture** | Centralized | Distributed |
| **Branching** | Manual branching | Lightweight branching |
| **Speed** | Slower for large projects | Faster with better scaling |
| **Use Case** | Large enterprises | Agile development teams |

---

## 🚀 Conclusion
This repository is a comprehensive guide for managing **version control** in a **DevOps environment** using **SVN and Mercurial**. Feel free to explore and contribute! 🎉
