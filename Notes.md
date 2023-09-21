# Git/Github notes

**Main Workflow:**
1. Make a repository on Github
2. Clone to local machine.
3. Perform changes on it.
4. Add changes.
5. Commit.
6. Push the changes.

-**Link to cheat sheet:**
[Click here](https://lwfiles.mycourse.app/62a6cd5e1e9e2fbf212d608d-public/publicFiles/git-cheat-sheet-education.pdf)

## GIT Commands:

- **To add user info:**
1. git config --global user.name “[firstname lastname]”

2. git config --global user.email “[valid-email]”
- **STAGE & SNAPSHOT:**

1. git status:

2. git add [file]

3. git reset [file]:

4. git diff

5. git diff --staged

- **BRANCH & MERGE:**

1. git branch

2. git merge -M main

3. git checkout [branch name]

4. git checkout -b [new branch mane]

5. git branch -d [branch name]

6. git diff [branch name]

7. git merge [branch name]

-**SHARE & UPDATE:**

1. git pull
- fetch and merge any commits from the tracking remote branch

2. git push
- Transmit local branch commits to the remote repository branch

- **INSPECT & COMPARE:**
1. git log

2. git log branchB..branchA

3. git diff branchB...branchA

- **TRACKING PATH CHANGES:**

1. git rm [file]

2. git mv [existing-path] [new-path]

3. git log --stat -M

- **TEMPORARY COMMITS:**
- Temporarily store modified, tracked files in order to change branches
1. git stash

2. git stash list

3. git stash pop

4. git stash drop

-**Undoing changes:**
1. Staged changes:
- git reset [file name]
- git reset

2. Committed changes:
- git reset HEAD~1

3. For many commits:
- git reset [commit hash]
- git reset --hard [commit hash]

- **Remote commands:**
1. git remote
2. git remote -v

***

# Markdown Notes:

Important link:
- [To learn markdown via yt](https://www.youtube.com/watch?v=bpdvNwvEeSE "Hitesh Choudhary yt link")

**Syntax:**

- #For Heading1

- ##For Heading2

- _ before and _ after to **italicise**

- **"before" and ** after a text to **bold** it

- ~~ before and after to scratch a text

- For links: "[]" and then ().First for writing and second for link.

- For images :Same as above just use ! at first position and image in .png link format

- For code block: ```before text and after text and in between 1st line write coding language

- For Tables:use |

- Quotes: > Then text

- Use "-" to get bullet list

- For a line at the end use "---" or "***"

---
## Course notes

