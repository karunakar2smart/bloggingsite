---
title: Add HTTPS to Github pages with a custom domain for Free.
permalink: Blog/add-HTTPS-Github-Pages-custom-domain.html
layout: post
image: upload/add-https-image-with-lock.jpg
description: "We learn about adding HTTPS to Github Pages with a Custom Domain. Yes, I learned all the tricks about Adding HTTPS to Github pages, what is https, the purpose of HTTPS, and also about Github Pages."
datepublished: "2018-12-09"
datemodified: "2019-08-28"
margin-top: -170px

---

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

<figure><img src="/uploads/setting-enforce-https-github-pages.png" data-src="uploads/setting-enforce-https-github-pages.png" alt="https-github-pages" title="Adding-HTTPS-to-Github-Pages" class="lazy" />
<figcaption>Setting HTTPS-Enforce to Github Pages.
</figcaption>
</figure>

Make sure that you have checked "**Enforce HTTPS**" button and hit the save button. That's it, after a while our custom domain website runs with **HTTPS** request, ensuring users who request your site over HTTP are upgraded to HTTPS.

{% include googlead5.html %}

<h3><strong>Github Public Announcement.</strong></h3>

Github has partnered with the certificate authority Let’s Encrypt on this project. As supporters of [Let’s Encrypt’s mission](https://letsencrypt.org/){: target="_blank" rel="noopener"} to make the web more secure for everyone, we’ve officially become Silver-level sponsors of the initiative.

Thank you for reading this tutorial.

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
				<li><a href="#what-is-HTTPS" class="test"><b>What is HTTPS?</b></a></li>
				<li><a href="#purpose-of-HTTPS" class="test"><b>What is Purpose of HTTPS?</b></a></li>
				<li><a href="#add-HTTPS-Github-Pages" class="test"><b>Add HTTPS to Github Pages.</b></a></li>
				<li><a href="#discourse-comments" class="test"><b>Throw a comment.</b></a></li>
			</ol>
		</div>
</div>
