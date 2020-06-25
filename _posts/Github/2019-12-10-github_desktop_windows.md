---
title: Github Desktop - Install and use GitHub desktop for windows.
permalink: Blog/github_desktop_windows.html
layout: post
image: upload/github-desktop-windows.png
description: "Install and use GitHub Desktop on windows to manage your project work. Authenticate to GitHub.com, keep the project up-to-date, and review your preferred settings. Use GitHub Desktop to manage your projects, create meaningful commits, and track the project's history in an app instead of on the command line."
datepublished: "2020-01-17"
datemodified: "2020-06-25"
margin-top: -120px
category: [Github-Pages, Blog]
---

This guide will walk you through the process of using GitHub Desktop to work on a Git repository. GitHub Desktop extends and simplifies your GitHub.com workflow, using a visual interface instead of text commands on the command line. By the end of this guide, you'll have used GitHub Desktop to create a repository, make changes to the repository, and publish the changes to GitHub.com.

Although most developers use the command line when working with version control systems, there are many GUI clients available that can potentially simplify the process. GUI clients might be especially helpful when you’re trying to see what has changed in a file since the GUI can quickly highlight and indicate the changes taking place.

Here are the quick steps to download and install the Github desktop.

<ol id="install-github-desktop">
<li>Visit the GitHub Desktop download page. </li>
<li>Choose Download for Windows.</li>
<li><span style="color: black; font-weight: bolder">Note:</span> If you are a network administrator, you can use the GitHub Desktop Windows installer package to deploy GitHub Desktop.</li>

<li>  In your computer's Downloads folder, double-click GitHub Desktop. </li>
<li>In the pop-up window, click Install.</li>

<li>After the program has been installed, click Run. </li>
<li>Launch GitHub Desktop and follow the initial welcome flow to sign into your GitHub account. You'll see a "Configure Git" step, where you can set your name and email address. To ensure your commits are correctly attributed to your GitHub account, use the email address associated with your GitHub account.</li></ol>

<img src="/uploads/github-desktop.png">

With GitHub Desktop open, you can drag and drop repositories from within the file manager to automatically add them to your Git repository, or you can clone a repository from your GitHub account to your local drive (repositories clone to C:\Users\NAME\Documents\GitHub--where NAME is your Windows username).

With a repository cloned to your local drive, you can start working on it locally and then compare, merge, rebase, creating a new repository, deleting repository and many more.

Once your work is complete, you can push it back to GitHub by clicking Repository - Push. If you work with a team, you can create new pull requests by clicking Repository - Pull.

After installing the Github desktop, then perform reading these actions to master the Github desktop.

{% include googlead1.html %}

Below the menu is a bar that shows the current state of your repository in GitHub Desktop:

<ul>

<li><strong>Current repository</strong> shows the name of the repository you're working on. You can click on the Current repository to switch to a different repository in GitHub Desktop.  </li>

<li><strong>Current branch</strong> shows the name of the branch you're working on. You can click on the Current branch to view all the branches in your repository, switch to a different branch, or create a new branch. Once you create pull requests in your repository, you can also view these by clicking on the Current branch.</li>

<li><strong>Publish repository</strong> appears because you haven't published your repository to GitHub yet, which you'll do later in the next step. </li>

<img src="/uploads/explore-github-desktop.png">

</ul>

In the left sidebar, you'll find the Changes and History views.

<ul>
<li>The <strong>Changes view</strong> shows changes you've made to files in your current branch but haven't committed to your local repository. At the bottom, you'll also notice a box with "Summary" and "Description" text boxes and a <strong>Commit to master</strong> button. This is where you'll commit new changes. The Commit button lets you know which branch you're committing your changes to.
</li>

<img src="/uploads/commit-area.png">

<li> The <strong>History view</strong> shows the previous commits on the current branch of your repository. You should see an "Initial commit" that was created by GitHub Desktop when you created your repository. To the right of the commit, depending on the options you selected while creating your repository, you may see .gitattributes, .gitignore, LICENSE, or README files. You can click each file to see a diff for that file, which is the changes made to the file in that commit. The diff only shows the parts of the file that have changed, not the entire contents of the file.  
</li>

<img src="/uploads/history-view.png">

</ul>

<h2>Push your repository to GitHub using Github Desktop.</h2>

Currently, your repository only exists on your computer, and you're the only one who can access the repository. Publishing your repository to GitHub keeps it synchronized across multiple computers and team members on the same project. To publish the repository, you'll "push" it to GitHub, which makes it available on GitHub.com as well.

<ul>

Click Publish repository.

<img src="/uploads/publish-repository.png">

<li>You'll see a few familiar fields. "Name" and "Description" match the fields you completed when you created the repository.</li>

<li>You'll see the option to Keep this code private. Select this option if you don't want to share your code publicly with other users on GitHub.</li>

<li>The Organization dropdown, if present, lets you publish your repository to a specific organization that you belong to on GitHub. It's okay if you're not a member of an organization yet!
</li>

<img src="/uploads/publish-repository-steps.png">

<li>Click Publish repository.</li>

<li>You can access the repository on GitHub.com from within GitHub Desktop. In the file menu, click Repository, then click View on GitHub. This will take you directly to the repository in your default browser. </li>
</ul>

{% include googlead2.html %}

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
        <li><a href="#install-github-desktop" class="test"><b>Install Github Desktop.</b></a></li>
								<li><a href="#disqus_thread" class="test"><b>Throw a comment</b></a></li>
							</ol>
						</div>
</div>
