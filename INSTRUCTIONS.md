# Final Steps to Complete the Assignment

I have set up the project structure and generated most of the required files. To complete the assignment, you need to perform a few manual steps on GitHub.

## Part 1: GitHub UI (12 points)

You need to submit the **URL** of the following files from your GitHub repository.
Confirm these files exist in your repo (they are already created locally):
1. `README.md`
2. `LICENSE`
3. `CODE_OF_CONDUCT.md`
4. `CONTRIBUTING.md`
5. `simple-interest.sh`

**Action:**
1. Push the local changes to your GitHub repository:
   ```bash
   git push origin main
   ```
   If `origin` is not set to your fork, update it:
   ```bash
   git remote set-url origin https://github.com/<YOUR_USERNAME>/mcino-Introduction-to-Git-and-GitHub.git
   ```

## Part 2: Git CLI (8 points)

### Task 6: Verify Fork (`forked-repo`)
Run the following command in your terminal (Git Bash) and copy the output into the file `forked-repo` (replace the placeholder text):
```bash
curl https://api.github.com/repos/<YOUR_USERNAME>/mcino-Introduction-to-Git-and-GitHub > forked-repo
```

### Task 7: Verify Merge (`merge_branches`)
This file is already generated! You can submit the content of `merge_branches`.

### Task 8: Verify PR (`bug-fix-revert`)
1. Create a Pull Request on GitHub from `bug-fix-typo` branch to `main` (if you pushed `bug-fix-typo`).
   ```bash
   git push origin bug-fix-typo
   ```
2. Once the PR is created, note the PR number.
3. Run the following command and copy the output into the file `bug-fix-revert` (replace placeholder):
   ```bash
   curl https://api.github.com/repos/<YOUR_USERNAME>/mcino-Introduction-to-Git-and-GitHub/pulls/<PR_NUMBER> > bug-fix-revert
   ```

### Task 9: Verify Branches (`github-branches`)
This file is already generated! You can submit the content of `github-branches`.

---
Once all files are updated, commit and push them again to your repo, then submit the URLs/File contents as requested by the assignment.
