# Complete Beginner Guide to Git & GitHub

This README is written for **absolute beginners** to understand **Git and GitHub** in a clear, structured, and professional way. It is suitable for **software engineering students**, **CS beginners**, and anyone entering the **software industry**.

---

## 1️⃣ Introduction to Git & GitHub

### What is Git?

**Git** is a **version control system** used in the software industry to track changes in source code.

In simple words:

> Git keeps a record of every change made to your code so you can manage, review, and restore it whenever needed.

### Why Git is Important in the Software Industry

* Tracks code changes
* Prevents loss of work
* Helps multiple developers work on the same project
* Maintains complete project history

---

### What is GitHub?

**GitHub** is a **cloud-based platform** that hosts Git repositories.

In simple words:

> GitHub is an online place where developers store, share, and collaborate on code using Git.

### Why GitHub is Used in the Software Industry

* Online backup of projects
* Team collaboration
* Code review and project management
* Open-source development
* Portfolio building for developers

---

## 2️⃣ Difference Between Git and GitHub

| Git                      | GitHub                  |
| ------------------------ | ----------------------- |
| Version control software | Online hosting platform |
| Runs locally on computer | Runs on the internet    |
| Tracks code changes      | Stores and shares code  |
| Works without internet   | Requires internet       |

---

## 3️⃣ How Git & GitHub Work Together

1. Developer writes code on local machine
2. Git tracks changes locally
3. Code is committed (saved)
4. GitHub stores the code online
5. Team members collaborate using GitHub

---

## 4️⃣ Installing Git

### Step 1: Download Git

Download Git from the official website:
[https://git-scm.com](https://git-scm.com)

### Step 2: Install Git

* Use default settings during installation
* Finish installation

### Step 3: Verify Installation

```bash
git --version
```

If Git is installed correctly, the version will be displayed.

---

## 5️⃣ Basic Git Configuration (Very Important)

Git configuration tells Git **who you are**.

### Configure User Name

```bash
git config --global user.name "Your Full Name"
```

### Configure Email Address

```bash
git config --global user.email "your-email@example.com"
```

> The email should be the same as your GitHub account email.

### Check Configuration

```bash
git config --list
```

---

## 6️⃣ Creating Your First Git Repository

### Step 1: Create a Project Folder

```bash
mkdir my-project
cd my-project
```

### Step 2: Initialize Git

```bash
git init
```

This command creates a **Git repository** in the folder.

---

## 7️⃣ Basic Git Commands (Beginner Level)

### git status

```bash
git status
```

Shows the current state of files.

---

### git add

```bash
git add filename
```

Add all files:

```bash
git add .
```

Moves files to the staging area.

---

### git commit

```bash
git commit -m "Your message"
```

Saves changes permanently with a message.

---

### git log

```bash
git log
```

Displays commit history.

---

## 8️⃣ Introduction to GitHub (Practical)

### Step 1: Create a GitHub Account

* Visit [https://github.com](https://github.com)
* Sign up

### Step 2: Create a New Repository

* Click **New Repository**
* Enter repository name
* Choose Public or Private

---

## 9️⃣ Connecting Local Git with GitHub

### Add Remote Repository

```bash
git remote add origin https://github.com/username/repository-name.git
```

### Push Code to GitHub

```bash
git branch -M main
git push -u origin main
```

---

## 🔟 Understanding Branches in Git

### What is a Branch?

A **branch** is a separate version of the project.

In simple words:

> Branch allows developers to work on new features without affecting the main code.

### Why Branches Are Used

* Feature development
* Bug fixing
* Safe experimentation

---

### Common Branch Commands

Create a branch:

```bash
git branch feature-1
```

Switch branch:

```bash
git checkout feature-1
```

Create and switch together:

```bash
git checkout -b feature-1
```

---

## 1️⃣1️⃣ Daily Use Commands

```bash
git pull   # Get latest code from GitHub
git push   # Upload code to GitHub
```

---

## 1️⃣2️⃣ Common Beginner Mistakes

* Not configuring Git
* Forgetting git add
* Writing unclear commit messages
* Pushing without pulling latest changes

---

## 1️⃣3️⃣ Best Practices for Students

* Practice Git daily
* Use meaningful commit messages
* Create branches for new features
* Keep GitHub profile updated

---

## 1️⃣4️⃣ Practice Assignment for Students

1. Create a new folder
2. Initialize Git
3. Create a file (README.md)
4. Add and commit the file
5. Push the project to GitHub
6. Create a new branch

---

Happy Learning 🚀

**Instructor:** Fahad Ahmed
