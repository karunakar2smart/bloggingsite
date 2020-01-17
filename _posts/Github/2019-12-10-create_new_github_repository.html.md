---
title: Absolute Method To Start And Create Your First Own GitHub Repository.
permalink: Blog/create_new_github_repository.html
layout: post
image: upload/create-first-github-repository.png
description: "This tutorial will guide you through to create and use a new Github repository where GitHub stores each project in its own online repository. we can also create a remote repository on GitHub right from the command line, allow the user to interactively create a .gitignore file and so on."
datepublished: "2020-01-17"
datemodified: "2020-01-17"
margin-top: -200px
category: [Github-Pages, Blog]
---

This tutorial provides an overview of how to set up a repository (repo) under Git version control. This resource will walk you through initializing a Git repository for a new or existing project. Included below are workflow examples of repositories both created locally and cloned from remote repositories. This guide assumes a basic familiarity with a command-line interface.

<h1 id="what-is-github-repository">What is the Github Repository?</h1>

A repository is like a folder for your project. Your project’s repository contains all of your project’s files and stores each file’s revision history. You can also discuss and manage your project’s work within the repository. You can own repositories individually, or you can share ownership of repositories with other people in an organization.

<h2 id="create-new-github-repository">Create a new Github Repository.</h2>

<ol>
<li>In the upper-right corner of any page, use the drop-down menu, and select New repository. <br>
<img src="/uploads/git-new-repository-1.png">
 </li>
<li>Type a short, memorable name for your repository. For example, "hello-world". <br>
<img src="/uploads/git-new-repository-2.png">
</li>
<li>Optionally, add a description of your repository. For example, "My first repository on GitHub." <br>
<img src="/uploads/git-new-repository-3.png">
</li>

<li>Choose to make the repository either public or private. Public repositories are visible to the public, while private repositories are only accessible to you, and people you share them with. For more information, see "Setting repository visibility." <br>
<img src="/uploads/git-new-repository-4.png">
</li>

<li>Select Initialize this repository with a README. <br>


<img src="/uploads/git-new-repository-5.png">

</li>
<li>Click Create repository.</li>
</ol>

Congratulations! You've successfully created your first repository and initialized it with a README file.

{% include googlead2.html %}

<hr>

<h1 id="create-github-repo-using-command-line">Create Github repo using the command line.</h1>

<ol>
<li>Open Git Bash.</li>
<li>Change the current working directory to your local project.</li>
<li>Initialize the local directory as a Git repository. <br>
<pre><code> $ git init </code></pre></li>
<li>Add the files to your new local repository. This stages them for the first commit. <br>
<pre><code>$ git add <br>
# Adds the files in the local repository and stages them for commit. To unstage, a file, use 'git reset HEAD YOUR-FILE'. </code></pre></li>
<li>Commit the files that you've staged in your local repository. <br>
<pre><code>$ git commit -m "First commit" <br>
# Commits the tracked changes and prepares them to be pushed to a remote repository. To remove this commit and modify the file, use 'git reset --soft HEAD~1' and commit and add the file again.</code></pre></li>
<li>At the top of your GitHub repository's Quick Setup page, click to copy the remote repository URL.<br> <img src="/uploads/git-repo-setup.png"></li>
<li>In the Command prompt, add the URL for the remote repository where your local repository will be pushed.</li>

<pre><code>$ git remote add origin remote repository URL <br>
# Sets the new remote  <br>
$ git remote -v <br>
# Verifies the new remote URL</code></pre>
<li>Push the changes in your local repository to GitHub. <br>
</li>

<pre><code>$ git push origin master <br>
# Pushes the changes in your local repository up to the remote repository you specified as the origin</code></pre>
</ol>

{% include googlead3.html %}

<h4>Next Step</h4>

Here I demonstrated how to create a git repository using two methods: git init and git clone. All the processes we have done here had been achieved by using the command line. 

Instead of using the command line, we can also use Graphic User Interface software i.e GUI named Github desktop. 

we can use <a href="https://www.alltechnotricks.com/Blog/github_desktop_windows.html" rel="noopener">GitHub Desktop</a> to manage your projects, create meaningful commits, keep the project up-to-date, and review your preferred settings and track the project's history in an app instead of on the command line.

{% include googlead4.html %}


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
						</button><div id="links_container">
							<ol>
        <li><a href="#what-is-github-repository" class="test"><b>What is the Github Repository?</b></a></li>
        <li><a href="#create-new-github-repository" class="test"><b>Create a new Github Repository.</b></a></li>
        <li><a href="#create-github-repo-using-command-line" class="test"><b>Create Github repo using the command line.</b></a></li>
								<li><a href="#disqus_thread" class="test"><b>Throw a comment</b></a></li>
							</ol>
						</div>
</div>