## Horiseon Refactor Webpage

## Description

```
As a marketing agency our services are Search Engine Optimization, Online Reputation Management, Social Media Marketing
```

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Getting Started

```

I have changed the title element and added more semantic elements rather than divs.
I have checked all the links are working and fixed
I have added alt attribute to all img tags.
Created some new classes for CSS file and added those in HTML page.
Rearranged the CSS file to remove duplications.

```

## Code Snippet

```shiby@LAPTOP-UT5MGDS6 MINGW64 /c/bootcamp/Challenges
$ cd Horiseon-Solutions/

shiby@LAPTOP-UT5MGDS6 MINGW64 /c/bootcamp/Challenges/Horiseon-Solutions (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md
        modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")

shiby@LAPTOP-UT5MGDS6 MINGW64 /c/bootcamp/Challenges/Horiseon-Solutions (main)
$ git add -A
warning: in the working copy of 'index.html', CRLF will be replaced by LF the next time Git touches it

shiby@LAPTOP-UT5MGDS6 MINGW64 /c/bootcamp/Challenges/Horiseon-Solutions (main)
$ git commit -m "added main tag to html"
[main 79e5a1a] added main tag to html
 2 files changed, 92 insertions(+), 80 deletions(-)

shiby@LAPTOP-UT5MGDS6 MINGW64 /c/bootcamp/Challenges/Horiseon-Solutions (main)
$ git pull origin main
Enter passphrase for key '/c/Users/shiby/.ssh/id_ed25519':
From github.com:Shiby-Mathew/Horiseon-Solutions
 * branch            main       -> FETCH_HEAD
Already up to date.

shiby@LAPTOP-UT5MGDS6 MINGW64 /c/bootcamp/Challenges/Horiseon-Solutions (main)
$ git push origin main
Enter passphrase for key '/c/Users/shiby/.ssh/id_ed25519':
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 871 bytes | 96.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To github.com:Shiby-Mathew/Horiseon-Solutions.git
   1f13e63..79e5a1a  main -> main

shiby@LAPTOP-UT5MGDS6 MINGW64 /c/bootcamp/Challenges/Horiseon-Solutions (main)
$

```

## Mock-Up

The following image shows the web application's appearance and functionality:

![The Horiseon webpage includes a navigation bar, a header image, and cards with text and images at the bottom of the page.]("./assets/images/01-html-css-git-homework-demo.png")
