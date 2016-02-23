# git-instructions

## What's Git?

Git is what's called a version control system. Many of you may have used one before—there's quite a few out there: Git, Subversion, Mercurial, Dimensions…

How is Git different? It's free. It's open source. It is fast and scalable. It works on Windows, Linux, OS X, and more. It lets you work locally on a whole project—no need to be connected to the network or a central repository. It's easy to create branches for new features. It's super flexible. It's widely used.

## What's GitHub?

It's the site you're on now! Simply, it is a web-based host for your Git repositories (i.e. projects). It's totally free to use if you plan on making your projects public. And it offers a bunch of niceties on top of plain Git, which make development and collaboration easier. These include:

- Bug tracking
- Feature requests
- Task management (i.e. you can assign people)
- Wikis for your projects (if you want them)
- Easy static website creation and hosting through [GitHub pages](https://pages.github.com/)

You can put your [web app](https://github.com/18F/openFEC-web-app), [command line client](https://github.com/dcgov/dcgov-cli), [map](https://github.com/blog/1528-there-s-a-map-for-that), [3D model](https://github.com/blog/1465-stl-file-viewing), [text](https://github.com/showcases/writing), and other projects as GitHub repositories.

## Who Uses GitHub?

A whole lot of people and organizations.

DC Government uses it. You're on one of its repositories.

Over 500 other [government organizations](https://government.github.com/) use it. So do [Code for DC](https://github.com/codefordc), [Google](https://github.com/google), the [Open Knowledge Foundation](https://github.com/okfn), [Facebook](https://github.com/facebook), and many individuals, like [me](https://github.com/emanuelfeld) and hopefully you too!

One of the big benefits of GitHub is that **it's social**. It makes it easy to follow others, reuse their projects (when openly licensed), share your own, and collaborate outside of your team.

## Getting Set Up with Git and GitHub

### Windows

1. Sign up for a GitHub account at https://github.com
2. Download the GitHub Desktop Client application from https://desktop.github.com/
3. Download the command line interface from https://git-for-windows.github.io/
4. Open Git Bash on your computer and run:
        
        git config --global user.name "Your Name"
        git config --global user.email "your_email@whatever.com"

5. Set up GitHub authentication caching on your computer by following the instructions at https://help.github.com/articles/caching-your-github-password-in-git/#platform-windows

### Mac

1. Sign up for a GitHub account at https://github.com
2. Download the GitHub Desktop Client application from https://desktop.github.com/
3. Open Terminal on your computer and run:

        git config --global user.name "Your Name"
        git config --global user.email "your_email@whatever.com"

4. Set up GitHub authentication caching on your computer by following the instructions at https://help.github.com/articles/caching-your-github-password-in-git/

## Learn to Use Git and GitHub

- https://try.github.io/ is a browser-based tutorial that takes you step by step through 25 "challenges"
- http://gitimmersion.com/index.html provides a full length Git tutorial, walking you through setup and usage on your own computer (Windows and Mac)

Once you've gone through those, checkout out [git - the simple guide](https://rogerdudler.github.io/git-guide/) for a refresher on commands.

Git supports many different approaches to coordinating work between developers. If you're looking for ideas on how best to manage your team, check out [Git Flow](http://nvie.com/posts/a-successful-git-branching-model/).
