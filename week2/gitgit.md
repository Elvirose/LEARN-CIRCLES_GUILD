>Fork, commit, open a PR in GITHUB
```
PS C:\Users\elvir> gh --version
gh version 2.74.2 (2025-06-18)
https://github.com/cli/cli/releases/tag/v2.74.2
PS C:\Users\elvir> gh auth login
? Where do you use GitHub? GitHub.com
? What is your preferred protocol for Git operations on this host? HTTPS
? Authenticate Git with your GitHub credentials? Yes
? How would you like to authenticate GitHub CLI? Login with a web browser

Press Enter to open https://github.com/login/device in your browser...
✓ Authentication complete.
- gh config set -h github.com git_protocol https
✓ Configured git protocol
✓ Logged in as Elvirose
PS C:\Users\elvir> gh repo fork octocat/Spoon-Knife --clone
✓ Created fork Elvirose/Spoon-Knife
Cloning into 'Spoon-Knife'...
remote: Enumerating objects: 16, done.
remote: Total 16 (delta 0), reused 0 (delta 0), pack-reused 16 (from 1)
Receiving objects: 100% (16/16), done.
Resolving deltas: 100% (3/3), done.
From https://github.com/octocat/Spoon-Knife
 * [new branch]      change-the-title -> upstream/change-the-title
 * [new branch]      main             -> upstream/main
 * [new branch]      test-branch      -> upstream/test-branch
✓ Cloned fork
! Repository octocat/Spoon-Knife set as the default repository. To learn more about the default repository, run: gh repo set-default --help
PS C:\Users\elvir> cd Spoon-Knife

PS C:\Users\elvir\Spoon-Knife> notepad day8.md
PS C:\Users\elvir\Spoon-Knife> git add .
PS C:\Users\elvir\Spoon-Knife> git commit -m "Add day8.md - Day 8 task completed"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'elvir@ElviRose.(none)')
PS C:\Users\elvir\Spoon-Knife> git config --global user.name "Elvi Rose Joshi"
PS C:\Users\elvir\Spoon-Knife> git config --global user.email "elvirose351@gmail.com"
PS C:\Users\elvir\Spoon-Knife> git commit -m "Add day8.md - Day 8 task completed"
[main 5a08324] Add day8.md - Day 8 task completed
 1 file changed, 6 insertions(+)
 create mode 100644 day8.md
PS C:\Users\elvir\Spoon-Knife> git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 479 bytes | 239.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Elvirose/Spoon-Knife.git
   d0dd1f6..5a08324  main -> main
PS C:\Users\elvir\Spoon-Knife> gh pr create --title "Add day8.md" --body "Added day8.md for Git Day 8 task using GitHub CLI from PowerShell."

Creating pull request for Elvirose:main into main in octocat/Spoon-Knife

https://github.com/octocat/Spoon-Knife/pull/37047
PS C:\Users\elvir\Spoon-Knife>
```
