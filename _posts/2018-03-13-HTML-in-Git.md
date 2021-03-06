---
layout: post
title: Displaying an HTML Page in Git
tags: Git HTML Rmd R
---

**13 March 2018** -- Setting up an HTML page in GitHub is not difficult but it is a bit lengthy. Just follow these steps.

1.  Create the HTML from your RMarkdown document and save to your local directory.
2.  Create a new repo, or go to an existing repo, in your GitHub.
3.  In the repo, create a new file called `docs/index.html`.
4.  In the `index.html` file, type this code: `<html><body><p>Hello World</p></body></html>`
5.  Commit the file.
6.  In the repo, click on the Settings tab.
7.  Scroll down to GitHub Pages Section.
8.  Under "Source", choose "master branch/docs folder" and save. If that doesn't work, try the "master branch" and save.
9.  A message will appear that your site is read to be published. Click on the link.
10. When Git finds the `index.html` file in a `docs/` folder, it creates a web address for the contents. The address takes the form: `http://username.github.io/repository`
11. Go to that address. You should see your "Hello World" greeting. That is your `index.html` file.
12. Go back to the `docs/` folder and open it.
13. Upload the HTML file you created in RMarkdown and commit.
14. Return to your github.io site but add the HTML file name to the address: `http://username.github.io/repository/filename.html`.
15. You should find your HTML posted there.
