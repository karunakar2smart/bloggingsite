---
title: Host a website using Github pages with a custom URL and Godaddy Domain.
permalink: Blog/github-pages-custom-domain.html
layout: post
image: upload/host-website-using-github-pages.png
description: "We can host a website using Github pages with a custom URL and a personal domain name. We will learn more about adding CNAME file, creating a new repository on Github, configuring DNS for Domain name and finally checking the live status of our website with custom URL."
datepublished: "2018-10-23"
datemodified: "2020-12-25"
margin-top: -310px
tags: github-pages
category: [Github-Pages, Blog]
---

In here, we learn all the steps required to **launch a website with a custom URL using Github pages and GoDaddy Domain name**. Yes, we can launch our own website as Github pages without paying any **hosting fee**. Most importantly, this website(<a href="https://www.alltechnotricks.com/" target="_blank" rel="noopener">www.alltechnotricks.com</a>) has also hosted as **Github pages**.

All we need to have some coding knowledge and a **custom domain name**. I eventually do blogging through this technique without paying any hosting fee. As always, there is no charge for **hosting as Github pages**.

<h2 id="buy-domain-name-at-godaddy-domains"><strong>1. Buy Your Domain Name At GoDaddy Domains.</strong></h2>

Firstly, we need to buy a **domain name**. In my case, I prefer **Godaddy** because their customer support is very good. Choose whatever you prefer to make a living and buy it.

Importantly, **Google** does not rank its domains based on their names. i.e. .COM doesn't rank much higher than .ORG or .IO or any other domain name. All the domain name rankings depend on **Google's search engine optimization(SEO)**.

{% include googlead2.html %}

<h2 id="create-a-simple-static-webpage"><strong>2. Create A Simple Static Website.</strong></h2>

We need to create a static **HTML webpage** and save it as **index.html**. All the required tags must be included in the **index.html** webpage in which we must be coded manually or by doing copy paste.

Then make your super awesome website. Paste the following into **index.html**. If you are feeling adventurous you could paste some of the sites from HTML5 UP. It’s your website so I’ll leave that up to you!

Here is the simple **code** of a webpage with simple **important tags**.

<pre>
<code>
&lt;!DOCTYPE html&gt; <br>
&lt;html&gt; <br>
&lt;head&gt; <br>
&lt;title&gt;
&lt;This is Title of the Webpage. &lt;/title&gt; <br>
&lt;/head&gt; <br>
&lt;body&gt; <br>	&lt;h1&gt; This is heading number 1. &lt;/h1&gt;  <br>
&lt;h2&gt; This is heading number 2. &lt;/h2&gt; <br>
&lt;p&gt; This is the paragraph to describe some news. &lt;/p&gt; <br>
&lt;/body&gt; <br>
&lt;/html&gt;
</code>
</pre>

{% include googlead5.html %}

<h2 id="create-new-repo-on-github"><strong>3. Create The New Repository On Github</strong></h2>

Create a new **REPOSITORY** on **Github.com** by just clicking the plus icon on the top right corner and then the **new repository**. Fill all the essential fields according to your interest and hit the submit button.

After creating click on the add **new file** to upload our newly created simple **index.html** document which we were already created in **step2**. Upload this **index.html** document and hit **commit** with a message.

<figure>
<img src="/uploads/creating-new-repository.png" data-src="/uploads/creating-new-repository.png" class="lazy" alt="creating-new-repositor" title="creating-new-github-repositor">
<figcaption>Create New Github Repository.</figcaption>
</figure>

Another way to create a **new repository** is by using **GitBash**. After installing **Github** desktop locally we can **add** (<code>$ git add</code>), **commit** (<code>$ git commit -m "Commit Message"</code>), **push** (<code>\$ git push</code>) etc directly from the GitBash. I have written an awesome article on how to commit, push, add the new repository by using **git command lines**.

<blockquote>You can check your live version of your simple website at <strong>YOURUSERNAME.github.io</strong></blockquote>

{% include googlead4.html %}

<h2 id="add-CNAME-file-to-github"><strong>4. Add CNAME File to Github Pages.</strong></h2>

In order to add **CNAME**, click on the upload/New file located at the top right corner of the repository page. Save the file name as **CNAME** with your personal **domain name** in it.

Importantly, we need to save the file name as **CNAME** by including our personal **Godaddy domain name** in it. After filling all the required field hit the commit button with a commit message.

In my case, I filled my **CNAME** file as shown in the image below.

<figure>
<img src="/uploads/adding-CNAME-file.png" data-src="/uploads/adding-CNAME-file.png" class="lazy" alt="adding-CNAME-file" title="adding-CNAME-file">
<figcaption>Adding CNAME File To Github</figcaption>
</figure>

{% include googlead3.html %}

<h2 id="configure-DNS-server-for-domain-name"><strong>5. Configure DNS Server For DOMAIN Name.</strong></h2>

Over at [https://in.godaddy.com/](https://in.godaddy.com/){: target="\_blank" rel="noopener"} head to the “**Manage DNS**” tab and scroll to the “**Custom resource records**” section at the bottom of the page.

<ol>
<li> We need to <strong>add</strong> two "<strong>@</strong>" type <strong>A records</strong> that point to the <strong>Github IP's 192.30.252.153</strong> and <strong>192.30.252.154</strong>. </li>
<li> We also need to add one "<strong>www</strong>" <strong>CNAME record</strong> that points to your <strong>USERNAME.github.io</strong> URL. </li>
</ol>

In my case, I added the following records at **GoDaddy registrar** as shown in the following image below.

<figure>
<img src="/uploads/setting-DNS-records.png" data-src="/uploads/setting-DNS-records.png" class="lazy" alt="setting-DNS-records" title="setting-DNS-records">
<figcaption>Setting DNS Records</figcaption>
</figure>

After completing all the steps, we can really check the **live status** of our website with a **custom URL** which directly redirects our **username.github.io** URL to our **personal domain URL**.

Thank you for reading this tutorial.

Thank you. Please share this article if you love. 😍

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
				<li><a href="#buy-domain-name-at-godaddy-domains" class="test"><b>Buy a Domain Name at Godaddy Domains.</b></a></li>
				<li><a href="#create-a-simple-static-webpage" class="test"><b>Create a Simple Static Site.</b></a></li>
				<li><a href="#create-new-repo-on-github" class="test"><b>Create New Repository On Github Pages.</b></a></li>
				<li><a href="#add-CNAME-file-to-github" class="test"><b>Adding CNAME file to Github Pages.</b></a></li>
				<li><a href="#configure-DNS-server-for-domain-name" class="test"><b>Configure DNS Server For Domain Name.</b></a></li>
				<li><a href="#disqus_thread" class="test"><b>Throw a comment.</b></a></li>
			</ol>
		</div>
</div>
