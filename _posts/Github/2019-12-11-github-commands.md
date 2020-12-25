---
title: Github Commands - List Of Most Useful GitHub Commands.
permalink: Blog/github_commands.html
layout: post
image: upload/github-commands-list.png
description: "List of commonly used Github Commands. Github is a distributed version control system that helps to manage the repositories. In this blog post on git commands, you will explore the top most used basic git commands which would use in a day-to-day workflow."
datepublished: "2020-01-17"
datemodified: "2020-12-25"
margin-top: -320px
category: [Github-Pages, Blog]
---

Git is the free and open-source distributed version control system that's responsible for everything GitHub related that happens locally on your computer. This guide features the most important and commonly used Git commands for easy reference. This guide provides a list of the most common GIT commands, a short description for them and example usage.

Before we begin, you should run git --version to check your current git version. Here is the official git documentation, you can read details about git commands, parameters and new releases of git.

<h3 id="configuration-of-github">Configuration of Github. </h3>

<table>
 <th colspan="2">SETUP GIT</th>
 <tr><td colspan="2" style="text-align: center">Configuring user information used across all local repositories</td></tr>
 <!-- <th colspan="2">Important Dates.</th> --> <br>
 <tr>
 <td>git config --global user.name “[firstname lastname]”</td>
 <td>Set a name that is identifiable for credit when reviewing version history </td>
 </tr>

 <tr>
 <td>git config --global user.email “[valid-email]” 
</td>
 <td>Set an email address that will be associated with each history marker </td>
 </tr>

 <tr>
 <td>git config --global color.ui auto
</td>
 <td>Set automatic command line coloring for Git for easy reviewing</td>
 </tr>
 </table>

{% include googlead1.html %}

<h3 id="github-commands">Working with git – Important Git commands.</h3>

<table>
 <th colspan="2">SETUP & INIT</th>
 <tr><td colspan="2" style="text-align: center">Configuring user information, initializing and cloning repositories.</td></tr><br>
 <tr>
 <td>git init</td>
 <td>Initialize an existing directory as a Git repository.</td>
 </tr>
 <tr>
 <td>git clone [url]</td>
 <td>Retrieve an entire repository from a hosted location via URL.</td>
 </tr>
 </table>

{% include googlead3.html %}

<h3 id="stage-snapshot">STAGE & SNAPSHOT</h3>

<table>
 <th colspan="2">STAGE & SNAPSHOT.</th>
 <tr><td colspan="2" style="text-align: center">Working with snapshots and the Git staging area.</td></tr><br>
 <tr>
 <td>git status</td>
 <td>Show modified files in the working directory, staged for your next commit</td>
 </tr>
 <tr>
 <td>git add [file]</td>
 <td>Add a file as it looks now to your next commit (stage)</td>
 </tr>

 <tr>
 <td>git reset [file]</td>
 <td>Unstage a file while retaining the changes in the working directory.</td>
 </tr>

<tr>
 <td>git diff</td>
 <td>diff of what is changed but not staged.</td>
 </tr>

<tr>
 <td>git diff --staged</td>
 <td>diff of what is staged but not yet committed.</td>
 </tr>

<tr>
 <td>git commit -m “[descriptive message]”</td>
<td>Commit your staged content as a new commit snapshot</td>
</tr>

</table>

{% include googlead4.html %}

<h3 id="branch-merge">BRANCH & MERGE </h3>
<table>

<th colspan="2">BRANCH & MERGE</th>

<tr><td colspan="2" style="text-align: center">Isolating work in branches, changing context, and integrating changes.</td></tr><br>

<tr>
<td>git branch</td>
<td>list your branches. a * will appear next to the currently active branch</td>
</tr>

<tr>
<td>git branch [branch-name]</td>
<td>create a new branch at the current commit</td>
</tr>

<tr>
<td>git checkout</td>
<td>switch to another branch and check it out into your working directory</td>
</tr>

<tr>

<td>git merge [branch]</td>
<td>merge the specified branch’s history into the current one</td>
</tr>

<tr>

<td>git log</td>
<td>Show all commits in the current branch’s history</td>
</tr>
</table>

{% include googlead5.html %}

