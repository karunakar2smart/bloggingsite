---
title: Add HTTPS to Github pages with a custom domain for Free.
permalink: Blog/add-HTTPS-Github-Pages-custom-domain.html
layout: post
image: upload/add-https-image-with-lock.jpg
description: "We learn about adding HTTPS to Github Pages with a Custom Domain. Yes, I learned all the tricks about Adding HTTPS to Github pages, what is https, the purpose of HTTPS, and also about Github Pages."
datepublished: "2018-12-09"
last_modified_at: "2019-07-21"
margin-top: -190px

---

<div class="imp_container">
<div class="important_links">
					<ol>
						<li style="font-weight: bold; list-style: none;">Adding "HTTPS" To Github Pages With a Custom Domain.</li>
						<li style="list-style-position: inside;"><a href="#what-is-HTTPS"><h2><strong>What is HTTPS?</strong></h2></a></li>
						<li style="list-style-position: inside;"><a href="#purpose-of-HTTPS"><h2><strong>What is Purpose of HTTPS?</strong></h2></a></li>
						<li style="list-style-position: inside;"><a href="#add-HTTPS-Github-Pages"><h2><strong>Add HTTPS to Github Pages.</strong></h2></a></li>
					</ol>
				</div>
</div>

<div class="header-image">
<img src="#" data-src="../upload/add-https-image-with-lock.jpg" class="lazy" alt="add-HTTPS-to-github-page-custom-domain" title="add-HTTPS-to-github-page-custom-domain">
</div>	

In here, we learn all the steps required to **add HTTPS with a custom URL using Github pages**. Yes, we can add "**HTTPS**" or **SSL certificate** to our own website using **Github pages** without paying any money. Most importantly, my website([https://www.alltechnotricks.com](https://www.alltechnotricks.com/){: target="_blank" rel="noopener"}) has also added **HTTPS** by using these techniques.

All we need to have a **custom domain** name hosted using Github Pages. I do blogging through this technique without paying any fee. As always, there is no charge for adding **SSL certificate** to **Github pages**.

{% include googlead1.html %}

<h2 id="what-is-HTTPS"><strong>1. What is HTTPS?</strong></h2>

**Hypertext Transfer Protocol Secure (HTTPS)** is an extension of the **Hypertext Transfer Protocol (HTTP)** for secure communication over a computer network and is widely used on the Internet.

In **HTTPS**, the communication protocol is encrypted using Transport Layer Security (TLS), or formerly, its predecessor, **Secure Sockets Layer (SSL)**. The protocol is therefore also often referred to as HTTP over TLS, or **HTTP** over **SSL**. 

<h2 id="purpose-of-HTTPS"><strong>2. What is the Purpose of HTTPS?</strong></h2>


**HTTPS** encrypts traffic between GitHub’s servers and your browser giving you confidence that the page you asked for is the page you’re reading, from the site you think it is, and that others can’t snoop on or modify its contents along the way.

The principal motivation for **HTTPS** is authentication of the accessed website and protection of the privacy and integrity of the exchanged data while in transit. 

It protects against man-in-the-middle attacks. The bidirectional encryption of communications between a client and server protects against eavesdropping and tampering of the communication.

In practice, this provides a reasonable assurance that one is communicating without interference by attackers with the website that one intended to communicate with, as opposed to an impostor. 

{% include googlead3.html %}

<h2 id="add-HTTPS-Github-Pages"><strong>3. Adding "HTTPS" to Github Pages with Custom Domain.</strong></h2>

Adding **HTTPS** to Github pages with a **custom domain** is as easy as adding a CNAME file to Github. Importantly, we are going to add an SSL certificate to our custom domain using Github pages.

All we need to follow these steps respectively. Ok, let us get started.

After creating and uploading **CNAME file** with a custom domain name in it as shown in the previous post, login into Github repository page then, scroll down to the repository settings page, then you will find a section called "**Github Pages**" as shown in the image below. 

<div class="article-image">
<img src="#" data-src="../uploads/setting-enforce-https-github-pages.png" class="lazy" alt="setting-enforce-https-github-pages" title="setting-enforce-https-github-pages">
</div>	

Make sure that you have checked "**Enforce HTTPS**" button and hit the save button. That's it, after a while our custom domain website runs with **HTTPS** request, ensuring users who request your site over HTTP are upgraded to HTTPS.

{% include googlead5.html %}

<h3><strong>Github Public Announcement.</strong></h3>

Github has partnered with the certificate authority Let’s Encrypt on this project. As supporters of [Let’s Encrypt’s mission](https://letsencrypt.org/){: target="_blank" rel="noopener"} to make the web more secure for everyone, we’ve officially become Silver-level sponsors of the initiative.

Thank you for reading this tutorial.

{% include googlead3.html %}

---
<div class="anim_container">
<button id="show">
			<svg style="width: 35px; height: 35px; animation: vertical 1s linear infinite;" fill="#06f" viewbox="0 0 320 512">
				<path d="M313.553 119.669L209.587 7.666c-9.485-10.214-25.676-10.229-35.174 0L70.438 119.669C56.232 134.969 67.062 160 88.025 160H152v272H68.024a11.996 11.996 0 0 0-8.485 3.515l-56 56C-4.021 499.074 1.333 512 12.024 512H208c13.255 0 24-10.745 24-24V160h63.966c20.878 0 31.851-24.969 17.587-40.331z" /> </svg>
		</button>
<div id="links_container">
			<ol>
				<li><a href="#what-is-HTTPS" class="test"><strong>What is HTTPS?</strong></a></li>
				<li><a href="#purpose-of-HTTPS" class="test"><strong>What is Purpose of HTTPS?</strong></a></li>
				<li><a href="#add-HTTPS-Github-Pages" class="test"><strong>Add HTTPS to Github Pages.</strong></a></li>
				<li><a href="#disqus_thread" class="test"><strong>Throw a comment.</strong></a></li>
			</ol>
			<ol>
				<li><a href="https://www.alltechnotricks.com" target="_top" class="test">Home</a></li>
				<li><a href="https://www.alltechnotricks.com/Blog.html" target="_top" class="test">Blog</a></li>
				<li><a href="#top" class="test">Back To Top</a></li>
			</ol>
		</div>
</div>
			



			
			