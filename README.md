# Meeting 4: make it your own

A small website about fish for practicing HTML, CSS, Git, and GitHub together. It uses one font, a simple layout, and no navigation or external links. No accounts, packages, or build tools are needed to run the page.

## Open the website

1. Clone this repository and open its folder in your editor.
2. Open `index.html` in a browser. You can double-click the file.
3. After an edit, save the file and refresh the browser to see the change.

`index.html` contains the words. `styles.css` controls the appearance.

## Five small changes

Search the files for `TODO` to find the five numbered comments. Pick a task with your group, then make your own version.

| Task | File | Change |
| --- | --- | --- |
| 1 | `index.html` | Write a new heading for the fish website. Keep `id="intro-title"` on the heading. |
| 2 | `index.html` | Rewrite the introduction to explain why you find fish interesting. |
| 3 | `styles.css` | Change `--accent` to another dark color. It changes the site name and borders. |
| 4 | `index.html` | Replace the third fish with your favorite fish and a short description. |
| 5 | `index.html` | Replace the gill fact with another fish fact and update its heading. |

The TODO comments are hints in the source code, so they do not appear on the website. Remove the comment for a task when you finish it. Keep your change focused on your assigned task so everyone's work is easier to combine.

## Share your changes

Use your own branch. Replace the example branch name with your own name and task:

```bash
git clone https://github.com/fremontdeveloperclub/dev-club-meeting-4.git
cd dev-club-meeting-4
git switch -c your-name/task-1
```

Edit your file, save it, and check the page in your browser. Then review and commit your change:

```bash
git diff
git add index.html
git commit -m "Update the fish website heading"
git push -u origin your-name/task-1
```

For task 3, stage `styles.css` instead. Use a commit message that describes your change. Open a pull request on GitHub and ask a teammate to review it before merging.

If you do not have permission to push to this repository, ask an officer for collaborator access or fork the repository and clone your fork instead.
