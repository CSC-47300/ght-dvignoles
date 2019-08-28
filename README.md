# Github-Pages-Markdown-Tutorial

We'll discuss how to create a Github Pages project page and talking a little bit about Markdown

The goal of this exercise is to show how you can create a public profile for your project & keep it seperate from your main code. 

Before we get into github pages, we will learn a little bit about using markdown.
1. clone this repository
2. create a new file in this repository called 'bio.md'
3. in the new file, fill out the following information:

```markdown
Syllabus Qs
-----------------------
1. What on the syllabus are you most interested in working on?
2. What on the syllabus do you find confusing/unclear? 
3. What on the syllabus scares you? 
```
4. add and commit the file:
  ```bash
  git add bio.md
  git commit -m "biography"
  ```
5. push the changes:
  ```
  git push
  ```

The basic steps for a github pages webpage are:

1. create a gh-pages branch (you can also tell github which branch or folder to serve the page from via the repository settings)
```bash
    git checkout -b gh-pages
```
2. create an index.html 
3. commit and push changes to the gh-pages branch
4. check out your new site. 
