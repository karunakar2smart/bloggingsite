---
title: Github for beginners- right from the command line to hosting a website(2020).
permalink: Blog/github_beginners_guide.html
layout: post
image: upload/github-guide-for-beginners.png
description: "In this Github for beginners post, you will get introduced to Github & its various commands. It talks about Github pages, repo, installs Git, Git commands & desktop, hosting with Jekyll, etc for complete newbies."
datepublished: "2019-06-20"
datemodified: "2021-03-05"
margin-top: -555px
category: [Github-Pages, Blog]
---

Do you ever ask yourself, <b>"What is GitHub?"</b> or wish you had an opportunity to learn the basics of Git? If you’ve always wanted to use GitHub, but haven’t quite been able to get up to speed. In this "Github for beginners" post, you will get introduced to Github &amp; its various commands. It talks about Github pages, repo, installs Git, Git commands &amp; desktop, hosting with Jekyll, etc for complete newbies. This beginner-friendly article is for you.

<h2 id="github"><strong>1. What is Github?</strong></h2>

Github is a web-based hosting service for version control using <strong>Git</strong>. Github is a place where developers store their open source software projects and networks with like-minded people and work together without any conflicts. Github provides access control and several collaboration features like creating repositories, pull requests, merge, commits, branches, etc for each and every project to make developer life better.

<blockquote>GitHub is a code hosting platform for collaboration and version control. GitHub lets you (and others) work together on projects.
<br> <strong>Github</strong> = <strong>Git</strong>(<strong>Version Control System</strong>) &amp; <strong>Hub</strong>(<strong>Code hosting platform</strong>).</blockquote>

<h2 id="git"><strong>2. What is Git?</strong></h2>

Git is an Open Source <strong>DISTRIBUTED VERSION CONTROL SYSTEM</strong>. It is mainly used for source code management in software development. It is a Command Line Interface(CLI) tool and can be mastered easily.

<h2 id="version-control-system"><strong>3. What is Version Control System?</strong></h2>

Version control systems are a category of software tools that help a software team manage changes to source code over time. Version control software keeps track of <strong>every modification</strong> to the code in a special kind of database. If a mistake is made, developers can turn back the clock and compare earlier versions of the code to help fix the mistake while minimizing disruption to all team members.

VCS treats each file/change as a revision and coordinates work on those change among multiple people providing information like who edited or created it, when, what changes were made, etc. It also provides the ability to revert a file/change to a previous revision for allowing editors to track each other's edits, correct mistakes, and defend against vandalism and spamming. VCS can be distributed or centralized, but distributed has more advantages.

This development doesn’t depend on a single entity as VCS tends to be distributed. Each entity is treated with equal importance as others.

Developers can review project history to find out:

<ul>
<li>Which changes were made?</li>
<li>Who made the changes?</li>
<li>When were the changes made?</li>
<li>Why were the changes needed?</li>
</ul>

{% include googlead1.html %}

<h2 id="github-pages"><strong>4. What is GitHub Pages?</strong></h2>

<strong>GitHub Pages</strong> is a static site hosting service designed to host your personal, organization, or project pages directly from a GitHub repository. You can create and publish GitHub Pages sites online using the Jekyll Static site generator Or if you prefer to work locally, you can use <strong>GitHub Desktop</strong> or the command line. GitHub Pages doesn't support server-side code such as PHP, Ruby, or Python.

<blockquote>Ready to get started? <br> Build your own site from scratch or generate one for your project. <br>You get one site per GitHub account and organization, and unlimited project sites.
<br> Let's get started at <a href="https://pages.github.com/" rel="noopener" target="_blank">Github pages.</a></blockquote>

<h2 id="install-git-in-pc"><strong>5. How to install Git in pc?</strong></h2>

