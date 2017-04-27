---
layout: post
title:  "#00 - Preliminary installations"
date:   2017-04-25 03:13:39 +0200
categories: installation chocolatey jekyll 
---
Preliminary steps before starting to code:
* install Jekyll locally
* write a first post
* deploy to GitHub pages
* document the lot

#### Installing Jekyll:
* For Windows machines, the [Jekyll site][jekyll-windows] recommends using **[Bash on Ubuntu on Windows][microsoft-ubuntu-about]**. Installed following [this][microsoft-ubuntu-install] step-by-step.
* Now let's turn our attention to **Jekyll**. The instructions provided by [David Burela][burela-jekyll-install] are pretty straight forward but I had to install the package manager **Chocolatey** first which is eplained [here][choco-install]
* Once installed, running the commands on the [quick start guide][jekyll-quick-start] is enough. I named it myblog just to be creative right from the start. *Note*: for starting the jekyll server in the future simply type `> bundle exec jekyll serve`.
* Once served up, check out the site locally in your brower [here][jekyll-localhost]
* Now deploy it to GitHub Pages following the instructions on [hongkiat][hongkiat-github-pages]
* For this, I need to install **Git** first locally. Done with Chocolatey through the terminal directly in **Visual Studio Code**. VSC must be 'run as administrator' for that purpose. Type `> choco install git`.

 [jekyll-windows]:            https://jekyllrb.com/docs/windows/
 [microsoft-ubuntu-about]:    https://msdn.microsoft.com/en-us/commandline/wsl/about
 [microsoft-ubuntu-install]:  https://msdn.microsoft.com/en-us/commandline/wsl/install_guide
 [burela-jekyll-install]:     https://davidburela.wordpress.com/2015/11/28/easily-install-jekyll-on-windows-with-3-command-prompt-entries-and-chocolatey/
 [choco-install]:             https://chocolatey.org/install
 [jekyll-quick-start]:        
 [jekyll-localhost]:          http://localhost:4000/
 [markdown-cheatsheet]:       https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
 [hongkiat-github-pages]:     http://www.hongkiat.com/blog/jekyll-github-pages/amp/