# lessons

In this repository you will find (PDF, documentation links, articles and more) has been shared during our learning period

## Slack

Our slack work space
[FbW-26](https://Fbw-26.slack.com/)

[Using Slack](https://get.slack.help/hc/en-us/articles/202288908-Format-your-messages)

## Ubuntu

1. eBook to introduce you to the world of Ubuntu and Linux.  
   [Getting Started with Ubuntu 16.04](./ubuntu/Getting_Started_with_Ubuntu_16.04.pdf)

1. Package management on Ubuntu using **apt**  
   [Ubuntu Help Page: apt](https://help.ubuntu.com/lts/serverguide/apt.html.en)

1. Set command aliases  
   [Set aliases Ubuntu/Debian Linux](https://www.hostingadvice.com/how-to/set-command-aliases-linuxubuntudebian/)

## Terminal

1. A Cheat Sheet with the most common terminal commands.

   - [CLI Basics](https://github.com/hnsreeny/terminal)

   - [CLI Cheat Sheet](./terminal/CLI-Cheat-Sheet.pdf)

1. History of CLI  
   [Video](https://www.youtube.com/watch?v=4RPtJ9UyHS0&feature=youtu.be)

## Markdown

1. Starter tutorial from GitHub  
   [Markdown tutorial](https://www.markdowntutorial.com)

1. Markdown CheatSheet  
   [Markdown CheatSheet](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)

## GIT

1. Git slides  
   [Slides ](https://github.com/hnsreeny/git/)

1. Official Documentation  
   [Git scm Doc](https://git-scm.com/doc)

1. Git Glossary  
   [Git Glossary](./git/glossary.md)

1. Github Training videos  
   [Github on Youtube](https://www.youtube.com/watch?v=noZnOSpcjYY&list=PLg7s6cbtAD15G8lNyoaYDuKZSKyJrgwB-&index=1)

1. Intro videos  
   [Git SCM Videos](https://git-scm.com/videos)

1. A cheat sheet for the most common git commands:  
   [Git Cheat Sheet](./git/git-cheatsheet-EN-grey.pdf)

### git setting

#### SSh Key

[Github](https://help.github.com/en/enterprise/2.15/user/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

#### New repo

```
echo "# YOUR-REPO-NAME" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:YOUR-ACCOUNT/YOUR-REPO.git
git push -u origin master

```

#### upstream

If you have cloned repository from someone and it would update often and you want to get those updates from time to time, then instead of editing origin it would be best to add a new remote:

```
$ git remote rename origin upstream
$ git remote add origin https://github.com/YOUR-ACCOUNT/YOUR_REPO
# or
git remote add origin git@github.com:YOUR-ACCOUNT/YOUR-REPO.git
```

Then whenever you want to check if there is changes from upstream, you can do:

```
$ git fetch upstream
```

However if you want to pull from the original repo you will use:

```
$ git pull upstream master
```

## The Internet

1. A youTube video about the history of the internet (2018)  
   [History of the internet](https://www.youtube.com/watch?v=oNUl_9ZYA6w)

1. History of the Internet  
   [Internet Society](https://www.internetsociety.org/internet/history-internet/)

## JavaScript

1. Slides
   [JavaScript](https://github.com/hnsreeny/javaScript/blob/master/JavaScript.pdf)
1. What is JS
   [Mozilla](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript)

1. JavaScript more great recourses  
   [JavaScript](https://github.com/FBw-26/lessons/blob/master/javaScript/README.md)
