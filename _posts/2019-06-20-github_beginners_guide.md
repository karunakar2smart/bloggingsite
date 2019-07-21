--- 
title: Github for beginners- right from the command line to hosting a website(2019).
permalink: Blog/github_beginners_guide.html
layout: post 
image: upload/github-guide-for-beginners.png
description: "In this Github for beginners post, you will get introduced to Github & its various commands. It talks about Github pages, repo, installs Git, Git commands & desktop, hosting with Jekyll, etc for complete newbies." 
datepublished: "2019-06-20" 
datemodified: "2019-07-21"
margin-top: -540px

---

<div class="imp_container">
<div class="important_links">
					<ol><span style="color: black; margin-bottom: 5px;">A complete beginners guide for Github.</span>
						<br>
						<li style="list-style-position: inside;"><a href="#github"><h2><strong style="font-weight: 600;">What is Github?</strong></h2></a></li>
						<li style="list-style-position: inside;"><a href="#git"><h2><strong style="font-weight: 600;">What is Git?</strong></h2></a></li>
						<li style="list-style-position: inside;"><a href="#version-control-system"><h2><strong style="font-weight: 600;">What is version control system?</strong></h2></a></li>
						<li style="list-style-position: inside;"><a href="#github-pages"><h2><strong style="font-weight: 600;">What is GitHub Pages?</strong></h2></a></li>
						<li style="list-style-position: inside;"><a href="#install-git-in-pc"><h2><strong style="font-weight: 600;">How to install Git in pc?</strong></h2></a></li>
						<li style="list-style-position: inside;"><a href="#github-desktop"><h2><strong style="font-weight: 600;">What is Github Desktop?</strong></h2></a></li>
						<li style="list-style-position: inside;"><a href="#install-github-desktop"><h2><strong style="font-weight: 600;">How to install Github Desktop?</strong></h2></a></li>
						<li style="list-style-position: inside;"><a href="#git-commands"><h2><strong style="font-weight: 600;">What are some basic Git Commands?</strong></h2></a></li>
						<li style="list-style-position: inside;"><a href="#create-repo-in-github"><h2><strong style="font-weight: 600;">How to create a repository in Github?</strong></h2></a></li>
						<li style="list-style-position: inside;"><a href="#host-website-using-github-pages"><h2><strong style="font-weight: 600;">Can I host a website using Github Pages?</strong></h2></a></li>
						<li style="list-style-position: inside;"><a href="#jekyll"><h2><strong style="font-weight: 600;">What is Jekyll?</strong></h2></a></li>
						<li style="list-style-position: inside;"><a href="#custom-domain-to-github-pages"><h2><strong style="font-weight: 600;">Adding a custom domain to Github Pages?</strong></h2></a></li>
						<li style="list-style-position: inside;"><a href="#github-pages-with-HTTPS"><h2><strong style="font-weight: 600;">How to secure the Github Pages with HTTPS?</strong></h2></a></li>
						<li style="list-style-position: inside;"><a href="#usage-limits-of-github-pages"><h2><strong style="font-weight: 600;">What are the usage limits of Github Pages?</strong></h2></a></li>
					</ol>
				</div>
</div>

<div class="header-image">
<img src="#" data-src="../upload/github-guide-for-beginners.png" class="lazy" alt="github-guide-for-beginners" title="Github-beginners-guide-2019" class="lazy">
</div>

Do you ever ask yourself, “<b>What is GitHub?</b>” or wish you had an opportunity to learn the basics of Git? If you’ve always wanted to use GitHub, but haven’t quite been able to get up to speed. In this "Github for beginners" post, you will get introduced to Github &amp; its various commands. It talks about Github pages, repo, installs Git, Git commands &amp; desktop, hosting with Jekyll, etc for complete newbies. This beginner-friendly article is for you.

<h2 id="github"><strong>1. What is Github?</strong></h2>

Github is a web-based hosting service for version control using <strong>Git</strong>. Github is a place where developers store their open source software projects and networks with like-minded people and work together without any conflicts. Github provides access control and several collaboration features like creating repositories, pull requests, merge, commits, branches, etc for each and every project to make developer life better.

<div class="article_inside_notes">
<svg viewbox="0 0 448 512">
<path d="M400 32H48C21.5 32 0 53.5 0 80v352c0 26.5 21.5 48 48 48h352c26.5 0 48-21.5 48-48V80c0-26.5-21.5-48-48-48zM277.3 415.7c-8.4 1.5-11.5-3.7-11.5-8 0-5.4.2-33 .2-55.3 0-15.6-5.2-25.5-11.3-30.7 37-4.1 76-9.2 76-73.1 0-18.2-6.5-27.3-17.1-39 1.7-4.3 7.4-22-1.7-45-13.9-4.3-45.7 17.9-45.7 17.9-13.2-3.7-27.5-5.6-41.6-5.6-14.1 0-28.4 1.9-41.6 5.6 0 0-31.8-22.2-45.7-17.9-9.1 22.9-3.5 40.6-1.7 45-10.6 11.7-15.6 20.8-15.6 39 0 63.6 37.3 69 74.3 73.1-4.8 4.3-9.1 11.7-10.6 22.3-9.5 4.3-33.8 11.7-48.3-13.9-9.1-15.8-25.5-17.1-25.5-17.1-16.2-.2-1.1 10.2-1.1 10.2 10.8 5 18.4 24.2 18.4 24.2 9.7 29.7 56.1 19.7 56.1 19.7 0 13.9.2 36.5.2 40.6 0 4.3-3 9.5-11.5 8-66-22.1-112.2-84.9-112.2-158.3 0-91.8 70.2-161.5 162-161.5S388 165.6 388 257.4c.1 73.4-44.7 136.3-110.7 158.3zm-98.1-61.1c-1.9.4-3.7-.4-3.9-1.7-.2-1.5 1.1-2.8 3-3.2 1.9-.2 3.7.6 3.9 1.9.3 1.3-1 2.6-3 3zm-9.5-.9c0 1.3-1.5 2.4-3.5 2.4-2.2.2-3.7-.9-3.7-2.4 0-1.3 1.5-2.4 3.5-2.4 1.9-.2 3.7.9 3.7 2.4zm-13.7-1.1c-.4 1.3-2.4 1.9-4.1 1.3-1.9-.4-3.2-1.9-2.8-3.2.4-1.3 2.4-1.9 4.1-1.5 2 .6 3.3 2.1 2.8 3.4zm-12.3-5.4c-.9 1.1-2.8.9-4.3-.6-1.5-1.3-1.9-3.2-.9-4.1.9-1.1 2.8-.9 4.3.6 1.3 1.3 1.8 3.3.9 4.1zm-9.1-9.1c-.9.6-2.6 0-3.7-1.5s-1.1-3.2 0-3.9c1.1-.9 2.8-.2 3.7 1.3 1.1 1.5 1.1 3.3 0 4.1zm-6.5-9.7c-.9.9-2.4.4-3.5-.6-1.1-1.3-1.3-2.8-.4-3.5.9-.9 2.4-.4 3.5.6 1.1 1.3 1.3 2.8.4 3.5zm-6.7-7.4c-.4.9-1.7 1.1-2.8.4-1.3-.6-1.9-1.7-1.5-2.6.4-.6 1.5-.9 2.8-.4 1.3.7 1.9 1.8 1.5 2.6z" /> </svg>
<p>GitHub is a code hosting platform for collaboration and version control. GitHub lets you (and others) work together on projects.
<br> <strong>Github</strong> = <strong>Git</strong>(<strong>Version Control System</strong>) &amp; <strong>Hub</strong>(<strong>Code hosting platform</strong>).</p>
</div>

