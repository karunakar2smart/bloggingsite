--- 
title: Host a website using Github pages with a custom URL and Godaddy Domain.
permalink: Blog/github-pages-custom-domain.html
layout: post 
image: upload/host-website-using-github-pages.png
description: "We can host a website using Github pages with a custom URL and a personal domain name. We will learn more about adding CNAME file, creating a new repository on Github, configuring DNS for Domain name and finally checking the live status of our website with custom URL." 
datepublished: "2018-10-23" 
datemodified: "2019-07-21"
margin-top: -300px

---
<div class="imp_container">
<div class="important_links">
					<ol>
						<li style=" font-weight: bold; list-style: none;">Launch a Website with a Custom URL using Github Pages and Godaddy Domains.</li>
						<li style="list-style-position: inside;"><a href="#buy-domain-name-at-godaddy-domains"><h2><strong>Buy a Domain Name at Godaddy Domains.</strong></h2></a></li>
						<li style="list-style-position: inside;"><a href="#create-a-simple-static-webpage"><h2><strong>Create a Simple Static Site.</strong></h2></a></li>
						<li style="list-style-position: inside;"><a href="#create-new-repo-on-github"><h2><strong>Create New Repository On Github.</strong></h2></a></li>
						<li style="list-style-position: inside;"><a href="#add-CNAME-file-to-github"><h2><strong>Adding CNAME file to Github Pages.</strong></h2></a></li>
						<li style="list-style-position: inside;"><a href="#configure-DNS-server-for-domain-name"><h2><strong>Configure DNS Server For Domain Name.</strong></h2></a></li>
					</ol>
				</div>
</div>

<div class="header-image">
<img src="#" data-src="../upload/host-website-using-github-pages.png" class="lazy" alt="add-HTTPS-to-github-page-custom-domain" title="add-HTTPS-to-github-page-custom-domain">
</div>

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

<div style="width: 100%; height: auto; text-align: center; background-color: rgba(0, 0, 0, 0.53); color: white; padding: 5px; margin: auto; font-size: 19px;"> <code>
		&lt!DOCTYPE html&gt <br>
		&lthtml&gt <br>
		&lthead&gt <br>
		&lttitle&gt This is Title of the Webpage. &lt/title&gt <br>
		&lt/head&gt <br>
		&ltbody&gt <br>
		&lth1&gt This is heading number 1. &lt/h1&gt  <br>
		&lth2&gt This is heading number 2. &lt/h2&gt  <br>
		&ltp&gt This is the paragraph to describe some news. &lt/p&gt <br>
		&lt/body&gt <br>
		&lt/html&gt
		</code> 
</div>

{% include googlead5.html %}

<h2 id="create-new-repo-on-github"><strong>3. Create The New Repository On Github</strong></h2>

Create a new **REPOSITORY** on **Github.com** by just clicking the plus icon on the top right corner and then the **new repository**. Fill all the essential fields according to your interest and hit the submit button.

After creating click on the add **new file** to upload our newly created simple **index.html** document which we were already created in **step2**. Upload this **index.html** document and hit **commit** with a message.

<div class="article-image">
<img src="#" data-src="../uploads/creating-new-repository.png" class="lazy" alt="creating-new-repositor" title="creating-new-repositor">
</div>	

Another way to create a **new repository** is by using **GitBash**. After installing **Github** desktop locally we can **add** (<code>$ git add</code>), **commit** (<code>$ git commit -m "Commit Message"</code>), **push** (<code>$ git push</code>) etc directly from the GitBash. I have written an awesome article on how to commit, push, add the new repository by using **git command lines**.

<div class="article_inside_notes">
<svg viewbox="0 0 448 512">
					<path d="M362.146 191.976c-13.71-21.649-38.761-34.016-65.006-30.341V74c0-40.804-32.811-74-73.141-74-40.33 0-73.14 33.196-73.14 74L160 168l-18.679-78.85C126.578 50.843 83.85 32.11 46.209 47.208 8.735 62.238-9.571 104.963 5.008 142.85l55.757 144.927c-30.557 24.956-43.994 57.809-24.733 92.218l54.853 97.999C102.625 498.97 124.73 512 148.575 512h205.702c30.744 0 57.558-21.44 64.555-51.797l27.427-118.999a67.801 67.801 0 0 0 1.729-15.203L448 256c0-44.956-43.263-77.343-85.854-64.024zM399.987 326c0 1.488-.169 2.977-.502 4.423l-27.427 119.001c-1.978 8.582-9.29 14.576-17.782 14.576H148.575c-6.486 0-12.542-3.621-15.805-9.449l-54.854-98c-4.557-8.141-2.619-18.668 4.508-24.488l26.647-21.764a16 16 0 0 0 4.812-18.139l-64.09-166.549C37.226 92.956 84.37 74.837 96.51 106.389l59.784 155.357A16 16 0 0 0 171.227 272h11.632c8.837 0 16-7.163 16-16V74c0-34.375 50.281-34.43 50.281 0v182c0 8.837 7.163 16 16 16h6.856c8.837 0 16-7.163 16-16v-28c0-25.122 36.567-25.159 36.567 0v28c0 8.837 7.163 16 16 16h6.856c8.837 0 16-7.163 16-16 0-25.12 36.567-25.16 36.567 0v70z" />
				</svg>