Install Git on Windows. <strong>Download</strong> the [latest Git for Windows installer](https://git-scm.com/downloads){: target="\_blank" rel="noopener"}. When you've successfully started the installer, you should see the Git Setup wizard screen. Open a Command Prompt (or Git Bash if during installation you elected not to use Git from the Windows Command Prompt).

Before you start using <strong>Git</strong>, you have to make it available on your computer. Even if it’s already installed, it’s probably a good idea to update to the latest version. You can either install it as a package or via another installer or <strong>download</strong> the source code and compile it yourself.

<strong>Git</strong> is responsible for everything <strong>GitHub-related</strong> that happens locally on your computer.

To use Git on the command line, you'll need to <strong>download</strong>, <strong>install</strong>, and <strong>configure Git</strong> on your computer.

If you want to work with Git locally, but don't want to use the command line, you can instead download and install the <strong>GitHub Desktop</strong> client.

<blockquote> Download &amp; install latest version of Git at official <a href="https://git-scm.com/downloads" target="_blank" rel="noopener">Git downloads</a> page. </blockquote>

{% include googlead2.html %}

<h2 id="github-desktop"><strong>6. What is Github Desktop?</strong></h2>

<strong>GitHub Desktop</strong> is a fast and easy way to contribute to projects from Windows and OS X, whether you are a seasoned user or new user, <a href="https://desktop.github.com/" target="_blank" rel="noopener">GitHub Desktop</a> is designed to simplify the all process and workflow in your GitHub and replace GitHub for Mac and Windows with a unified experience across both platforms. GitHub Desktop is an open source Electron-based GitHub app written in TypeScript and uses React.

<figure><img src="/uploads/github-desktop.png" data-src="/uploads/github-desktop.png" alt="Github-desktop" title="Github-desktop" class="lazy" />
<figcaption>Github Desktop Image.
</figcaption>
</figure>

<strong>GitHub Desktop</strong> will allow us to easily start using version control. GitHub Desktop offers a <strong>Graphical User Interface(GUI)</strong> to use <strong>Git</strong>. A GUI allows users to interact with a program using a visual interface rather than relying on text commands. Though there are some potential advantages to using the command line version of Git in the long run, using a GUI can reduce the learning curve of using version control and Git.

<blockquote> Extend your GitHub workflow beyond your browser with GitHub Desktop. <br> Get a unified cross-platform experience that’s completely open source and ready to customize.
<br> Download latest version of <a href="https://desktop.github.com/" target="_blank" rel="noopener">Github desktop</a> </blockquote>

<h2 id="install-github-desktop"><strong>7. How to Install GitHub Desktop?</strong></h2>

You can <a href="https://help.github.com/en/desktop/getting-started-with-github-desktop/installing-github-desktop" target="_blank" rel="noopener">download GitHub Desktop</a> “<strong>Classic</strong>” for Windows or OS X here. Once you have downloaded the file, unzip it and open the app, following the instructions for logging in to your GitHub account. Once you have <strong>installed GitHub Desktop</strong> and followed the setup instructions we can start using the software with a text document.

<blockquote> Here is the complete installation guide to <a href="	https://help.github.com/en/desktop/getting-started-with-github-desktop/installing-github-desktop" target="_blank" rel="noopener">install Github Desktop.</a> </blockquote>

{% include googlead3.html %}

<h2 id="git-commands"><strong>8. What are some basic Git Commands?</strong></h2>

To use <strong>Git</strong>, developers use specific commands to copy, create, change, and combine code. These commands can be executed directly from the command line or by using an application like <strong>GitHub Desktop</strong>.

Here are some common commands for using Git:

<ul>
<li><strong style="background-color: #ff0; padding: 2px 5px;">git init</strong>: initializes a brand new Git repository and begins tracking an existing directory. It adds a hidden subfolder within the existing directory that houses the internal data structure required for version control.</li>
<li><strong style="background-color: #ff0; padding: 2px 5px;">git clone</strong>: creates a local copy of a project that already exists remotely. The clone includes all the project’s files, history, and branches.</li>
<li><strong style="background-color: #ff0; padding: 2px 5px;">git add</strong>: stages a change. Git tracks changes to a developer’s codebase, but it’s necessary to stage and take a snapshot of the changes to include them in the project’s history. This command performs staging, the first part of that two-step process. Any changes that are staged will become a part of the next snapshot and a part of the project’s history. Staging and committing separately gives developers complete control over the history of their project without changing how they code and work.</li>
<li><strong style="background-color: #ff0; padding: 2px 5px;">git commit</strong>: saves the snapshot to the project history and completes the change-tracking process. In short, a commit functions like taking a photo. Anything that’s been staged with git add will become a part of the snapshot with git commit.</li>
<li><strong style="background-color: rgba(255, 255, 0, 0.46); padding: 2px 5px;">git status</strong>: shows the status of changes as untracked, modified, or staged.</li>
<li><strong style="background-color: #ff0; padding: 2px 5px;">git branch</strong>: shows the branches being worked on locally.</li>
<li><strong style="background-color: #ff0; padding: 2px 5px;">git merge</strong>: merges lines of development together. This command is typically used to combine changes made on two distinct branches. For example, a developer would merge when they want to combine changes from a feature branch into the master branch for deployment.</li>
<li><strong style="background-color: #ff0; padding: 2px 5px;">git pull</strong>: updates the local line of development with updates from its remote counterpart. Developers use this command if a teammate has made commits to a branch on a remote, and they would like to reflect those changes in their local environment.</li>
<li><strong style="background-color: #ff0; padding: 2px 5px;">git push</strong>: updates the remote repository with any commits made locally to a branch.</li>
</ul>

<blockquote> Here is the complete list of <a href="https://github.com/joshnh/Git-Commands" target="_blank" rel="noopener">Github commands.</a> </blockquote>

<h2 id="create-repo-in-github"><strong>9. What is a repository in Github?</strong></h2>

A <strong>repository</strong> is like a folder for your project. Your project's repository contains all of your project's files and stores each file's revision history. You can also discuss and manage your project's work within the repository. You can own repositories individually, or you can share ownership of repositories with other people in an organization.</p>

<h3><strong>Create a new repository in Github.</strong></h3>
<ol>
<li>Go to Github.</li>
<li>Log in to your account.</li>
<li>Click the new repository button in the top-right. You’ll have an option there to initialize the repository with a README file, but I don’t.</li>
<li>Click the "Create repository" button.</li>
</ol>

<figure><img src="/uploads/create-new-repository.png" data-src="/uploads/create-new-repository.png" alt="create-new-github-repository" title="create-new-github-repository" class="lazy" />
<figcaption>Create New Github Repository.
</figcaption>
</figure>

<h2 id="host-website-using-github-pages"><strong>10. Can I host a website using Github pages?</strong></h2>

Yes, we can host our <strong>personal website</strong> on Github as Github pages for free of cost. We use a static site generator called Jekyll to serve as a CMS for the publishers and the GitHub. Importantly, we can use our own <a href="https://www.alltechnotricks.com/Blog/github-pages-custom-domain.html" target="_blank" rel="noopener">custom domain</a> to get hosted on the Github.

<blockquote> Here is the complete guide to <a href="https://www.alltechnotricks.com/Blog/github-pages-custom-domain.html" target="_blank" rel="noopener">host a website using Github pages.</a> </blockquote>

{% include googlead4.html %}

<h2 id="jekyll"><strong>11. What is Jekyll?</strong></h2>

<strong>Jekyll</strong> is a s<strong>tatic site generator</strong>, which in reduced terms means that it will let you develop a website with some dynamic-like functionalities like automatic navigation menus, cross-links and so on; but the end result is actually just generated as static files (files that only need to be served, not computed). <a href="https://jekyllrb.com/" target="_blank" rel="noopener">Jekyll</a> Static files only need to be hosted on a web server (which makes it cheap) and are easily deployable. You give it text written in your favorite markup language and it churns through layouts to create a static website. Throughout that process, you can tweak how you want the site URLs to look, what data gets displayed in the layout, and many more.

<figure><img src="/uploads/github-pages-jekyll-homepage.png" data-src="/uploads/github-pages-jekyll-homepage.png" alt="github-pages-jekyll-homepage" title="github-pages-jekyll-homepage" class="lazy" />
<figcaption>Github Pages: Jekyll Homepage.
</figcaption>
</figure>

Most, importantly, we can blog with <strong>Jekyll</strong>, as you were reading this article, my blog(<a href="https://www.alltechnotricks.com" target="_blank" rel="noopener">Karunakar Patel blog</a>) is hosted on Github served as Github pages for free by using <strong>Jekyll.</strong>

<blockquote>GitHub Pages are powered by Jekyll, so you can easily deploy your site using GitHub for free—custom domain name and all.
<br> <br> Let's get started at <a href="https://jekyllrb.com/" target="_blank" rel="noopener">Jekyll(static site generator) → </a></blockquote>

{% include googlead5.html %}

<h2 id="custom-domain-to-github-pages"><strong>12. How to add a custom domain name to Github Pages?</strong></h2>

Go to your GitHub Pages site's repository settings. Under "<strong>Custom domain</strong>", add or remove your custom domain and click “<strong>Save</strong>”. Setting “<strong>custom domain</strong>” creates a file named <strong>CNAME</strong> in the same repository. That's it we add a custom domain name to Github.

<blockquote>Learn more about adding a <a href="https://www.alltechnotricks.com/Blog/github-pages-custom-domain.html" target="_blank" rel="noopener">custom domain name to Github pages</a> →</blockquote>

<h2 id="github-pages-with-HTTPS"><strong>13. How to secure the Github Pages site with HTTPS?</strong></h2>

<strong>HTTPS</strong> adds a layer of encryption that prevents others from snooping on or tampering with traffic to your site. You can enforce HTTPS for your <strong>GitHub Pages site</strong> to transparently redirect all HTTP requests to HTTPS.

Here is how to add HTTPS to Github Pages.

<ol>
<li>On GitHub, navigate to the main page of the repository.</li>
<li>Under your repository name, click Settings.</li>
<li>Under "GitHub Pages," select Enforce HTTPS.</li>
</ol>

<blockquote>Learn more at <a href="https://www.alltechnotricks.com/Blog/add-HTTPS-Github-Pages-custom-domain.html" target="_blank" rel="noopener">adding HTTPS to Github pages.</a>→
<br> The same technique I used to add HTTPS to my <a href="https://www.alltechnotricks.com" target="_blank" rel="noopener">Karunakar Patel Blog</a>. </blockquote>

{% include googlead4.html %}

<h2 id="usage-limits-of-github-pages"><strong>14. What are the usage limits of GitHub Pages?</strong></h2>

GitHub Pages sites are subject to the following usage limits:

<ol>
<li>GitHub Page's source repositories have a recommended limit of 1GB.</li>
<li>Published GitHub Pages sites may be no larger than 1 GB.</li>
<li>GitHub Pages sites have a soft bandwidth limit of 100GB per month.</li>
<li>GitHub Pages sites have a soft limit of 10 builds per hour.</li>
</ol>

If your site exceeds these usage quotas, we may not be able to serve your site, or you may receive a polite email from <strong>GitHub</strong> Support or <strong>GitHub Premium</strong> Support suggesting strategies for reducing your site's impact on our servers, including putting a third-party <strong>content distribution network(CDN)</strong> in front of your site, making use of other GitHub features, such as releases, or moving to a different hosting service that might better fit your needs.

<strong>GitHub Pages</strong> is not intended for or allowed to be used as a free web hosting service to run your online business, e-commerce site, or any other website that is primarily directed at either facilitating commercial transactions or providing commercial software as a service (SaaS).

<div class="anim_container">
<button id="show">
<svg width="24" height="20" viewBox="0 0 24 20">
<path d="M3 0H1C0.4 0 0 0.4 0 1V3C0 3.6 0.4 4 1 4H3C3.6 4 4 3.6 4 3V1C4 0.4 3.6 0 3 0Z"
									fill="#0066FF" />
								<path d="M3 0H1C0.4 0 0 0.4 0 1V3C0 3.6 0.4 4 1 4H3C3.6 4 4 3.6 4 3V1C4 0.4 3.6 0 3 0Z"
									transform="translate(0 8)" fill="#0066FF" />
								<path d="M3 0H1C0.4 0 0 0.4 0 1V3C0 3.6 0.4 4 1 4H3C3.6 4 4 3.6 4 3V1C4 0.4 3.6 0 3 0Z"
									transform="translate(0 16)" fill="#0066FF" />
								<path
									d="M15 0H1C0.4 0 0 0.4 0 1V3C0 3.6 0.4 4 1 4H15C15.6 4 16 3.6 16 3V1C16 0.4 15.6 0 15 0Z"
									transform="translate(8)" fill="#0066FF" />
								<path
									d="M15 0H1C0.4 0 0 0.4 0 1V3C0 3.6 0.4 4 1 4H15C15.6 4 16 3.6 16 3V1C16 0.4 15.6 0 15 0Z"
									transform="translate(8 8)" fill="#0066FF" />
								<path
									d="M15 0H1C0.4 0 0 0.4 0 1V3C0 3.6 0.4 4 1 4H15C15.6 4 16 3.6 16 3V1C16 0.4 15.6 0 15 0Z"
									transform="translate(8 16)" fill="#0066FF" />
							</svg>
						</button>
<div id="links_container">
			<ol>
				<li> <a href="#github" class="test"><b>What is Github?</b></a></li>
				<li><a href="#git" class="test"><b>What is Git?</b></a></li>
				<li><a href="#version-control-system" class="test"><b>What is version control system?</b></a></li>
				<li><a href="#github-pages" class="test"><b>What is GitHub Pages?</b></a></li>
				<li><a href="#install-git-in-pc" class="test"><b>How to install Git in pc?</b></a></li>
				<li><a href="#github-desktop" class="test"><b>What is Github Desktop?</b></a></li>
				<li><a href="#install-github-desktop" class="test"><b>How to install Github Desktop?</b></a></li>
				<li><a href="#git-commands" class="test"><b>What are some basic Git Commands?</b></a></li>
				<li><a href="#create-repo-in-github" class="test"><b>How to create a repository in Github?</b></a></li>
				<li><a href="#host-website-using-github-pages" class="test"><b>Can I host a website using Github Pages?</b></a></li>
				<li><a href="#jekyll" class="test"><b>What is Jekyll?</b></a></li>
				<li><a href="#custom-domain-to-github-pages" class="test"><b>Adding a custom domain to Github Pages?</b></a></li>
				<li><a href="#github-pages-with-HTTPS" class="test"><b>How to secure the Github Pages site with HTTPS?</b></a></li>
				<li><a href="#usage-limits-of-github-pages" class="test"><b>What are the usage limits of Github Pages?</b></a></li>
				<li><a href="#disqus_thread" class="test"><b>Throw a Comment.</b></a></li>
			</ol>
		</div>
</div>
