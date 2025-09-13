# 🚀 Linux + Git Commands Cheatsheet

## 🔹 Linux Commands
1. pwd  
   → Print working directory (shows current path)  

2. ls -l  
   → List directory contents with details  

3. cd <directory>  
   → Change directory (example: cd Documents/)  

4. mkdir <name>  
   → Create a new directory (example: mkdir projects)  

5. rm -rf <name>  
   → Remove directory or file recursively (example: rm -rf old_folder/)  

6. cp file1 file2  
   → Copy files (example: cp notes.txt backup_notes.txt)  

7. mv file1 file2  
   → Move or rename files (example: mv draft.txt final.txt)  

8. cat file.txt  
   → Show file contents (example: cat readme.md)  


## 🔹 Git Commands
9. git init  
   → Initialize a new Git repository  

10. git clone <url>  
    → Clone a remote repo (example: git clone git@github.com:user/repo.git)  

11. git status  
    → Show repo status (staged/unstaged changes)  

12. git add <file>  
    → Stage changes (example: git add readme.md)  

13. git commit -m "message"  
    → Commit staged changes with a message  

14. git log --oneline  
    → View commit history in compact form  

15. git push origin main  
    → Push commits to the remote `main` branch  
### Linux: `ls`
**Usage:** `ls -la`  
Lists files in a directory.  
- `-l` = long format  
- `-a` = show hidden files  

**Example:**
```bash
ls -la /etc
### Linux: `pwd` — Print working directory
**Usage:** `pwd`  
**What it does:** Prints the absolute path of the current directory.  
**Example:**
```bash
pwd
# /home/nishita/projects/linux-git-cheatsheet
### Linux: `cd` — Change directory
**Usage:** `cd <path>` • `cd ..` (up) • `cd ~` (home)  
**Example:**
```bash
cd ~/projects
cd ..
### Linux: `mkdir` — Make directory
**Usage:** `mkdir <name>` • `mkdir -p parent/child`  
**Example:**
```bash
mkdir demo && cd demo
mkdir -p logs/2025/09

**Usage:** `rm -rf <path>`  
**Warning:** Permanently deletes without prompt; double-check the path.  
**Example:**
```bash
rm -rf old_folder//

*Usage:* cp <src> <dst> • cp -r <dir> <dst>  
*Example:*
```bash
cp notes.txt backup_notes.txt
cp -r src/ backup/
**Usage:** `mv <src> <dst>`  
**Example:**
```bash
mv draft.txt final.txt
mv file.txt docs/file.txt

**Usage:** `cat <file>`  
**Example:**
```bash
cat README.md

**Usage:** `git init` • `git init -b main`  
**Example:**
```bash
git init -b main
**Usage:** `git clone <ssh-or-https-url>`  
**Example:**
```bash
git clone git@github.com:user/repo.git
### Git: `git status` — Show repository status
**Usage:** `git status`  
**Shows:** Current branch, staged/unstaged changes, untracked files.
### Git: `git add` — Stage changes
**Usage:** `git add <file>` • `git add .` (stage all changes)  
**Example:**
```bash
git add README.md
**Usage:** `git commit -m "meaningful message"`  
**Example:**
```bash
git commit -m "feat: add grep section"