<p>You can check your live version of your simple website at <strong>YOURUSERNAME.github.io</strong></p>
</div>

{% include googlead4.html %}

<h2 id="add-CNAME-file-to-github"><strong>4. Add CNAME File to Github Pages.</strong></h2>

In order to add **CNAME**, click on the upload/New file located at the top right corner of the repository page. Save the file name as **CNAME** with your personal **domain name** in it.

Importantly, we need to save the file name as **CNAME** by including our personal **Godaddy domain name** in it. After filling all the required field hit the commit button with a commit message.

In my case, I filled my **CNAME** file as shown in the image below.

<div class="article-image">
<img src="#" data-src="../uploads/adding-CNAME-file.png" class="lazy" alt="adding-CNAME-file" title="adding-CNAME-file">
</div>	

{% include googlead3.html %}

<h2 id="configure-DNS-server-for-domain-name"><strong>5. Configure DNS Server For DOMAIN Name.</strong></h2>

Over at [https://in.godaddy.com/](https://in.godaddy.com/){: target="_blank" rel="noopener"} head to the “**Manage DNS**” tab and scroll to the “**Custom resource records**” section at the bottom of the page.

<div class="article_inside_links">
<ol style="border-left: 5px solid #06f;">
					<li> We need to <strong>add</strong> two "<strong>@</strong>" type <strong>A records</strong> that point to the <strong>Github IP's 192.30.252.153</strong> and <strong>192.30.252.154</strong>. </li>
					<li> We also need to add one "<strong>www</strong>" <strong>CNAME record</strong> that points to your <strong>USERNAME.github.io</strong> URL. </li>
				</ol>
</div>

In my case, I added the following records at **GoDaddy registrar** as shown in the following image below.

<div class="article-image">
<img src="#" data-src="../uploads/setting-DNS-records.png" class="lazy" alt="setting-DNS-records" title="setting-DNS-records">
</div>	

After completing all the steps, we can really check the **live status** of our website with a **custom URL** which directly redirects our **username.github.io** URL to our **personal domain URL**.

Thank you for reading this tutorial.

Thank you. Please share this article if you love. 😍

{% include googlead3.html %}

---

<div class="anim_container">
<button id="show">
			<svg style="width: 35px; height: 35px; animation: vertical 1s linear infinite; " fill="#06f" viewbox="0 0 320 512">
				<path d="M313.553 119.669L209.587 7.666c-9.485-10.214-25.676-10.229-35.174 0L70.438 119.669C56.232 134.969 67.062 160 88.025 160H152v272H68.024a11.996 11.996 0 0 0-8.485 3.515l-56 56C-4.021 499.074 1.333 512 12.024 512H208c13.255 0 24-10.745 24-24V160h63.966c20.878 0 31.851-24.969 17.587-40.331z" /> </svg>
		</button>
<div id="links_container">
			<ol>
				<li><a href="#buy-domain-name-at-godaddy-domains" class="test"><strong>Buy a Domain Name at Godaddy Domains.</strong></a></li>
				<li><a href="#create-a-simple-static-webpage" class="test"><strong>Create a Simple Static Site.</strong></a></li>
				<li><a href="#create-new-repo-on-github" class="test"><strong>Create New Repository On Github Pages.</strong></a></li>
				<li><a href="#add-CNAME-file-to-github" class="test"><strong>Adding CNAME file to Github Pages.</strong></a></li>
				<li><a href="#configure-DNS-server-for-domain-name" class="test"><strong>Configure DNS Server For Domain Name.</strong></a></li>
				<li><a href="#disqus_thread" class="test"><strong>Throw a comment.</strong></a></li>
			</ol>
			<ol>
				<li><a href="https://www.alltechnotricks.com" target="_top" class="test">Home</a></li>
				<li><a href="https://www.alltechnotricks.com/Blog.html" target="_top" class="test">Blog</a></li>
				<li><a href="#top" class="test">Back To Top</a></li>
			</ol>
		</div>
</div>

			
			
			

			