<h2 id="git"><strong>2. What is Git?</strong></h2>

Git is an Open Source <strong>DISTRIBUTED VERSION CONTROL SYSTEM</strong>. It is mainly used for source code management in software development. It is a Command Line Interface(CLI) tool and can be mastered easily.

<h2 id="version-control-system"><strong>3. What is Version Control System?</strong></h2>

Version control systems are a category of software tools that help a software team manage changes to source code over time. Version control software keeps track of <strong>every modification</strong> to the code in a special kind of database. If a mistake is made, developers can turn back the clock and compare earlier versions of the code to help fix the mistake while minimizing disruption to all team members.

VCS treats each file/change as a revision and coordinates work on those change among multiple people providing information like who edited or created it, when, what changes were made, etc. It also provides the ability to revert a file/change to a previous revision for allowing editors to track each other's edits, correct mistakes, and defend against vandalism and spamming. VCS can be distributed or centralized, but distributed has more advantages.

This development doesn’t depend on a single entity as VCS tends to be distributed. Each entity is treated with equal importance as others.

<div class="article_inside_links">
<ol>Developers can review project history to find out:
					<br>
					<br>
					<li>Which changes were made?</li>
					<li>Who made the changes?</li>
					<li>When were the changes made?</li>
					<li>Why were the changes needed?</li>
				</ol>
</div>

{% include googlead1.html %}

<h2 id="github-pages"><strong>4. What is GitHub Pages?</strong></h2>

<strong>GitHub Pages</strong> is a static site hosting service designed to host your personal, organization, or project pages directly from a GitHub repository. You can create and publish GitHub Pages sites online using the Jekyll Static site generator Or if you prefer to work locally, you can use <strong>GitHub Desktop</strong> or the command line. GitHub Pages doesn't support server-side code such as PHP, Ruby, or Python.

<div class="article_inside_notes">
<svg viewbox="0 0 448 512">
<path d="M400 32H48C21.5 32 0 53.5 0 80v352c0 26.5 21.5 48 48 48h352c26.5 0 48-21.5 48-48V80c0-26.5-21.5-48-48-48zM277.3 415.7c-8.4 1.5-11.5-3.7-11.5-8 0-5.4.2-33 .2-55.3 0-15.6-5.2-25.5-11.3-30.7 37-4.1 76-9.2 76-73.1 0-18.2-6.5-27.3-17.1-39 1.7-4.3 7.4-22-1.7-45-13.9-4.3-45.7 17.9-45.7 17.9-13.2-3.7-27.5-5.6-41.6-5.6-14.1 0-28.4 1.9-41.6 5.6 0 0-31.8-22.2-45.7-17.9-9.1 22.9-3.5 40.6-1.7 45-10.6 11.7-15.6 20.8-15.6 39 0 63.6 37.3 69 74.3 73.1-4.8 4.3-9.1 11.7-10.6 22.3-9.5 4.3-33.8 11.7-48.3-13.9-9.1-15.8-25.5-17.1-25.5-17.1-16.2-.2-1.1 10.2-1.1 10.2 10.8 5 18.4 24.2 18.4 24.2 9.7 29.7 56.1 19.7 56.1 19.7 0 13.9.2 36.5.2 40.6 0 4.3-3 9.5-11.5 8-66-22.1-112.2-84.9-112.2-158.3 0-91.8 70.2-161.5 162-161.5S388 165.6 388 257.4c.1 73.4-44.7 136.3-110.7 158.3zm-98.1-61.1c-1.9.4-3.7-.4-3.9-1.7-.2-1.5 1.1-2.8 3-3.2 1.9-.2 3.7.6 3.9 1.9.3 1.3-1 2.6-3 3zm-9.5-.9c0 1.3-1.5 2.4-3.5 2.4-2.2.2-3.7-.9-3.7-2.4 0-1.3 1.5-2.4 3.5-2.4 1.9-.2 3.7.9 3.7 2.4zm-13.7-1.1c-.4 1.3-2.4 1.9-4.1 1.3-1.9-.4-3.2-1.9-2.8-3.2.4-1.3 2.4-1.9 4.1-1.5 2 .6 3.3 2.1 2.8 3.4zm-12.3-5.4c-.9 1.1-2.8.9-4.3-.6-1.5-1.3-1.9-3.2-.9-4.1.9-1.1 2.8-.9 4.3.6 1.3 1.3 1.8 3.3.9 4.1zm-9.1-9.1c-.9.6-2.6 0-3.7-1.5s-1.1-3.2 0-3.9c1.1-.9 2.8-.2 3.7 1.3 1.1 1.5 1.1 3.3 0 4.1zm-6.5-9.7c-.9.9-2.4.4-3.5-.6-1.1-1.3-1.3-2.8-.4-3.5.9-.9 2.4-.4 3.5.6 1.1 1.3 1.3 2.8.4 3.5zm-6.7-7.4c-.4.9-1.7 1.1-2.8.4-1.3-.6-1.9-1.7-1.5-2.6.4-.6 1.5-.9 2.8-.4 1.3.7 1.9 1.8 1.5 2.6z" /> </svg>
<p>Ready to get started? Build your own site from scratch or generate one for your project. You get one site per GitHub account and organization, and unlimited project sites.
<br> Let's get started at <a href="https://pages.github.com/" rel="noopener" target="_blank">Github pages.</a></p>
</div>

<h2 id="install-git-in-pc"><strong>5. How to install Git in pc?</strong></h2>

