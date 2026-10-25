# Meeting 4: make it your own

A small website about fish for practicing HTML, CSS, Git, and GitHub together. It uses one font, a simple layout, and no navigation or external links. No accounts, packages, or build tools are needed to run the page.

## Practice the Week 3 workflow

**Everyone creates their own branch.** Follow the Git Summary from last week's slides: clone → create a branch → make changes → commit → push → open a pull request → review.

For this exercise, leave your pull request open. **Do not merge it.**

### 1. Clone the repository

Copy the shared repository to your computer, then enter its folder:

```bash
git clone https://github.com/fremontdeveloperclub/dev-club-meeting-4.git
cd dev-club-meeting-4
```

### 2. Create your own branch

Before editing any files, create and switch to a new branch. Replace `your-name/task-1` with your own name and task, such as `maya/fish-heading`. Each student should choose a different branch name.

```bash
git switch -c your-name/task-1
```

Check which branch you are working on:

```bash
git branch --show-current
```

It should print your branch name, not `main`. Ask an officer if you are still on `main` before making changes.

### 3. Make a small change

Open the folder in your editor. `index.html` contains the words; `styles.css` controls the appearance. Search for `TODO` to find the five numbered comments. Choose one task and complete it on your own branch.

| Task | File | Change |
| --- | --- | --- |
| 1 | `index.html` | Write a new heading for the fish website. Keep `id="intro-title"` on the heading. |
| 2 | `index.html` | Rewrite the introduction to explain why you find fish interesting. |
| 3 | `styles.css` | Change `--accent` to another dark color. It changes the site name and borders. |
| 4 | `index.html` | Replace the third fish with your favorite fish and a short description. |
| 5 | `index.html` | Replace the gill fact with another fish fact and update its heading. |

The TODO comments are hints in the source code, so they do not appear on the website. Remove the comment for your task when you finish it. Keep your change focused on that task.

Save your file, then double-click `index.html` to open it in a browser. Refresh the browser after each edit to see your changes.

### 4. Stage and commit

Saving a file does not create a Git commit. Review your changes, stage the file you edited, and save a checkpoint:

```bash
git diff
git add index.html
git commit -m "Update the fish website heading"
```

For task 3, stage `styles.css` instead. Use a commit message that describes your change.

### 5. Push your branch

Upload your branch to the shared GitHub repository. Use the exact branch name you created in step 2:

```bash
git push -u origin your-name/task-1
```

Push your own branch, not `main`. If GitHub says you do not have permission, ask an officer for collaborator access.

### 6. Open a pull request

On GitHub, open a pull request with:

- **Base:** `main`
- **Compare:** your own branch

Give it a short title and describe what you changed. Opening a pull request proposes your changes; it does not merge them.

### 7. Review and leave it open

Ask a teammate or officer to review your pull request. If they request changes, edit and commit on the same branch, then run `git push` again. The existing pull request will update automatically. If GitHub reports a conflict, ask an officer to help you resolve it on your branch.

**Do not merge your pull request. Leave it open for the officers to review during the meeting.** Your task is complete when the pull request is open.
