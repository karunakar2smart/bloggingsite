---
title: Install Git on Windows - A Step By Step Guide To Install Git.
permalink: Blog/install_git_windows.html
layout: post
image: upload/install-git-on-windows.jpg
description: "The following set of instructions details how to install Git on Windows. You can either install it as a package or via another installer or download the source code and compile it. Git for Windows focuses on offering a lightweight, native set of tools that bring the full feature set of the Git SCM to Windows while providing appropriate use."
datepublished: "2020-01-17"
datemodified: "2021-03-05"
margin-top: -118px
category: [Github-Pages, Blog]
---

Here is the best place to learn how to install the latest, stable, prepackaged version git on Windows using their package managers. Git can also be compiled from source and installed on any operating system. This guide will walk you through the basics of getting started with Git, from installing the software to using basic commands on both local and remote repositories (repo).

<strong>Git</strong> is a distributed version control system for tracking changes in source code during software development. It is designed for coordinating work among programmers, but it can be used to track changes in any set of files. Git is the most popular distributed version control and source code management. Its goals include speed, data integrity, and support for distributed, non-linear workflows.

<h2 id="git-for-windows">Git for Windows stand-alone installer.</h2>

<ol>
<li>Download the latest Git for Windows installer and run it. This will open a new window in which you can find all the required information about the software. Click the Next button to proceed.
</li>
<li>Siteground First Image Is Here.</li>
<li>When you've successfully started the installer, you should see the Git Setup wizard screen. On the next step, you should choose where to install the program. <br>

<img src="/uploads/install-git-windows-1.png">

The default path is "C:\Program Files\Git". If you want the software installed in a different location click the Browse button and specify a different folder. <br>

<img src="/uploads/install-git-windows-2.png">

Click Next when ready to proceed. Follow the Next and Finish prompts to complete the installation. The default options are pretty sensible for most users.</li>

<img src="/uploads/install-git-windows-3.png">

<li>Open a Command Prompt (or Git Bash if during installation you elected not to use Git from the Windows Command Prompt).</li>
<li>Run the following commands to configure your Git username and email using the following commands. These details will be associated with any commits that you create:</li>
<pre>
<code>

git config --global user.name "My Name" <br>
git config --global user.email "user@domain.com"

</code>
</pre>
</ol>

You can check your current version of Git by running the git --version command in a terminal (Linux, macOS) or command prompt (Windows).

For example:

<pre>
<code>
git --version <br>
git version 2.7.4
</code>
</pre>

<img src="/uploads/install-git-windows-cmd.jpg">

If you don't see a supported version of Git, you'll need to either upgrade Git or perform a fresh install, as described above.

{% include googlead1.html %}

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
				<li> <a href="#git-for-windows" class="test"><b>Git for Windows</b></a></li>
				<li><a href="#disqus_thread" class="test"><b>Throw a Comment.</b></a></li>
			</ol>
		</div>
</div>
