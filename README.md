# Society of Capital Design, website

Five sheet site plus a login protected editor at admin.html. All
content (events, essay cycles, results, chapters, leadership,
numbers, Bulletin issues, emails) lives in content.json and is edited
entirely on the site. The GitHub repository is the database: every
save from the editor is a commit, and GitHub Pages republishes free.
No paid services anywhere.

## First time setup
Follow ADMIN-SETUP.txt: create a fine grained GitHub token (Contents
read and write on this repo only), upload these files, turn on GitHub
Pages, sign in at /admin.html.

## Day to day editing
yoursite/admin.html, sign in with your token, use the tabs. Photos
and PDFs upload from your phone. Saves go live in about a minute.

## Files
* index.html, about.html, events.html, newsletter.html, join.html:
  the five public sheets
* admin.html: the editor (token sign in, tokens made only by you)
* content.json: all site content, edited through admin.html
* config.js: the repo identity (owner, repo, branch)
* scd-logo.jpg: the logo used in every header
* ADMIN-SETUP.txt: one time setup steps
* HOW-TO-EDIT.txt: editing guide and publishing rules
* challenge-section-SAVED-FOR-LATER.html: the Capital Design
  Challenge section, held until the event is actually scheduled