<h3 id="inspect-compare">INSPECT & COMPARE</h3>
<table>
<th colspan="2">INSPECT & COMPARE</th>
<tr><td colspan="2" style="text-align: center">Examining logs, diffs and object information</td></tr><br>
<tr>
<td>git log</td>
<td>Show the commit history for the currently active branch</td>
</tr>
<tr>
<td>git log branchB..branchA</td>
<td>Show the commits on branchA that are not on branchB.</td>
</tr>
<tr>
<td>git log --follow [file]</td>
<td>Show the commits that changed file, even across renames.</td>
</tr>
<tr>
<td>git diff branchB...branchA</td>
<td>Show the diff of what is in branchA that is not in branchB.</td>
</tr>
<tr>
<td>git show [SHA]</td>
<td>Show any object in Git in human-readable format</td>
</tr>
</table>

{% include googlead2.html %}

<h3 id="tracking-path-changes">TRACKING PATH CHANGES.</h3>

<table>
<th colspan="2">TRACKING PATH CHANGES</th>
<tr><td colspan="2" style="text-align: center">Versioning file removes and path changes</td></tr><br>
<tr>
<td>git rm [file]</td>
<td>Delete the file from project and stage the removal for commit</td>
</tr>
<tr>
<td>git mv [existing-path] [new-path]</td>
<td>Change an existing file path and stage the move</td>
</tr>
<tr>
<td>git log --stat -M</td>
<td>Show all commit logs with indication of any paths that moved</td>
</tr>
</table>

{% include googlead2.html %}

<h3 id="share-update">SHARE & UPDATE</h3>

<table>
<th colspan="2">SHARE & UPDATE</th>
<tr><td colspan="2" style="text-align: center">Retrieving updates from another repository and updating local repos.</td></tr><br>
<tr>
<td>git remote add [alias] [url]</td>
<td>add a git URL as an alias</td>
</tr>
<tr>
<td>git fetch [alias]</td>
<td>fetch down all the branches from that Git remote</td>
</tr>
<tr>
<td>git merge [alias]/[branch]</td>
<td>merge a remote branch into your current branch to bring it up to date</td>
</tr>
<tr>
<td>git push [alias] [branch]</td>
<td>Transmit local branch commits to the remote repository branch</td>
</tr>
<tr>
<td>git pull</td>
<td>fetch and merge any commits from the tracking remote branch</td>
</tr>
</table>

{% include googlead3.html %}

<h3 id="rewrite-history">REWRITE HISTORY</h3>
<table>
<th colspan="2">REWRITE HISTORY</th>
<tr><td colspan="2" style="text-align: center">Rewriting branches, updating commits and clearing history</td></tr><br>
<tr>
<td>git rebase [branch]</td>
<td>Apply any commits of current branch ahead of specified one</td>
</tr>
<tr>
<td>git reset --hard [commit]</td>
<td>Clear staging area, rewrite working tree from specified commit</td>
</tr>
</table>

{% include googlead4.html %}

<h3 id="temporary-commits">TEMPORARY COMMITS</h3>

<table>
<th colspan="2">TEMPORARY COMMITS</th>
<tr><td colspan="2" style="text-align: center">Temporarily store modified, tracked files in order to change branches</td></tr><br>
<tr>
<td>git stash</td>
<td>Save modified and staged changes</td>
</tr>
<tr>
<td>git stash list</td>
<td>List stack-order of stashed file changes</td>
</tr>
<tr>
<td>git stash pop</td>
<td>Write working from top of stash stack</td>
</tr>
<tr>
<td>git stash drop</td>
<td>Discard the changes from top of stash stack.</td>
</tr>
</table>
{% include googlead5.html %}

Next Step

After learning all the basic GitHub commands, then to put your project up on GitHub, you'll need to create a repository for it to live in.
For more information on this karunakar Patel blog, you will walk through the Absolute method to start and create your first own GitHub repository right from start to finish.

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
								<li><a href="#configuration-of-github" class="test"><b>Configuration of Github.</b></a></li>
								<li><a href="#github-commands" class="test"><b>Github Commands.</b></a></li>
								<li><a href="#stage-snapshot" class="test"><b>STAGE & SNAPSHOT</b></a></li>
								<li><a href="#branch-merge" class="test"><b>BRANCH & MERGE </b></a>
								</li>
								<li><a href="#inspect-compare" class="test"><b>INSPECT & COMPARE</b></a></li>
								<li><a href="#tracking-path-changes" class="test"><b>TRACKING PATH CHANGES.</b></a></li>
								<li><a href="#share-update" class="test"><b>SHARE & UPDATE</b></a></li>
								<li><a href="#rewrite-history" class="test"><b>REWRITE HISTORY</b></a></li>
        <li><a href="#temporary-commits" class="test"><b>TEMPORARY COMMITS</b></a></li>
								<li><a href="#disqus_thread" class="test"><b>Throw a comment</b></a></li>
							</ol>
						</div>
</div>