Install Git on Windows. <strong>Download</strong> the [latest Git for Windows installer](https://git-scm.com/downloads){: target="_blank" rel="noopener"}. When you've successfully started the installer, you should see the Git Setup wizard screen. Open a Command Prompt (or Git Bash if during installation you elected not to use Git from the Windows Command Prompt).

Before you start using <strong>Git</strong>, you have to make it available on your computer. Even if it’s already installed, it’s probably a good idea to update to the latest version. You can either install it as a package or via another installer or <strong>download</strong> the source code and compile it yourself.

<strong>Git</strong> is responsible for everything <strong>GitHub-related</strong> that happens locally on your computer.

To use Git on the command line, you'll need to <strong>download</strong>, <strong>install</strong>, and <strong>configure Git</strong> on your computer.

If you want to work with Git locally, but don't want to use the command line, you can instead download and install the <strong>GitHub Desktop</strong> client.

<div class="article_inside_notes">
<svg viewbox="0 0 448 512">
<path d="M400 32H48C21.5 32 0 53.5 0 80v352c0 26.5 21.5 48 48 48h352c26.5 0 48-21.5 48-48V80c0-26.5-21.5-48-48-48zM277.3 415.7c-8.4 1.5-11.5-3.7-11.5-8 0-5.4.2-33 .2-55.3 0-15.6-5.2-25.5-11.3-30.7 37-4.1 76-9.2 76-73.1 0-18.2-6.5-27.3-17.1-39 1.7-4.3 7.4-22-1.7-45-13.9-4.3-45.7 17.9-45.7 17.9-13.2-3.7-27.5-5.6-41.6-5.6-14.1 0-28.4 1.9-41.6 5.6 0 0-31.8-22.2-45.7-17.9-9.1 22.9-3.5 40.6-1.7 45-10.6 11.7-15.6 20.8-15.6 39 0 63.6 37.3 69 74.3 73.1-4.8 4.3-9.1 11.7-10.6 22.3-9.5 4.3-33.8 11.7-48.3-13.9-9.1-15.8-25.5-17.1-25.5-17.1-16.2-.2-1.1 10.2-1.1 10.2 10.8 5 18.4 24.2 18.4 24.2 9.7 29.7 56.1 19.7 56.1 19.7 0 13.9.2 36.5.2 40.6 0 4.3-3 9.5-11.5 8-66-22.1-112.2-84.9-112.2-158.3 0-91.8 70.2-161.5 162-161.5S388 165.6 388 257.4c.1 73.4-44.7 136.3-110.7 158.3zm-98.1-61.1c-1.9.4-3.7-.4-3.9-1.7-.2-1.5 1.1-2.8 3-3.2 1.9-.2 3.7.6 3.9 1.9.3 1.3-1 2.6-3 3zm-9.5-.9c0 1.3-1.5 2.4-3.5 2.4-2.2.2-3.7-.9-3.7-2.4 0-1.3 1.5-2.4 3.5-2.4 1.9-.2 3.7.9 3.7 2.4zm-13.7-1.1c-.4 1.3-2.4 1.9-4.1 1.3-1.9-.4-3.2-1.9-2.8-3.2.4-1.3 2.4-1.9 4.1-1.5 2 .6 3.3 2.1 2.8 3.4zm-12.3-5.4c-.9 1.1-2.8.9-4.3-.6-1.5-1.3-1.9-3.2-.9-4.1.9-1.1 2.8-.9 4.3.6 1.3 1.3 1.8 3.3.9 4.1zm-9.1-9.1c-.9.6-2.6 0-3.7-1.5s-1.1-3.2 0-3.9c1.1-.9 2.8-.2 3.7 1.3 1.1 1.5 1.1 3.3 0 4.1zm-6.5-9.7c-.9.9-2.4.4-3.5-.6-1.1-1.3-1.3-2.8-.4-3.5.9-.9 2.4-.4 3.5.6 1.1 1.3 1.3 2.8.4 3.5zm-6.7-7.4c-.4.9-1.7 1.1-2.8.4-1.3-.6-1.9-1.7-1.5-2.6.4-.6 1.5-.9 2.8-.4 1.3.7 1.9 1.8 1.5 2.6z" /> </svg>
<p> Download &amp; install latest version of Git at official <a href="https://git-scm.com/downloads" target="_blank" rel="noopener">Git downloads</a> page. </p>
</div>

{% include googlead2.html %}

<h2 id="github-desktop"><strong>6. What is Github Desktop?</strong></h2>

<strong>GitHub Desktop</strong> is a fast and easy way to contribute to projects from Windows and OS X, whether you are a seasoned user or new user, <a href="https://desktop.github.com/" target="_blank" rel="noopener">GitHub Desktop</a> is designed to simplify the all process and workflow in your GitHub and replace GitHub for Mac and Windows with a unified experience across both platforms. GitHub Desktop is an open source Electron-based GitHub app written in TypeScript and uses React.

<div class="article-image">
<img src="#" data-src="../uploads/github-desktop.png" class="lazy" alt="github-desktop-image" title="Github-desktop-sample-image">
</div>	

<strong>GitHub Desktop</strong> will allow us to easily start using version control. GitHub Desktop offers a <strong>Graphical User Interface(GUI)</strong> to use <strong>Git</strong>. A GUI allows users to interact with a program using a visual interface rather than relying on text commands. Though there are some potential advantages to using the command line version of Git in the long run, using a GUI can reduce the learning curve of using version control and Git. 

<div class="article_inside_notes">
<svg viewbox="0 0 448 512">
<path d="M400 32H48C21.5 32 0 53.5 0 80v352c0 26.5 21.5 48 48 48h352c26.5 0 48-21.5 48-48V80c0-26.5-21.5-48-48-48zM277.3 415.7c-8.4 1.5-11.5-3.7-11.5-8 0-5.4.2-33 .2-55.3 0-15.6-5.2-25.5-11.3-30.7 37-4.1 76-9.2 76-73.1 0-18.2-6.5-27.3-17.1-39 1.7-4.3 7.4-22-1.7-45-13.9-4.3-45.7 17.9-45.7 17.9-13.2-3.7-27.5-5.6-41.6-5.6-14.1 0-28.4 1.9-41.6 5.6 0 0-31.8-22.2-45.7-17.9-9.1 22.9-3.5 40.6-1.7 45-10.6 11.7-15.6 20.8-15.6 39 0 63.6 37.3 69 74.3 73.1-4.8 4.3-9.1 11.7-10.6 22.3-9.5 4.3-33.8 11.7-48.3-13.9-9.1-15.8-25.5-17.1-25.5-17.1-16.2-.2-1.1 10.2-1.1 10.2 10.8 5 18.4 24.2 18.4 24.2 9.7 29.7 56.1 19.7 56.1 19.7 0 13.9.2 36.5.2 40.6 0 4.3-3 9.5-11.5 8-66-22.1-112.2-84.9-112.2-158.3 0-91.8 70.2-161.5 162-161.5S388 165.6 388 257.4c.1 73.4-44.7 136.3-110.7 158.3zm-98.1-61.1c-1.9.4-3.7-.4-3.9-1.7-.2-1.5 1.1-2.8 3-3.2 1.9-.2 3.7.6 3.9 1.9.3 1.3-1 2.6-3 3zm-9.5-.9c0 1.3-1.5 2.4-3.5 2.4-2.2.2-3.7-.9-3.7-2.4 0-1.3 1.5-2.4 3.5-2.4 1.9-.2 3.7.9 3.7 2.4zm-13.7-1.1c-.4 1.3-2.4 1.9-4.1 1.3-1.9-.4-3.2-1.9-2.8-3.2.4-1.3 2.4-1.9 4.1-1.5 2 .6 3.3 2.1 2.8 3.4zm-12.3-5.4c-.9 1.1-2.8.9-4.3-.6-1.5-1.3-1.9-3.2-.9-4.1.9-1.1 2.8-.9 4.3.6 1.3 1.3 1.8 3.3.9 4.1zm-9.1-9.1c-.9.6-2.6 0-3.7-1.5s-1.1-3.2 0-3.9c1.1-.9 2.8-.2 3.7 1.3 1.1 1.5 1.1 3.3 0 4.1zm-6.5-9.7c-.9.9-2.4.4-3.5-.6-1.1-1.3-1.3-2.8-.4-3.5.9-.9 2.4-.4 3.5.6 1.1 1.3 1.3 2.8.4 3.5zm-6.7-7.4c-.4.9-1.7 1.1-2.8.4-1.3-.6-1.9-1.7-1.5-2.6.4-.6 1.5-.9 2.8-.4 1.3.7 1.9 1.8 1.5 2.6z" /> </svg>
<p> Extend your GitHub workflow beyond your browser with GitHub Desktop. Get a unified cross-platform experience that’s completely open source and ready to customize.
<br> Download latest version of <a href="https://desktop.github.com/" target="_blank" rel="noopener">Github desktop</a> </p>
</div>

<h2 id="install-github-desktop"><strong>7. How to Install GitHub Desktop?</strong></h2>

You can <a href="https://help.github.com/en/desktop/getting-started-with-github-desktop/installing-github-desktop" target="_blank" rel="noopener">download GitHub Desktop</a> “<strong>Classic</strong>” for Windows or OS X here. Once you have downloaded the file, unzip it and open the app, following the instructions for logging in to your GitHub account. Once you have <strong>installed GitHub Desktop</strong> and followed the setup instructions we can start using the software with a text document.

<div class="article_inside_notes">
<svg viewbox="0 0 448 512">
<path d="M400 32H48C21.5 32 0 53.5 0 80v352c0 26.5 21.5 48 48 48h352c26.5 0 48-21.5 48-48V80c0-26.5-21.5-48-48-48zM277.3 415.7c-8.4 1.5-11.5-3.7-11.5-8 0-5.4.2-33 .2-55.3 0-15.6-5.2-25.5-11.3-30.7 37-4.1 76-9.2 76-73.1 0-18.2-6.5-27.3-17.1-39 1.7-4.3 7.4-22-1.7-45-13.9-4.3-45.7 17.9-45.7 17.9-13.2-3.7-27.5-5.6-41.6-5.6-14.1 0-28.4 1.9-41.6 5.6 0 0-31.8-22.2-45.7-17.9-9.1 22.9-3.5 40.6-1.7 45-10.6 11.7-15.6 20.8-15.6 39 0 63.6 37.3 69 74.3 73.1-4.8 4.3-9.1 11.7-10.6 22.3-9.5 4.3-33.8 11.7-48.3-13.9-9.1-15.8-25.5-17.1-25.5-17.1-16.2-.2-1.1 10.2-1.1 10.2 10.8 5 18.4 24.2 18.4 24.2 9.7 29.7 56.1 19.7 56.1 19.7 0 13.9.2 36.5.2 40.6 0 4.3-3 9.5-11.5 8-66-22.1-112.2-84.9-112.2-158.3 0-91.8 70.2-161.5 162-161.5S388 165.6 388 257.4c.1 73.4-44.7 136.3-110.7 158.3zm-98.1-61.1c-1.9.4-3.7-.4-3.9-1.7-.2-1.5 1.1-2.8 3-3.2 1.9-.2 3.7.6 3.9 1.9.3 1.3-1 2.6-3 3zm-9.5-.9c0 1.3-1.5 2.4-3.5 2.4-2.2.2-3.7-.9-3.7-2.4 0-1.3 1.5-2.4 3.5-2.4 1.9-.2 3.7.9 3.7 2.4zm-13.7-1.1c-.4 1.3-2.4 1.9-4.1 1.3-1.9-.4-3.2-1.9-2.8-3.2.4-1.3 2.4-1.9 4.1-1.5 2 .6 3.3 2.1 2.8 3.4zm-12.3-5.4c-.9 1.1-2.8.9-4.3-.6-1.5-1.3-1.9-3.2-.9-4.1.9-1.1 2.8-.9 4.3.6 1.3 1.3 1.8 3.3.9 4.1zm-9.1-9.1c-.9.6-2.6 0-3.7-1.5s-1.1-3.2 0-3.9c1.1-.9 2.8-.2 3.7 1.3 1.1 1.5 1.1 3.3 0 4.1zm-6.5-9.7c-.9.9-2.4.4-3.5-.6-1.1-1.3-1.3-2.8-.4-3.5.9-.9 2.4-.4 3.5.6 1.1 1.3 1.3 2.8.4 3.5zm-6.7-7.4c-.4.9-1.7 1.1-2.8.4-1.3-.6-1.9-1.7-1.5-2.6.4-.6 1.5-.9 2.8-.4 1.3.7 1.9 1.8 1.5 2.6z" /> </svg>
<p> Here is the complete installation guide to <a href="	https://help.github.com/en/desktop/getting-started-with-github-desktop/installing-github-desktop" target="_blank" rel="noopener">install Github Desktop.</a> </p>
</div>

{% include googlead3.html %}

<h2 id="git-commands"><strong>8. What are some basic Git Commands?</strong></h2>
	
To use <strong>Git</strong>, developers use specific commands to copy, create, change, and combine code. These commands can be executed directly from the command line or by using an application like <strong>GitHub Desktop</strong>.

<div class="article_inside_links">
				<ol> Here are some common commands for using Git:
					<br>
					<br>
					<li><strong style="background-color: #ff0; padding: 2px 5px;">git init</strong>: initializes a brand new Git repository and begins tracking an existing directory. It adds a hidden subfolder within the existing directory that houses the internal data structure required for version control.</li>
					<li><strong style="background-color: #ff0; padding: 2px 5px;">git clone</strong>: creates a local copy of a project that already exists remotely. The clone includes all the project’s files, history, and branches.</li>
					<li><strong style="background-color: #ff0; padding: 2px 5px;">git add</strong>: stages a change. Git tracks changes to a developer’s codebase, but it’s necessary to stage and take a snapshot of the changes to include them in the project’s history. This command performs staging, the first part of that two-step process. Any changes that are staged will become a part of the next snapshot and a part of the project’s history. Staging and committing separately gives developers complete control over the history of their project without changing how they code and work.</li>
					<li><strong style="background-color: #ff0; padding: 2px 5px;">git commit</strong>: saves the snapshot to the project history and completes the change-tracking process. In short, a commit functions like taking a photo. Anything that’s been staged with git add will become a part of the snapshot with git commit.</li>
					<li><strong style="background-color: rgba(255, 255, 0, 0.46); padding: 2px 5px;">git status</strong>: shows the status of changes as untracked, modified, or staged.</li>
					<li><strong style="background-color: #ff0; padding: 2px 5px;">git branch</strong>: shows the branches being worked on locally.</li>
					<li><strong style="background-color: #ff0; padding: 2px 5px;">git merge</strong>: merges lines of development together. This command is typically used to combine changes made on two distinct branches. For example, a developer would merge when they want to combine changes from a feature branch into the master branch for deployment.</li>
					<li><strong style="background-color: #ff0; padding: 2px 5px;">git pull</strong>: updates the local line of development with updates from its remote counterpart. Developers use this command if a teammate has made commits to a branch on a remote, and they would like to reflect those changes in their local environment.</li>
					<li><strong style="background-color: #ff0; padding: 2px 5px;">git push</strong>: updates the remote repository with any commits made locally to a branch.</li>
				</ol>
</div>

<div class="article_inside_notes">
<svg viewbox="0 0 448 512">
<path d="M400 32H48C21.5 32 0 53.5 0 80v352c0 26.5 21.5 48 48 48h352c26.5 0 48-21.5 48-48V80c0-26.5-21.5-48-48-48zM277.3 415.7c-8.4 1.5-11.5-3.7-11.5-8 0-5.4.2-33 .2-55.3 0-15.6-5.2-25.5-11.3-30.7 37-4.1 76-9.2 76-73.1 0-18.2-6.5-27.3-17.1-39 1.7-4.3 7.4-22-1.7-45-13.9-4.3-45.7 17.9-45.7 17.9-13.2-3.7-27.5-5.6-41.6-5.6-14.1 0-28.4 1.9-41.6 5.6 0 0-31.8-22.2-45.7-17.9-9.1 22.9-3.5 40.6-1.7 45-10.6 11.7-15.6 20.8-15.6 39 0 63.6 37.3 69 74.3 73.1-4.8 4.3-9.1 11.7-10.6 22.3-9.5 4.3-33.8 11.7-48.3-13.9-9.1-15.8-25.5-17.1-25.5-17.1-16.2-.2-1.1 10.2-1.1 10.2 10.8 5 18.4 24.2 18.4 24.2 9.7 29.7 56.1 19.7 56.1 19.7 0 13.9.2 36.5.2 40.6 0 4.3-3 9.5-11.5 8-66-22.1-112.2-84.9-112.2-158.3 0-91.8 70.2-161.5 162-161.5S388 165.6 388 257.4c.1 73.4-44.7 136.3-110.7 158.3zm-98.1-61.1c-1.9.4-3.7-.4-3.9-1.7-.2-1.5 1.1-2.8 3-3.2 1.9-.2 3.7.6 3.9 1.9.3 1.3-1 2.6-3 3zm-9.5-.9c0 1.3-1.5 2.4-3.5 2.4-2.2.2-3.7-.9-3.7-2.4 0-1.3 1.5-2.4 3.5-2.4 1.9-.2 3.7.9 3.7 2.4zm-13.7-1.1c-.4 1.3-2.4 1.9-4.1 1.3-1.9-.4-3.2-1.9-2.8-3.2.4-1.3 2.4-1.9 4.1-1.5 2 .6 3.3 2.1 2.8 3.4zm-12.3-5.4c-.9 1.1-2.8.9-4.3-.6-1.5-1.3-1.9-3.2-.9-4.1.9-1.1 2.8-.9 4.3.6 1.3 1.3 1.8 3.3.9 4.1zm-9.1-9.1c-.9.6-2.6 0-3.7-1.5s-1.1-3.2 0-3.9c1.1-.9 2.8-.2 3.7 1.3 1.1 1.5 1.1 3.3 0 4.1zm-6.5-9.7c-.9.9-2.4.4-3.5-.6-1.1-1.3-1.3-2.8-.4-3.5.9-.9 2.4-.4 3.5.6 1.1 1.3 1.3 2.8.4 3.5zm-6.7-7.4c-.4.9-1.7 1.1-2.8.4-1.3-.6-1.9-1.7-1.5-2.6.4-.6 1.5-.9 2.8-.4 1.3.7 1.9 1.8 1.5 2.6z" /> </svg>
<p> Here is the complete list of <a href="https://github.com/joshnh/Git-Commands" target="_blank" rel="noopener">Github commands.</a> </p>
</div>

<h2 id="create-repo-in-github"><strong>9. What is a repository in Github?</strong></h2>

A <strong>repository</strong> is like a folder for your project. Your project's repository contains all of your project's files and stores each file's revision history. You can also discuss and manage your project's work within the repository. You can own repositories individually, or you can share ownership of repositories with other people in an organization.</p>

<div class="article_inside_links">
				<ol>
					<h3 style="padding: 0px; margin: 0px 0px 9px 0px;"><strong>Create a new repository in Github.</strong></h3>
					<li>Go to Github.</li>
					<li>Log in to your account.</li>
					<li>Click the new repository button in the top-right. You’ll have an option there to initialize the repository with a README file, but I don’t.</li>
					<li>Click the "Create repository" button.</li>
				</ol>
</div> 

<div class="article-image">
<img src="#" data-src="../uploads/create-new-repository.png" class="lazy" alt="create-new-github-repository" title="create-new-github-repository">
</div>	

<h2 id="host-website-using-github-pages"><strong>10. Can I host a website using Github pages?</strong></h2>

Yes, we can host our <strong>personal website</strong> on Github as Github pages for free of cost. We use a static site generator called Jekyll to serve as a CMS for the publishers and the GitHub. Importantly, we can use our own <a href="https://www.alltechnotricks.com/Blog/github-pages-custom-domain.html" target="_blank" rel="noopener">custom domain</a> to get hosted on the Github.

<div class="article_inside_notes">
<svg viewbox="0 0 448 512">
<path d="M400 32H48C21.5 32 0 53.5 0 80v352c0 26.5 21.5 48 48 48h352c26.5 0 48-21.5 48-48V80c0-26.5-21.5-48-48-48zM277.3 415.7c-8.4 1.5-11.5-3.7-11.5-8 0-5.4.2-33 .2-55.3 0-15.6-5.2-25.5-11.3-30.7 37-4.1 76-9.2 76-73.1 0-18.2-6.5-27.3-17.1-39 1.7-4.3 7.4-22-1.7-45-13.9-4.3-45.7 17.9-45.7 17.9-13.2-3.7-27.5-5.6-41.6-5.6-14.1 0-28.4 1.9-41.6 5.6 0 0-31.8-22.2-45.7-17.9-9.1 22.9-3.5 40.6-1.7 45-10.6 11.7-15.6 20.8-15.6 39 0 63.6 37.3 69 74.3 73.1-4.8 4.3-9.1 11.7-10.6 22.3-9.5 4.3-33.8 11.7-48.3-13.9-9.1-15.8-25.5-17.1-25.5-17.1-16.2-.2-1.1 10.2-1.1 10.2 10.8 5 18.4 24.2 18.4 24.2 9.7 29.7 56.1 19.7 56.1 19.7 0 13.9.2 36.5.2 40.6 0 4.3-3 9.5-11.5 8-66-22.1-112.2-84.9-112.2-158.3 0-91.8 70.2-161.5 162-161.5S388 165.6 388 257.4c.1 73.4-44.7 136.3-110.7 158.3zm-98.1-61.1c-1.9.4-3.7-.4-3.9-1.7-.2-1.5 1.1-2.8 3-3.2 1.9-.2 3.7.6 3.9 1.9.3 1.3-1 2.6-3 3zm-9.5-.9c0 1.3-1.5 2.4-3.5 2.4-2.2.2-3.7-.9-3.7-2.4 0-1.3 1.5-2.4 3.5-2.4 1.9-.2 3.7.9 3.7 2.4zm-13.7-1.1c-.4 1.3-2.4 1.9-4.1 1.3-1.9-.4-3.2-1.9-2.8-3.2.4-1.3 2.4-1.9 4.1-1.5 2 .6 3.3 2.1 2.8 3.4zm-12.3-5.4c-.9 1.1-2.8.9-4.3-.6-1.5-1.3-1.9-3.2-.9-4.1.9-1.1 2.8-.9 4.3.6 1.3 1.3 1.8 3.3.9 4.1zm-9.1-9.1c-.9.6-2.6 0-3.7-1.5s-1.1-3.2 0-3.9c1.1-.9 2.8-.2 3.7 1.3 1.1 1.5 1.1 3.3 0 4.1zm-6.5-9.7c-.9.9-2.4.4-3.5-.6-1.1-1.3-1.3-2.8-.4-3.5.9-.9 2.4-.4 3.5.6 1.1 1.3 1.3 2.8.4 3.5zm-6.7-7.4c-.4.9-1.7 1.1-2.8.4-1.3-.6-1.9-1.7-1.5-2.6.4-.6 1.5-.9 2.8-.4 1.3.7 1.9 1.8 1.5 2.6z" /> </svg>
<p> Here is the complete guide to <a href="https://www.alltechnotricks.com/Blog/github-pages-custom-domain.html" target="_blank" rel="noopener">host a website using Github pages.</a> </p>
</div>

{% include googlead4.html %}

<h2 id="jekyll"><strong>11. What is Jekyll?</strong></h2>

<strong>Jekyll</strong> is a s<strong>tatic site generator</strong>, which in reduced terms means that it will let you develop a website with some dynamic-like functionalities like automatic navigation menus, cross-links and so on; but the end result is actually just generated as static files (files that only need to be served, not computed). <a href="https://jekyllrb.com/" target="_blank" rel="noopener">Jekyll</a> Static files only need to be hosted on a web server (which makes it cheap) and are easily deployable. You give it text written in your favorite markup language and it churns through layouts to create a static website. Throughout that process, you can tweak how you want the site URLs to look, what data gets displayed in the layout, and many more.

<div class="article-image">
<img src="#" data-src="../uploads/github-pages-jekyll-homepage.png" class="lazy" alt="github-pages-jekyll-homepage" title="Jekyll-homepage-github-pages">
</div>	

Most, importantly, we can blog with <strong>Jekyll</strong>, as you were reading this article, my blog(<a href="https://www.alltechnotricks.com" target="_blank" rel="noopener">Karunakar Patel blog</a>) is hosted on Github served as Github pages for free by using <strong>Jekyll.</strong>

<div class="article_inside_notes">
<svg viewbox="0 0 448 512">
<path d="M400 32H48C21.5 32 0 53.5 0 80v352c0 26.5 21.5 48 48 48h352c26.5 0 48-21.5 48-48V80c0-26.5-21.5-48-48-48zM277.3 415.7c-8.4 1.5-11.5-3.7-11.5-8 0-5.4.2-33 .2-55.3 0-15.6-5.2-25.5-11.3-30.7 37-4.1 76-9.2 76-73.1 0-18.2-6.5-27.3-17.1-39 1.7-4.3 7.4-22-1.7-45-13.9-4.3-45.7 17.9-45.7 17.9-13.2-3.7-27.5-5.6-41.6-5.6-14.1 0-28.4 1.9-41.6 5.6 0 0-31.8-22.2-45.7-17.9-9.1 22.9-3.5 40.6-1.7 45-10.6 11.7-15.6 20.8-15.6 39 0 63.6 37.3 69 74.3 73.1-4.8 4.3-9.1 11.7-10.6 22.3-9.5 4.3-33.8 11.7-48.3-13.9-9.1-15.8-25.5-17.1-25.5-17.1-16.2-.2-1.1 10.2-1.1 10.2 10.8 5 18.4 24.2 18.4 24.2 9.7 29.7 56.1 19.7 56.1 19.7 0 13.9.2 36.5.2 40.6 0 4.3-3 9.5-11.5 8-66-22.1-112.2-84.9-112.2-158.3 0-91.8 70.2-161.5 162-161.5S388 165.6 388 257.4c.1 73.4-44.7 136.3-110.7 158.3zm-98.1-61.1c-1.9.4-3.7-.4-3.9-1.7-.2-1.5 1.1-2.8 3-3.2 1.9-.2 3.7.6 3.9 1.9.3 1.3-1 2.6-3 3zm-9.5-.9c0 1.3-1.5 2.4-3.5 2.4-2.2.2-3.7-.9-3.7-2.4 0-1.3 1.5-2.4 3.5-2.4 1.9-.2 3.7.9 3.7 2.4zm-13.7-1.1c-.4 1.3-2.4 1.9-4.1 1.3-1.9-.4-3.2-1.9-2.8-3.2.4-1.3 2.4-1.9 4.1-1.5 2 .6 3.3 2.1 2.8 3.4zm-12.3-5.4c-.9 1.1-2.8.9-4.3-.6-1.5-1.3-1.9-3.2-.9-4.1.9-1.1 2.8-.9 4.3.6 1.3 1.3 1.8 3.3.9 4.1zm-9.1-9.1c-.9.6-2.6 0-3.7-1.5s-1.1-3.2 0-3.9c1.1-.9 2.8-.2 3.7 1.3 1.1 1.5 1.1 3.3 0 4.1zm-6.5-9.7c-.9.9-2.4.4-3.5-.6-1.1-1.3-1.3-2.8-.4-3.5.9-.9 2.4-.4 3.5.6 1.1 1.3 1.3 2.8.4 3.5zm-6.7-7.4c-.4.9-1.7 1.1-2.8.4-1.3-.6-1.9-1.7-1.5-2.6.4-.6 1.5-.9 2.8-.4 1.3.7 1.9 1.8 1.5 2.6z" /> </svg>
<p>GitHub Pages are powered by Jekyll, so you can easily deploy your site using GitHub for free—custom domain name and all.
<br> Let's get started at <a href="https://jekyllrb.com/" target="_blank" rel="noopener">Jekyll(static site generator) → </a></p>
</div>

{% include googlead5.html %}

<h2 id="custom-domain-to-github-pages"><strong>12. How to add a custom domain name to Github Pages?</strong></h2>

Go to your GitHub Pages site's repository settings. Under "<strong>Custom domain</strong>", add or remove your custom domain and click “<strong>Save</strong>”. Setting “<strong>custom domain</strong>” creates a file named <strong>CNAME</strong> in the same repository. That's it we add a custom domain name to Github.

<div class="article_inside_notes">
<svg viewbox="0 0 448 512">
<path d="M400 32H48C21.5 32 0 53.5 0 80v352c0 26.5 21.5 48 48 48h352c26.5 0 48-21.5 48-48V80c0-26.5-21.5-48-48-48zM277.3 415.7c-8.4 1.5-11.5-3.7-11.5-8 0-5.4.2-33 .2-55.3 0-15.6-5.2-25.5-11.3-30.7 37-4.1 76-9.2 76-73.1 0-18.2-6.5-27.3-17.1-39 1.7-4.3 7.4-22-1.7-45-13.9-4.3-45.7 17.9-45.7 17.9-13.2-3.7-27.5-5.6-41.6-5.6-14.1 0-28.4 1.9-41.6 5.6 0 0-31.8-22.2-45.7-17.9-9.1 22.9-3.5 40.6-1.7 45-10.6 11.7-15.6 20.8-15.6 39 0 63.6 37.3 69 74.3 73.1-4.8 4.3-9.1 11.7-10.6 22.3-9.5 4.3-33.8 11.7-48.3-13.9-9.1-15.8-25.5-17.1-25.5-17.1-16.2-.2-1.1 10.2-1.1 10.2 10.8 5 18.4 24.2 18.4 24.2 9.7 29.7 56.1 19.7 56.1 19.7 0 13.9.2 36.5.2 40.6 0 4.3-3 9.5-11.5 8-66-22.1-112.2-84.9-112.2-158.3 0-91.8 70.2-161.5 162-161.5S388 165.6 388 257.4c.1 73.4-44.7 136.3-110.7 158.3zm-98.1-61.1c-1.9.4-3.7-.4-3.9-1.7-.2-1.5 1.1-2.8 3-3.2 1.9-.2 3.7.6 3.9 1.9.3 1.3-1 2.6-3 3zm-9.5-.9c0 1.3-1.5 2.4-3.5 2.4-2.2.2-3.7-.9-3.7-2.4 0-1.3 1.5-2.4 3.5-2.4 1.9-.2 3.7.9 3.7 2.4zm-13.7-1.1c-.4 1.3-2.4 1.9-4.1 1.3-1.9-.4-3.2-1.9-2.8-3.2.4-1.3 2.4-1.9 4.1-1.5 2 .6 3.3 2.1 2.8 3.4zm-12.3-5.4c-.9 1.1-2.8.9-4.3-.6-1.5-1.3-1.9-3.2-.9-4.1.9-1.1 2.8-.9 4.3.6 1.3 1.3 1.8 3.3.9 4.1zm-9.1-9.1c-.9.6-2.6 0-3.7-1.5s-1.1-3.2 0-3.9c1.1-.9 2.8-.2 3.7 1.3 1.1 1.5 1.1 3.3 0 4.1zm-6.5-9.7c-.9.9-2.4.4-3.5-.6-1.1-1.3-1.3-2.8-.4-3.5.9-.9 2.4-.4 3.5.6 1.1 1.3 1.3 2.8.4 3.5zm-6.7-7.4c-.4.9-1.7 1.1-2.8.4-1.3-.6-1.9-1.7-1.5-2.6.4-.6 1.5-.9 2.8-.4 1.3.7 1.9 1.8 1.5 2.6z" /> </svg>
<p>Learn more about adding a <a href="https://www.alltechnotricks.com/Blog/github-pages-custom-domain.html" target="_blank" rel="noopener">custom domain name to Github pages</a> →</p>
</div>

<h2 id="github-pages-with-HTTPS"><strong>13. How to secure the Github Pages site with HTTPS?</strong></h2>

<strong>HTTPS</strong> adds a layer of encryption that prevents others from snooping on or tampering with traffic to your site. You can enforce HTTPS for your <strong>GitHub Pages site</strong> to transparently redirect all HTTP requests to HTTPS.

<div class="article_inside_links">
<ol> Here is how to add HTTPS to Github Pages.
					<br>
					<br>
					<li>On GitHub, navigate to the main page of the repository.</li>
					<li>Under your repository name, click Settings.</li>
					<li>Under "GitHub Pages," select Enforce HTTPS.</li>
				</ol>
</div>

<div class="article_inside_notes">
<svg viewbox="0 0 448 512">
<path d="M400 32H48C21.5 32 0 53.5 0 80v352c0 26.5 21.5 48 48 48h352c26.5 0 48-21.5 48-48V80c0-26.5-21.5-48-48-48zM277.3 415.7c-8.4 1.5-11.5-3.7-11.5-8 0-5.4.2-33 .2-55.3 0-15.6-5.2-25.5-11.3-30.7 37-4.1 76-9.2 76-73.1 0-18.2-6.5-27.3-17.1-39 1.7-4.3 7.4-22-1.7-45-13.9-4.3-45.7 17.9-45.7 17.9-13.2-3.7-27.5-5.6-41.6-5.6-14.1 0-28.4 1.9-41.6 5.6 0 0-31.8-22.2-45.7-17.9-9.1 22.9-3.5 40.6-1.7 45-10.6 11.7-15.6 20.8-15.6 39 0 63.6 37.3 69 74.3 73.1-4.8 4.3-9.1 11.7-10.6 22.3-9.5 4.3-33.8 11.7-48.3-13.9-9.1-15.8-25.5-17.1-25.5-17.1-16.2-.2-1.1 10.2-1.1 10.2 10.8 5 18.4 24.2 18.4 24.2 9.7 29.7 56.1 19.7 56.1 19.7 0 13.9.2 36.5.2 40.6 0 4.3-3 9.5-11.5 8-66-22.1-112.2-84.9-112.2-158.3 0-91.8 70.2-161.5 162-161.5S388 165.6 388 257.4c.1 73.4-44.7 136.3-110.7 158.3zm-98.1-61.1c-1.9.4-3.7-.4-3.9-1.7-.2-1.5 1.1-2.8 3-3.2 1.9-.2 3.7.6 3.9 1.9.3 1.3-1 2.6-3 3zm-9.5-.9c0 1.3-1.5 2.4-3.5 2.4-2.2.2-3.7-.9-3.7-2.4 0-1.3 1.5-2.4 3.5-2.4 1.9-.2 3.7.9 3.7 2.4zm-13.7-1.1c-.4 1.3-2.4 1.9-4.1 1.3-1.9-.4-3.2-1.9-2.8-3.2.4-1.3 2.4-1.9 4.1-1.5 2 .6 3.3 2.1 2.8 3.4zm-12.3-5.4c-.9 1.1-2.8.9-4.3-.6-1.5-1.3-1.9-3.2-.9-4.1.9-1.1 2.8-.9 4.3.6 1.3 1.3 1.8 3.3.9 4.1zm-9.1-9.1c-.9.6-2.6 0-3.7-1.5s-1.1-3.2 0-3.9c1.1-.9 2.8-.2 3.7 1.3 1.1 1.5 1.1 3.3 0 4.1zm-6.5-9.7c-.9.9-2.4.4-3.5-.6-1.1-1.3-1.3-2.8-.4-3.5.9-.9 2.4-.4 3.5.6 1.1 1.3 1.3 2.8.4 3.5zm-6.7-7.4c-.4.9-1.7 1.1-2.8.4-1.3-.6-1.9-1.7-1.5-2.6.4-.6 1.5-.9 2.8-.4 1.3.7 1.9 1.8 1.5 2.6z" /> </svg>
<p>Learn more at <a href="https://www.alltechnotricks.com/Blog/add-HTTPS-Github-Pages-custom-domain.html" target="_blank" rel="noopener">adding HTTPS to Github pages.</a>→
<br> The same technique I used to add HTTPS to my <a href="https://www.alltechnotricks.com" target="_blank" rel="noopener">Karunakar Patel Blog</a>. </p>
</div>

{% include googlead4.html %}

<h2 id="usage-limits-of-github-pages"><strong>14. What are the usage limits of GitHub Pages?</strong></h2>

<div class="article_inside_links">
<ol> GitHub Pages sites are subject to the following usage limits:
					<br>
					<br>
					<li>GitHub Page's source repositories have a recommended limit of 1GB.</li>
					<li>Published GitHub Pages sites may be no larger than 1 GB.</li>
					<li>GitHub Pages sites have a soft bandwidth limit of 100GB per month.</li>
					<li>GitHub Pages sites have a soft limit of 10 builds per hour.</li>
				</ol>
</div>

If your site exceeds these usage quotas, we may not be able to serve your site, or you may receive a polite email from <strong>GitHub</strong> Support or <strong>GitHub Premium</strong> Support suggesting strategies for reducing your site's impact on our servers, including putting a third-party <strong>content distribution network(CDN)</strong> in front of your site, making use of other GitHub features, such as releases, or moving to a different hosting service that might better fit your needs.

<strong>GitHub Pages</strong> is not intended for or allowed to be used as a free web hosting service to run your online business, e-commerce site, or any other website that is primarily directed at either facilitating commercial transactions or providing commercial software as a service (SaaS).

{% include googlead4.html %}

---

<div class="anim_container">
<button id="show">
			<svg style="width: 35px; height: 35px; animation: wrench 2s linear infinite; " fill="#06f" viewbox="0 0 320 512">
				<path d="M313.553 119.669L209.587 7.666c-9.485-10.214-25.676-10.229-35.174 0L70.438 119.669C56.232 134.969 67.062 160 88.025 160H152v272H68.024a11.996 11.996 0 0 0-8.485 3.515l-56 56C-4.021 499.074 1.333 512 12.024 512H208c13.255 0 24-10.745 24-24V160h63.966c20.878 0 31.851-24.969 17.587-40.331z" /> </svg>
		</button>
<div id="links_container">
			<ol>
				<li> <a href="#github" class="test">What is Github?</a></li>
				<li><a href="#git" class="test">What is Git?</a></li>
				<li><a href="#version-control-system" class="test">What is version control system?</a></li>
				<li><a href="#github-pages" class="test">What is GitHub Pages?</a></li>
				<li><a href="#install-git-in-pc" class="test">How to install Git in pc?</a></li>
				<li><a href="#github-desktop" class="test">What is Github Desktop?</a></li>
				<li><a href="#install-github-desktop" class="test">How to install Github Desktop?</a></li>
				<li><a href="#git-commands" class="test">What are some basic Git Commands?</a></li>
				<li><a href="#create-repo-in-github" class="test">How to create a repository in Github?</a></li>
				<li><a href="#host-website-using-github-pages" class="test">Can I host a website using Github Pages?</a></li>
				<li><a href="#jekyll" class="test">What is Jekyll?</a></li>
				<li><a href="#custom-domain-to-github-pages" class="test">Adding a custom domain to Github Pages?</a></li>
				<li><a href="#github-pages-with-HTTPS" class="test">How to secure the Github Pages site with HTTPS?</a></li>
				<li><a href="#usage-limits-of-github-pages" class="test">What are the usage limits of Github Pages?</a></li>
				<li><a href="#disqus_thread" class="test">Throw a Comment.</a></li>
			</ol>
			<ol>
				<li><a href="https://www.alltechnotricks.com" target="_blank" class="test">Home</a></li>
				<li><a href="https://www.alltechnotricks.com/Blog.html" target="_blank" class="test">Blog</a></li>
				<li><a href="#top" class="test">To Top</a></li>
			</ol>
		</div>
</div>

			
