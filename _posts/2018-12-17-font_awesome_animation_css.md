---
title: Animate All Font Awesome Icons With Pure CSS to Get Visitors Attention.
permalink: Blog/font_awesome_animation_css.html
layout: post
image: upload/css-animation-fontawesome-icons.png
description: "Font awesome icons with CSS animations would help to increase the engagement of the visitors. I included simple pure CSS code using font awesome CDN's where you can directly copy pure CSS code and paste in to use to animate all font awesome icons and use in your website for free. There are different types of animations for you to select and use for free. Learn more at font awesome icons with pure CSS animations."
datepublished: "2018-12-17"
datemodified: "2019-08-28"
margin-top: -180px

---

<b>Font Awesome</b> is a font and icon toolkit based on CSS and LESS. It was made by <b>Dave Gandy</b> for use with Twitter Bootstrap and later was incorporated into the <b>BootstrapCDN</b>. Font Awesome has a 20% market share among those websites which use third-party Font Scripts on their platform, ranking it second place after <b>Google Fonts</b>.

The use of <b>font awesome icons</b> in web design is a proven method to modernize a website and help direct user flow. Adding icons to your site’s content helps a user better process the information you’re trying to convey and provides a visual focal point that grounds a user to a specific section.

Graphical icons can be used in any number of ways to spice up your web design project. You can use them as visual accompaniments to text areas or as standalone links in situations where space is tight and text blocks aren’t feasible within the design. It’s this versatility to icons which makes them both so useful and widespread.

Fortunately, there’s no need to go about producing your own icon set. <b>Font Awesome</b> provides a versatile framework that incorporates nearly any icon graphic you can imagine along with needed scalability and customization capabilities. <b>Font Awesome</b> will almost assuredly save you time and money in your application of specific icons. The following article will walk through incorporating Font Awesome icons to optimize your web design project.

<h2 id="font-awesome-CDN"><strong>What is Font Awesome CDN?</strong></h2>

A <b>content delivery network (CDN)</b> refers to a geographically distributed group of servers which work together to provide fast delivery of Internet content. A <b>CDN</b> allows for the quick transfer of assets needed for loading Internet content including HTML pages, javascript files, stylesheets, images, and videos. The popularity of <b>CDN</b> services continues to grow, and today the majority of web traffic is served through CDNs, including traffic from major sites like Facebook, Netflix, and Amazon.

The most important benefits of using a CDN are

<ol>
<li>Improving website loading times.</li>
<li>Reducing bandwidth costs.</li>
<li>Increasing content availability and redundancy.</li>
<li>Improving website security.</li>
</ol>

{% include googlead1.html %}

<h2><strong>Adding Font Awesome CDN to our Website.</strong></h2>

To begin, you first want to ensure the following <a href="https://fontawesome.com/" target="_blank" rel="noopener">Font Awesome</a> resources are included on your site. No downloading or complicated scripts are needed--just one reference of the <b>Font Awesome CSS</b> will get you started.

To use font awesome icons in our website, add the following <b>font awesome CDN code</b> in between the style tags of HTML page.

<pre>
<code>
&lt;link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"&gt;
</code>
</pre>

After you get up and running, you can place <b>Font Awesome icons</b> just about anywhere with the <span style="padding: 0px 5px; border-radius: 5px; color: black; background-color: #ff0;">&lt; i &gt;</span> tag.

<h3><strong>Basic Font awesome Icons</strong></h3>

You can place Font Awesome icons just about anywhere using the CSS Prefix <span style="padding: 0px 5px; border-radius: 5px; color: black; background-color: #ff0;">fa</span> and the icon's name. Font Awesome is designed to be used with inline elements (we like the <span style="padding: 0px 5px; border-radius: 5px; color: black; background-color: #ff0;">&lt; i &gt;</span> tag for brevity, but using a <span style="padding: 0px 5px; border-radius: 5px; color: black; background-color: #ff0;">span</span> is more semantically correct).

<pre><code>&lt;i class="fa fa-camera-retro"&gt;&lt;/i&gt; fa-camera-retro</code></pre>


<h3><strong>Larger Font Awesome Icons.</strong></h3>

To increase <b>icon</b> sizes relative to their container, use the <span style="padding: 0px 5px; border-radius: 5px; color: black; background-color: #ff0;">fa-lg</span> (33% increase), <span style="padding: 0px 5px; border-radius: 5px; color: black; background-color: #ff0;">fa-2x</span>,<span style="padding: 0px 5px; border-radius: 5px; color: black; background-color: #ff0;">fa-3x</span>,<span style="padding: 0px 5px; border-radius: 5px; color: black; background-color: #ff0;">fa-4x</span>, or <span style="padding: 0px 5px; border-radius: 5px; color: black; background-color: #ff0;">fa-5x</span>classes.

<pre>
<code>
&lt;i class="fa fa-camera-retro fa-lg"&gt;&lt;/i&gt; fa-lg <br>&lt;i class="fa fa-camera-retro fa-2x"&gt;&lt;/i&gt; fa-2x<br>&lt;i class="fa fa-camera-retro fa-3x"&gt;&lt;/i&gt; fa-3x<br>&lt;i class="fa fa-camera-retro fa-4x"&gt;&lt;/i&gt; fa-4x<br>&lt;i class="fa fa-camera-retro fa-5x"&gt;&lt;/i&gt; fa-5x<br></code></pre>

<h3><strong>Fixed Width Icons.</strong></h3>

Use <span style="padding: 0px 5px; border-radius: 5px; color: black; background-color: #ff0;">fa-fw</span> to set icons at a fixed width. Great to use when different icon widths throw off alignment. Especially useful in things like nav lists and list groups.

<pre>
<code style="text-align: left;">&lt;div class="list-group"&gt; <br>
&lt;a class="list-group-item" href="#"&gt;&lt;i class="fa fa-home fa-fw" aria-hidden="true"&gt;&lt;/i&gt;Home&lt;/a&gt; <br>
&lt;a class="list-group-item" href="#"&gt;&lt;i class="fa fa-book fa-fw" aria-hidden="true"&gt;&lt;/i&gt;Library&lt;/a&gt; <br>
&lt;a class="list-group-item" href="#"&gt;&lt;i class="fa fa-pencil fa-fw" aria-hidden="true"&gt;&lt;/i&gt;Applications&lt;/a&gt;<br>
&lt;a class="list-group-item" href="#"&gt;&lt;i class="fa fa-cog fa-fw" aria-hidden="true"&gt;&lt;/i&gt;Settings&lt;/a&gt;<br>
&lt;/div&gt;<br></code></pre>

{% include googlead3.html %}

<h2 id="font-awesome-icons-animation"><strong>Animated Font Awesome Icons.</strong></h2>

Here is the list of best <b>font awesome css animations</b> listed below. Click on the label to extend and copy the <b>css code</b> and use in your website.

<div class="accordion_container">
<div style="margin-bottom: 18px;">
<input type="checkbox" name="myaccordion" id="tab_one">
<label for="tab_one"> <span class="karna_span"><span>1. Wrench</span> <span><svg id="svg_animation_icon" viewbox="0 0 576 512"><path d="M12.971 352h32.394C67.172 454.735 181.944 512 288 512c106.229 0 220.853-57.38 242.635-160h32.394c10.691 0 16.045-12.926 8.485-20.485l-67.029-67.029c-4.686-4.686-12.284-4.686-16.971 0l-67.029 67.029c-7.56 7.56-2.206 20.485 8.485 20.485h35.146c-20.29 54.317-84.963 86.588-144.117 94.015V256h52c6.627 0 12-5.373 12-12v-40c0-6.627-5.373-12-12-12h-52v-5.47c37.281-13.178 63.995-48.725 64-90.518C384.005 43.772 341.605.738 289.37.01 235.723-.739 192 42.525 192 96c0 41.798 26.716 77.35 64 90.53V192h-52c-6.627 0-12 5.373-12 12v40c0 6.627 5.373 12 12 12h52v190.015c-58.936-7.399-123.82-39.679-144.117-94.015h35.146c10.691 0 16.045-12.926 8.485-20.485l-67.029-67.029c-4.686-4.686-12.284-4.686-16.971 0L4.485 331.515C-3.074 339.074 2.28 352 12.971 352zM288 64c17.645 0 32 14.355 32 32s-14.355 32-32 32-32-14.355-32-32 14.355-32 32-32z"/></svg></span> </span></label>
<div class="inside_container">
<p> <code2>@keyframes wrench {<br>0% {<br>-webkit-transform: rotate(-12deg);<br>transform: rotate(-12deg);<br>}<br>8% {<br>-webkit-transform: rotate(12deg);<br>transform: rotate(12deg);<br>}<br>10% {<br>-webkit-transform: rotate(24deg);<br>transform: rotate(24deg);<br>}<br>18% {<br>-webkit-transform: rotate(-24deg);<br>transform: rotate(-24deg);<br>}<br>20% {<br>-webkit-transform: rotate(-24deg);<br>transform: rotate(-24deg);<br>}<br>28% {<br>-webkit-transform: rotate(24deg);<br>transform: rotate(24deg);<br>}<br>30% {<br>-webkit-transform: rotate(24deg);<br>transform: rotate(24deg);<br>}<br>38% {<br>-webkit-transform: rotate(-24deg);<br>transform: rotate(-24deg);<br>}<br>40% {<br>-webkit-transform: rotate(-24deg);<br>transform: rotate(-24deg);<br>}<br>48% {<br>-webkit-transform: rotate(24deg);<br>transform: rotate(24deg);<br>}<br>50% {<br>-webkit-transform: rotate(24deg);<br>transform: rotate(24deg);<br>}<br>58% {<br>-webkit-transform: rotate(-24deg);<br>transform: rotate(-24deg);<br>}<br>60% {<br>-webkit-transform: rotate(-24deg);<br>transform: rotate(-24deg);<br>}<br>68% {<br>-webkit-transform: rotate(24deg);<br>transform: rotate(24deg);<br>}<br>75%, 100% {<br>-webkit-transform: rotate(0deg);<br>transform: rotate(0deg);<br>}<br>}<br></code2></p>
<svg id="inside_animation_icon" style="width: 60px; height: 60px; animation: wrench 4s infinite alternate;" fill="#00ff1d" viewBox="0 0 448 512">
<path d="M319.4 320.6L224 416l-95.4-95.4C57.1 323.7 0 382.2 0 454.4v9.6c0 26.5 21.5 48 48 48h352c26.5 0 48-21.5 48-48v-9.6c0-72.2-57.1-130.7-128.6-133.8zM13.6 79.8l6.4 1.5v58.4c-7 4.2-12 11.5-12 20.3 0 8.4 4.6 15.4 11.1 19.7L3.5 242c-1.7 6.9 2.1 14 7.6 14h41.8c5.5 0 9.3-7.1 7.6-14l-15.6-62.3C51.4 175.4 56 168.4 56 160c0-8.8-5-16.1-12-20.3V87.1l66 15.9c-8.6 17.2-14 36.4-14 57 0 70.7 57.3 128 128 128s128-57.3 128-128c0-20.6-5.3-39.8-14-57l96.3-23.2c18.2-4.4 18.2-27.1 0-31.5l-190.4-46c-13-3.1-26.7-3.1-39.7 0L13.6 48.2c-18.1 4.4-18.1 27.2 0 31.6z" /> </svg>
</div>
</div>
<div style="margin-bottom: 18px;">
<input type="checkbox" name="myaccordion" id="tab_two">
<label for="tab_two"> <span class="karna_span"><span>2. Ringing</span> <span><svg style="width: 40px; height: 40px; animation: ring 3s infinite alternate;" fill="white" viewbox="0 0 448 512"><path d="M224 512c35.32 0 63.97-28.65 63.97-64H160.03c0 35.35 28.65 64 63.97 64zm215.39-149.71c-19.32-20.76-55.47-51.99-55.47-154.29 0-77.7-54.48-139.9-127.94-155.16V32c0-17.67-14.32-32-31.98-32s-31.98 14.33-31.98 32v20.84C118.56 68.1 64.08 130.3 64.08 208c0 102.3-36.15 133.53-55.47 154.29-6 6.45-8.66 14.16-8.61 21.71.11 16.4 12.98 32 32.1 32h383.8c19.12 0 32-15.6 32.1-32 .05-7.55-2.61-15.27-8.61-21.71z"/></svg></span> </span></label>
<div class="inside_container">
<p><code2>@keyframes ring { <br>
		0% {<br>-webkit-transform: rotate(-15deg);<br>transform: rotate(-15deg);<br>}<br>2% {<br>-webkit-transform: rotate(15deg);<br>transform: rotate(15deg);<br>}<br>4% {<br>-webkit-transform: rotate(-18deg);<br>transform: rotate(-18deg);<br>}<br>6% {<br>-webkit-transform: rotate(18deg);<br>transform: rotate(18deg);<br>}<br>8% {<br>-webkit-transform: rotate(-22deg);<br>transform: rotate(-22deg);<br>}<br>10% {<br>-webkit-transform: rotate(22deg);<br>transform: rotate(22deg);<br>}<br>12% {<br>-webkit-transform: rotate(-18deg);<br>transform: rotate(-18deg);<br>}<br>14% {<br>-webkit-transform: rotate(18deg);<br>transform: rotate(18deg);<br>}<br>16% {<br>-webkit-transform: rotate(-12deg);<br>transform: rotate(-12deg);<br>}<br>18% {<br>-webkit-transform:rotate(12deg);<br>transform: rotate(12deg);<br>}<br>20%,100% {<br>-webkit-transform: rotate(0deg);<br>transform: rotate(0deg);<br>}<br>}<br></code2></p>
<svg id="inside_animation_icon" style="width: 60px; height: 60px; animation: ring 3s infinite alternate" fill="#2c33f0" viewBox="0 0 576 512">
<path d="M552 64H448V24c0-13.3-10.7-24-24-24H152c-13.3 0-24 10.7-24 24v40H24C10.7 64 0 74.7 0 88v56c0 35.7 22.5 72.4 61.9 100.7 31.5 22.7 69.8 37.1 110 41.7C203.3 338.5 240 360 240 360v72h-48c-35.3 0-64 20.7-64 56v12c0 6.6 5.4 12 12 12h296c6.6 0 12-5.4 12-12v-12c0-35.3-28.7-56-64-56h-48v-72s36.7-21.5 68.1-73.6c40.3-4.6 78.6-19 110-41.7 39.3-28.3 61.9-65 61.9-100.7V88c0-13.3-10.7-24-24-24zM99.3 192.8C74.9 175.2 64 155.6 64 144v-16h64.2c1 32.6 5.8 61.2 12.8 86.2-15.1-5.2-29.2-12.4-41.7-21.4zM512 144c0 16.1-17.7 36.1-35.3 48.8-12.5 9-26.7 16.2-41.8 21.4 7-25 11.8-53.6 12.8-86.2H512v16z" /> </svg>
</div>
</div>

{% include googlead1.html %}

<div style="margin-bottom: 18px;">
<input type="checkbox" name="myaccordion" id="tab_three">
<label for="tab_three"> <span class="karna_span"><span>3. Vertical</span><span><svg style="width: 40px; height: 40px; animation: vertical 3s infinite alternate;" fill="white" viewbox="0 0 640 512"><path d="M608 32H32C14.33 32 0 46.33 0 64v384c0 17.67 14.33 32 32 32h576c17.67 0 32-14.33 32-32V64c0-17.67-14.33-32-32-32zM176 327.88V344c0 4.42-3.58 8-8 8h-16c-4.42 0-8-3.58-8-8v-16.29c-11.29-.58-22.27-4.52-31.37-11.35-3.9-2.93-4.1-8.77-.57-12.14l11.75-11.21c2.77-2.64 6.89-2.76 10.13-.73 3.87 2.42 8.26 3.72 12.82 3.72h28.11c6.5 0 11.8-5.92 11.8-13.19 0-5.95-3.61-11.19-8.77-12.73l-45-13.5c-18.59-5.58-31.58-23.42-31.58-43.39 0-24.52 19.05-44.44 42.67-45.07V152c0-4.42 3.58-8 8-8h16c4.42 0 8 3.58 8 8v16.29c11.29.58 22.27 4.51 31.37 11.35 3.9 2.93 4.1 8.77.57 12.14l-11.75 11.21c-2.77 2.64-6.89 2.76-10.13.73-3.87-2.43-8.26-3.72-12.82-3.72h-28.11c-6.5 0-11.8 5.92-11.8 13.19 0 5.95 3.61 11.19 8.77 12.73l45 13.5c18.59 5.58 31.58 23.42 31.58 43.39 0 24.53-19.05 44.44-42.67 45.07zM416 312c0 4.42-3.58 8-8 8H296c-4.42 0-8-3.58-8-8v-16c0-4.42 3.58-8 8-8h112c4.42 0 8 3.58 8 8v16zm160 0c0 4.42-3.58 8-8 8h-80c-4.42 0-8-3.58-8-8v-16c0-4.42 3.58-8 8-8h80c4.42 0 8 3.58 8 8v16zm0-96c0 4.42-3.58 8-8 8H296c-4.42 0-8-3.58-8-8v-16c0-4.42 3.58-8 8-8h272c4.42 0 8 3.58 8 8v16z"/></svg></span> </span></label>
<div class="inside_container">
<p><code2>@keyframes vertical { <br>0% {<br>-webkit-transform: translate(0,-3px);<br>transform: translate(0,-3px);<br>}<br>4% {<br>-webkit-transform: translate(0,3px);<br>transform: translate(0,3px);<br>}<br>8% {<br>-webkit-transform: translate(0,-3px);<br>transform: translate(0,-3px);<br>}<br>12% {<br>-webkit-transform: translate(0,3px);<br>transform: translate(0,3px);<br>}<br>16% {<br>-webkit-transform: translate(0,-3px);<br>transform: translate(0,-3px);<br>}<br>20% {<br>-webkit-transform: translate(0,3px);<br>transform: translate(0,3px);<br>}<br>22%, 100% {<br>-webkit-transform: translate(0,0);<br>transform: translate(0,0);<br>}<br>}<br></code2></p>
<svg id="inside_animation_icon" style="width: 60px; height: 60px; animation: vertical 3s infinite alternate;" fill="black" viewBox="0 0 384 512">
<path d="M135.652 0c23.625 0 43.826 20.65 43.826 44.8v99.851c17.048-16.34 49.766-18.346 70.944 6.299 22.829-14.288 53.017-2.147 62.315 16.45C361.878 158.426 384 189.346 384 240c0 2.746-.203 13.276-.195 16 .168 61.971-31.065 76.894-38.315 123.731C343.683 391.404 333.599 400 321.786 400H150.261l-.001-.002c-18.366-.011-35.889-10.607-43.845-28.464C93.421 342.648 57.377 276.122 29.092 264 10.897 256.203.008 242.616 0 224c-.014-34.222 35.098-57.752 66.908-44.119 8.359 3.583 16.67 8.312 24.918 14.153V44.8c0-23.45 20.543-44.8 43.826-44.8zM136 416h192c13.255 0 24 10.745 24 24v48c0 13.255-10.745 24-24 24H136c-13.255 0-24-10.745-24-24v-48c0-13.255 10.745-24 24-24zm168 28c-11.046 0-20 8.954-20 20s8.954 20 20 20 20-8.954 20-20-8.954-20-20-20z" /> </svg>
</div>
</div>
<div style="margin-bottom: 18px;">
<input type="checkbox" name="myaccordion" id="tab_four">
<label for="tab_four"> <span class="karna_span"><span>4. Horizontal</span><span style="margin-left: -20px;"><svg style="width: 40px; height: 40px; animation: horizontal 3s infinite;" fill="white" viewbox="0 0 640 512"><path d="M512.509 192.001c-16.373-.064-32.03 2.955-46.436 8.495l-77.68-125.153A24 24 0 0 0 368.001 64h-64c-8.837 0-16 7.163-16 16v16c0 8.837 7.163 16 16 16h50.649l14.896 24H256.002v-16c0-8.837-7.163-16-16-16h-87.459c-13.441 0-24.777 10.999-24.536 24.437.232 13.044 10.876 23.563 23.995 23.563h48.726l-29.417 47.52c-13.433-4.83-27.904-7.483-42.992-7.52C58.094 191.83.412 249.012.002 319.236-.413 390.279 57.055 448 128.002 448c59.642 0 109.758-40.793 123.967-96h52.033a24 24 0 0 0 20.406-11.367L410.37 201.77l14.938 24.067c-25.455 23.448-41.385 57.081-41.307 94.437.145 68.833 57.899 127.051 126.729 127.719 70.606.685 128.181-55.803 129.255-125.996 1.086-70.941-56.526-129.72-127.476-129.996zM186.75 265.772c9.727 10.529 16.673 23.661 19.642 38.228h-43.306l23.664-38.228zM128.002 400c-44.112 0-80-35.888-80-80s35.888-80 80-80c5.869 0 11.586.653 17.099 1.859l-45.505 73.509C89.715 331.327 101.213 352 120.002 352h81.3c-12.37 28.225-40.562 48-73.3 48zm162.63-96h-35.624c-3.96-31.756-19.556-59.894-42.383-80.026L237.371 184h127.547l-74.286 120zm217.057 95.886c-41.036-2.165-74.049-35.692-75.627-76.755-.812-21.121 6.633-40.518 19.335-55.263l44.433 71.586c4.66 7.508 14.524 9.816 22.032 5.156l13.594-8.437c7.508-4.66 9.817-14.524 5.156-22.032l-44.468-71.643a79.901 79.901 0 0 1 19.858-2.497c44.112 0 80 35.888 80 80-.001 45.54-38.252 82.316-84.313 79.885z"/></svg>
</span> </span></label>
<div class="inside_container">
<p><code2>@keyframes horizontal { <br>0% {<br>-webkit-transform: translate(0,0);<br>transform: translate(0,0);<br>}<br>6% {<br>-webkit-transform: translate(5px,0);<br>transform: translate(5px,0);<br>}<br>12% {<br>-webkit-transform: translate(0,0);<br>transform: translate(0,0);<br>}<br>18% {<br>-webkit-transform: translate(5px,0);<br>transform: translate(5px,0);<br>}<br>24% {<br>-webkit-transform: translate(0,0);<br>transform: translate(0,0);<br>}<br>30% {<br>-webkit-transform: translate(5px,0);<br>transform: translate(5px,0);<br>}<br>36%, 100% {<br>-webkit-transform: translate(0,0);<br>transform: translate(0,0);<br>}<br>}<br></code2></p>
<svg id="inside_animation_icon" style="width: 60px; height: 60px; animation: horizontal 2s infinite alternate-reverse;" fill="red" viewBox="0 0 576 512">
<path d="M528 0H48C21.5 0 0 21.5 0 48v320c0 26.5 21.5 48 48 48h192l-16 48h-72c-13.3 0-24 10.7-24 24s10.7 24 24 24h272c13.3 0 24-10.7 24-24s-10.7-24-24-24h-72l-16-48h192c26.5 0 48-21.5 48-48V48c0-26.5-21.5-48-48-48zm-16 352H64V64h448v288z" /> </svg>
</div>
</div>
<div style="margin-bottom: 18px;">
<input type="checkbox" name="myaccordion" id="tab_five">
<label for="tab_five"> <span class="karna_span"><span>5. Flashing</span><span><svg style="width: 40px; height: 40px; animation: flash 4s infinite alternate;" fill="white" viewbox="0 0 384 512"><path d="M272 428v28c0 10.449-6.68 19.334-16 22.629V488c0 13.255-10.745 24-24 24h-80c-13.255 0-24-10.745-24-24v-9.371c-9.32-3.295-16-12.18-16-22.629v-28c0-6.627 5.373-12 12-12h136c6.627 0 12 5.373 12 12zm-143.107-44c-9.907 0-18.826-6.078-22.376-15.327C67.697 267.541 16 277.731 16 176 16 78.803 94.805 0 192 0s176 78.803 176 176c0 101.731-51.697 91.541-90.516 192.673-3.55 9.249-12.47 15.327-22.376 15.327H128.893zM112 176c0-44.112 35.888-80 80-80 8.837 0 16-7.164 16-16s-7.163-16-16-16c-61.757 0-112 50.243-112 112 0 8.836 7.164 16 16 16s16-7.164 16-16z"/></svg></span></span>
</label>
<div class="inside_container" style="max-height: 380px;">
<p><code2>@-webkit-keyframes flash {<br>0%, 100%, 50% {<br>opacity: 1;<br>}<br>25%, 75%{<br>opacity: 0;<br>}<br>}<br>@keyframes flash {<br>0%, 100%, 50% {<br>opacity: 1;<br>}<br>25%, 75% {<br>opacity: 0;<br>}<br>}<br></code2></p>
<svg id="inside_animation_icon" style="width: 60px; height: 60px; animation: flash 5s infinite alternate" fill="#2f1d95" viewBox="0 0 448 512">
<path d="M319.5 114.7c-22.2-14-43.5-19.5-64.7-33.5-13-8.8-31.3-30-46.5-48.3-2.7 29.3-11.5 41.2-22 49.5-21.3 17-34.8 22.2-53.5 32.3C117 123 32 181.5 32 290.5 32 399.7 123.8 480 225.8 480 327.5 480 416 406 416 294c0-112.3-83-171-96.5-179.3zm2.5 325.6c-20.1 20.1-90.1 28.7-116.7 4.2-4.8-4.8.3-12 6.5-12 0 0 17 13.3 51.5 13.3 27 0 46-7.7 54.5-14 6.1-4.6 8.4 4.3 4.2 8.5zm-54.5-52.6c8.7-3.6 29-3.8 36.8 1.3 4.1 2.8 16.1 18.8 6.2 23.7-8.4 4.2-1.2-15.7-26.5-15.7-14.7 0-19.5 5.2-26.7 11-7 6-9.8 8-12.2 4.7-6-8.2 15.9-22.3 22.4-25zM360 405c-15.2-1-45.5-48.8-65-49.5-30.9-.9-104.1 80.7-161.3 42-38.8-26.6-14.6-104.8 51.8-105.2 49.5-.5 83.8 49 108.5 48.5 21.3-.3 61.8-41.8 81.8-41.8 48.7 0 23.3 109.3-15.8 106z" /> </svg>
</div>
</div>

{% include googlead2.html %}

<div style="margin-bottom: 18px;">
<input type="checkbox" name="myaccordion" id="tab_six">
<label for="tab_six"> <span class="karna_span"><span>6. Bouncing</span><span><svg style="width: 40px; height: 40px; animation: bounce 4s infinite alternate;" fill="white" viewbox="0 0 512 512"><path d="M367.9 329.76c-4.62 5.3-9.78 10.1-15.9 13.65v22.94c66.52 9.34 112 28.05 112 49.65 0 30.93-93.12 56-208 56S48 446.93 48 416c0-21.6 45.48-40.3 112-49.65v-22.94c-6.12-3.55-11.28-8.35-15.9-13.65C58.87 345.34 0 378.05 0 416c0 53.02 114.62 96 256 96s256-42.98 256-96c0-37.95-58.87-70.66-144.1-86.24zM256 128c35.35 0 64-28.65 64-64S291.35 0 256 0s-64 28.65-64 64 28.65 64 64 64zm-64 192v96c0 17.67 14.33 32 32 32h64c17.67 0 32-14.33 32-32v-96c17.67 0 32-14.33 32-32v-96c0-26.51-21.49-48-48-48h-11.8c-11.07 5.03-23.26 8-36.2 8s-25.13-2.97-36.2-8H208c-26.51 0-48 21.49-48 48v96c0 17.67 14.33 32 32 32z"/></svg></span></span>
</label>
<div class="inside_container" style="max-height: 330px;">
	<p><code2>@keyframes bounce {<br>0%, 10%, 20%, 50%, 80%, 100% {<br>-webkit-transform:translateY(0);<br>transform: translateY(0);<br>}<br>40% {<br>-webkit-transform:translateY(-15px);<br>transform: translateY(-15px);<br>}<br>60% {<br>-webkit-transform: translateY(-15px);<br>transform: translateY(-15px);<br>}<br>}<br></code2></p>
<svg id="inside_animation_icon" style="width: 60px; height: 60px; animation: bounce 6s infinite alternate;" fill="#000205" viewBox="0 0 352 512">
<path d="M205.22 22.09c-7.94-28.78-49.44-30.12-58.44 0C100.01 179.85 0 222.72 0 333.91 0 432.35 78.72 512 176 512s176-79.65 176-178.09c0-111.75-99.79-153.34-146.78-311.82zM176 448c-61.75 0-112-50.25-112-112 0-8.84 7.16-16 16-16s16 7.16 16 16c0 44.11 35.89 80 80 80 8.84 0 16 7.16 16 16s-7.16 16-16 16z" /> </svg>
</div>
</div>
<div style="margin-bottom: 18px;">
<input type="checkbox" name="myaccordion" id="tab_seven">
<label for="tab_seven"> <span class="karna_span"><span>7. Spinner..</span><span><svg style="width: 40px; height: 40px; animation: spin 3s infinite;" fill="white" viewbox="0 0 512 512"><path d="M274.835 12.646l25.516 62.393c4.213 10.301 16.671 14.349 26.134 8.492l57.316-35.479c15.49-9.588 34.808 4.447 30.475 22.142l-16.03 65.475c-2.647 10.81 5.053 21.408 16.152 22.231l67.224 4.987c18.167 1.348 25.546 24.057 11.641 35.826L441.81 242.26c-8.495 7.19-8.495 20.289 0 27.479l51.454 43.548c13.906 11.769 6.527 34.478-11.641 35.826l-67.224 4.987c-11.099.823-18.799 11.421-16.152 22.231l16.03 65.475c4.332 17.695-14.986 31.73-30.475 22.142l-57.316-35.479c-9.463-5.858-21.922-1.81-26.134 8.492l-25.516 62.393c-6.896 16.862-30.774 16.862-37.67 0l-25.516-62.393c-4.213-10.301-16.671-14.349-26.134-8.492l-57.317 35.479c-15.49 9.588-34.808-4.447-30.475-22.142l16.03-65.475c2.647-10.81-5.053-21.408-16.152-22.231l-67.224-4.987c-18.167-1.348-25.546-24.057-11.641-35.826L70.19 269.74c8.495-7.19 8.495-20.289 0-27.479l-51.454-43.548c-13.906-11.769-6.527-34.478 11.641-35.826l67.224-4.987c11.099-.823 18.799-11.421 16.152-22.231l-16.03-65.475c-4.332-17.695 14.986-31.73 30.475-22.142l57.317 35.479c9.463 5.858 21.921 1.81 26.134-8.492l25.516-62.393c6.896-16.861 30.774-16.861 37.67 0zM392 256c0-74.991-61.01-136-136-136-74.991 0-136 61.009-136 136s61.009 136 136 136c74.99 0 136-61.009 136-136zm-32 0c0 57.346-46.654 104-104 104s-104-46.654-104-104 46.654-104 104-104 104 46.654 104 104z"/></svg></span></span>
</label>
<div class="inside_container" style="max-height: 260px;">
	<p><code2>@keyframes spin {<br>0% {<br>-webkit-transform: rotate(0deg);<br>transform: rotate(0deg);<br>}<br>100% {<br>-webkit-transform: rotate(359deg);<br>transform: rotate(359deg);<br>}<br>}<br></code2></p>
<svg id="inside_animation_icon" style="width: 50px; height: 50px; animation: spin 2s infinite;" fill="black" viewBox="0 0 512 512">
<path d="M504 256c0 136.967-111.033 248-248 248S8 392.967 8 256 119.033 8 256 8s248 111.033 248 248zm-48 0l-.003-.282-26.064 22.741-62.679-58.5 16.454-84.355 34.303 3.072c-24.889-34.216-60.004-60.089-100.709-73.141l13.651 31.939L256 139l-74.953-41.525 13.651-31.939c-40.631 13.028-75.78 38.87-100.709 73.141l34.565-3.073 16.192 84.355-62.678 58.5-26.064-22.741-.003.282c0 43.015 13.497 83.952 38.472 117.991l7.704-33.897 85.138 10.447 36.301 77.826-29.902 17.786c40.202 13.122 84.29 13.148 124.572 0l-29.902-17.786 36.301-77.826 85.138-10.447 7.704 33.897C442.503 339.952 456 299.015 456 256zm-248.102 69.571l-29.894-91.312L256 177.732l77.996 56.527-29.622 91.312h-96.476z" /> </svg>
	</div></div>
<div style="margin-bottom: 18px;">
<input type="checkbox" name="myaccordion" id="tab_eight">
<label for="tab_eight"> <span class="karna_span"><span>8. FloatIng.</span><span><svg style="width: 40px; height: 40px; animation: float .5s infinite" fill="white" viewbox="0 0 496 512"><path d="M368.5 363.9l28.8-13.9c11.1 22.9 26 43.2 44.1 60.9 34-42.5 54.5-96.3 54.5-154.9 0-58.5-20.4-112.2-54.2-154.6-17.8 17.3-32.6 37.1-43.6 59.5l-28.7-14.1c12.8-26 30-49 50.8-69C375.6 34.7 315 8 248 8 181.1 8 120.5 34.6 75.9 77.7c20.7 19.9 37.9 42.9 50.7 68.8l-28.7 14.1c-11-22.3-25.7-42.1-43.5-59.4C20.4 143.7 0 197.4 0 256c0 58.6 20.4 112.3 54.4 154.7 18.2-17.7 33.2-38 44.3-61l28.8 13.9c-12.9 26.7-30.3 50.3-51.5 70.7 44.5 43.1 105.1 69.7 172 69.7 66.8 0 127.3-26.5 171.9-69.5-21.1-20.4-38.5-43.9-51.4-70.6zm-228.3-32l-30.5-9.8c14.9-46.4 12.7-93.8-.6-134l30.4-10c15 45.6 18 99.9.7 153.8zm216.3-153.4l30.4 10c-13.2 40.1-15.5 87.5-.6 134l-30.5 9.8c-17.3-54-14.3-108.3.7-153.8z"/></svg></span></span>
</label>
<div class="inside_container" style="max-height: 330px;">
<p><code2>@keyframes float {<br>0% {<br>-webkit-transform: translateY(0);<br>transform: translateY(0);<br>}<br>50% {<br>-webkit-transform: translateY(-6px);<br>transform: translateY(-6px);<br>}<br>100% {<br>-webkit-transform: translateY(0);<br>transform: translateY(0);<br>}<br>}<br></code2></p>
<svg id="inside_animation_icon" style="width: 60px; height: 60px; animation: float .8s infinite alternate;" fill="#F3130E" viewBox="0 0 496 512">
<path d="M481.5 60.3c-4.8-18.2-19.1-32.5-37.3-37.4C420.3 16.5 383 8.9 339.4 8L496 164.8c-.8-43.5-8.2-80.6-14.5-104.5zm-467 391.4c4.8 18.2 19.1 32.5 37.3 37.4 23.9 6.4 61.2 14 104.8 14.9L0 347.2c.8 43.5 8.2 80.6 14.5 104.5zM4.2 283.4L220.4 500c132.5-19.4 248.8-118.7 271.5-271.4L275.6 12C143.1 31.4 26.8 130.7 4.2 283.4zm317.3-123.6c3.1-3.1 8.2-3.1 11.3 0l11.3 11.3c3.1 3.1 3.1 8.2 0 11.3l-28.3 28.3 28.3 28.3c3.1 3.1 3.1 8.2 0 11.3l-11.3 11.3c-3.1 3.1-8.2 3.1-11.3 0l-28.3-28.3-22.6 22.7 28.3 28.3c3.1 3.1 3.1 8.2 0 11.3l-11.3 11.3c-3.1 3.1-8.2 3.1-11.3 0L248 278.6l-22.6 22.6 28.3 28.3c3.1 3.1 3.1 8.2 0 11.3l-11.3 11.3c-3.1 3.1-8.2 3.1-11.3 0l-28.3-28.3-28.3 28.3c-3.1 3.1-8.2 3.1-11.3 0l-11.3-11.3c-3.1-3.1-3.1-8.2 0-11.3l28.3-28.3-28.3-28.2c-3.1-3.1-3.1-8.2 0-11.3l11.3-11.3c3.1-3.1 8.2-3.1 11.3 0l28.3 28.3 22.6-22.6-28.3-28.3c-3.1-3.1-3.1-8.2 0-11.3l11.3-11.3c3.1-3.1 8.2-3.1 11.3 0l28.3 28.3 22.6-22.6-28.3-28.3c-3.1-3.1-3.1-8.2 0-11.3l11.3-11.3c3.1-3.1 8.2-3.1 11.3 0l28.3 28.3 28.3-28.5z" /> </svg>
</div>
</div>
<div style="margin-bottom: 18px;">
<input type="checkbox" name="myaccordion" id="tab_nine">
<label for="tab_nine"> <span class="karna_span"><span>9. Pulse......!</span><span><svg style="width: 40px; height: 40px; animation: pulse .5s infinite;" fill="white"  viewbox="0 0 512 512"><path d="M462.3 62.6C407.5 15.9 326 24.3 275.7 76.2L256 96.5l-19.7-20.3C186.1 24.3 104.5 15.9 49.7 62.6c-62.8 53.6-66.1 149.8-9.9 207.9l193.5 199.8c12.5 12.9 32.8 12.9 45.3 0l193.5-199.8c56.3-58.1 53-154.3-9.8-207.9z"/></svg></span></span>
</label>
<div class="inside_container" style="max-height: 350px;">
<p><code2>@keyframes pulse { <br>0% {<br>-webkit-transform: scale(1.1);<br>transform: scale(1.1);<br>}<br>50% {<br>-webkit-transform: scale(0.8);<br>transform: scale(0.8);<br>
  }<br>100% {<br>-webkit-transform: scale(1.1);<br>transform: scale(1.1);<br>}<br>}<br></code2> </p>
<svg id="inside_animation_icon" style="width: 40px; height: 40px; animation: pulse .7s infinite;" fill="black" viewBox="0 0 504 512">
<path d="M501.1 402.5c-8-20.8-31.5-31.5-53.1-25.9l-8.4 2.2-2.3-8.4c-5.9-21.4-27-36.5-49-33-25.2 4-40.6 28.6-34 52.6l22.9 82.6c1.5 5.3 7 8.5 12.4 7.1l83-21.5c24.1-6.3 37.7-31.8 28.5-55.7zm-177.6-4c-5.6-20.3-2.3-42 9-59.7 29.7-46.3 98.7-45.5 127.8 4.3 6.4.1 12.6 1.4 18.6 2.9 10.9-27.9 17.1-58.2 17.1-90C496 119 385 8 248 8S0 119 0 256s111 248 248 248c35.4 0 68.9-7.5 99.4-20.9-.3-.7-23.9-84.6-23.9-84.6zM168 240c-17.7 0-32-14.3-32-32s14.3-32 32-32 32 14.3 32 32-14.3 32-32 32zm120 156c0 19.2-28.7 41.5-71.5 44-8.5.8-12.1-11.8-3.6-15.4l17-7.2c13-5.5 20.8-13.5 20.8-21.5s-7.8-16-20.8-21.5l-17-7.2c-6-2.5-5.7-12.3 0-14.8l17-7.2c13-5.5 20.8-13.5 20.8-21.5s-7.8-16-20.8-21.5l-17-7.2c-8.8-3.7-4.6-16.6 3.6-15.4 42.8 2.5 71.5 24.8 71.5 44 0 13-13.4 27.3-35.2 36C274.6 368.7 288 383 288 396zm16-179c-8.3 7.4-21.6.4-19.8-10.8 4-25.2 34.2-42.1 59.9-42.1S400 181 404 206.2c1.7 11.1-11.3 18.3-19.8 10.8l-9.5-8.5c-14.8-13.2-46.2-13.2-61 0L304 217z" /> </svg>
</div>
</div>
<div style="margin-bottom: 18px;">
<input type="checkbox" name="myaccordion" id="tab_ten">
<label for="tab_ten"> <span class="karna_span"><span>10. TaDa......!</span><span>
<svg style="width: 40px; height: 40px; animation: tada 3s infinite;" fill="white"  viewbox="0 0 512 512"><path d="M502.3 190.8c3.9-3.1 9.7-.2 9.7 4.7V400c0 26.5-21.5 48-48 48H48c-26.5 0-48-21.5-48-48V195.6c0-5 5.7-7.8 9.7-4.7 22.4 17.4 52.1 39.5 154.1 113.6 21.1 15.4 56.7 47.8 92.2 47.6 35.7.3 72-32.8 92.3-47.6 102-74.1 131.6-96.3 154-113.7zM256 320c23.2.4 56.6-29.2 73.4-41.4 132.7-96.3 142.8-104.7 173.4-128.7 5.8-4.5 9.2-11.5 9.2-18.9v-19c0-26.5-21.5-48-48-48H48C21.5 64 0 85.5 0 112v19c0 7.4 3.4 14.3 9.2 18.9 30.6 23.9 40.7 32.4 173.4 128.7 16.8 12.2 50.2 41.8 73.4 41.4z"/></svg></span></span>
</label>
<div class="inside_container" style="max-height: 450px;">
<p><code2>@keyframes tada {<br>0% {<br>-webkit-transform: scale(1);<br>transform: scale(1);<br>}<br>10%, 20% {<br>-webkit-transform: scale(.9) rotate(-8deg);<br>transform: scale(.9) rotate(-8deg);<br>}<br>30%, 50%, 70% {<br>-webkit-transform: scale(1.3) rotate(8deg);<br>
    transform: scale(1.3) rotate(8deg);<br>}<br>40%, 60% {<br>-webkit-transform: scale(1.3) rotate(-8deg);<br>transform: scale(1.3) rotate(-8deg);<br>}<br>80%, 100% {<br>-webkit-transform: scale(1) rotate(0);<br>transform: scale(1) rotate(0);<br>}<br>}<br></code2> </p>
<svg id="inside_animation_icon" style="width: 60px; height: 60px; animation: tada 3s infinite" fill="#CC0F40" viewBox="0 0 512 512">
<path d="M512 464c0 26.51-21.49 48-48 48H48c-26.51 0-48-21.49-48-48V200.724a48 48 0 0 1 18.387-37.776c24.913-19.529 45.501-35.365 164.2-121.511C199.412 29.17 232.797-.347 256 .003c23.198-.354 56.596 29.172 73.413 41.433 118.687 86.137 139.303 101.995 164.2 121.512A48 48 0 0 1 512 200.724V464zm-65.666-196.605c-2.563-3.728-7.7-4.595-11.339-1.907-22.845 16.873-55.462 40.705-105.582 77.079-16.825 12.266-50.21 41.781-73.413 41.43-23.211.344-56.559-29.143-73.413-41.43-50.114-36.37-82.734-60.204-105.582-77.079-3.639-2.688-8.776-1.821-11.339 1.907l-9.072 13.196a7.998 7.998 0 0 0 1.839 10.967c22.887 16.899 55.454 40.69 105.303 76.868 20.274 14.781 56.524 47.813 92.264 47.573 35.724.242 71.961-32.771 92.263-47.573 49.85-36.179 82.418-59.97 105.303-76.868a7.998 7.998 0 0 0 1.839-10.967l-9.071-13.196z" /> </svg>
</div>
</div>

{% include googlead3.html %}

<div style="margin-bottom: 18px;">
<input type="checkbox" name="myaccordion" id="tab_eleven">
<label for="tab_eleven"> <span class="karna_span"><span>11. PassIng.</span><span><svg style="width: 40px; height: 40px; animation: passing 3s infinite;" fill="white" viewbox="0 0 640 512"><path d="M592.604 208.244C559.735 192.836 515.777 184 472 184H186.327c-4.952-6.555-10.585-11.978-16.72-16H376C229.157 137.747 219.403 32 96.003 32H96v128H80V32c-26.51 0-48 28.654-48 64v64c-23.197 0-32 10.032-32 24v40c0 13.983 8.819 24 32 24v16c-23.197 0-32 10.032-32 24v40c0 13.983 8.819 24 32 24v64c0 35.346 21.49 64 48 64V352h16v128h.003c123.4 0 133.154-105.747 279.997-136H169.606c6.135-4.022 11.768-9.445 16.72-16H472c43.777 0 87.735-8.836 120.604-24.244C622.282 289.845 640 271.992 640 256s-17.718-33.845-47.396-47.756zM488 296a8 8 0 0 1-8-8v-64a8 8 0 0 1 8-8c31.909 0 31.942 80 0 80z"/></svg></span></span>
</label>
<div class="inside_container" style="max-height: 390px;">
	<p><code2>@keyframes passing {<br>0% {<br>-webkit-transform: translateX(-50%);<br>transform: translateX(-50%);<br>opacity: 0;<br>}<br>50% {<br>-webkit-transform: translateX(0%);<br>transform: translateX(0%);<br>opacity: 1;<br>}<br>100% {<br>-webkit-transform: translateX(50%);<br>transform: translateX(50%);<br>opacity: 0;<br>}<br>}<br></code2></p>
<svg id="inside_animation_icon" style="width: 60px; height: 60px; animation: passing 2s infinite;" fill="black" viewbox="0 0 640 512">
<path d="M544 224l-128-16-48-16h-24L227.158 44h39.509C278.333 44 288 41.375 288 38s-9.667-6-21.333-6H152v12h16v164h-48l-66.667-80H18.667L8 138.667V208h8v16h48v2.666l-64 8v42.667l64 8V288H16v16H8v69.333L18.667 384h34.667L120 304h48v164h-16v12h114.667c11.667 0 21.333-2.625 21.333-6s-9.667-6-21.333-6h-39.509L344 320h24l48-16 128-16c96-21.333 96-26.583 96-32 0-5.417 0-10.667-96-32z" /> </svg>
</div>
</div>
<div style="margin-bottom: 18px;">
<input type="checkbox" name="myaccordion" id="tab_twelve">
<label for="tab_twelve"> <span class="karna_span"><span>12. ~~ReverSe.</span><span><svg style="width: 40px; height: 40px; animation: passing-reverse 2s infinite;" fill="white" viewbox="0 0 448 512"><path d="M257.5 445.1l-22.2 22.2c-9.4 9.4-24.6 9.4-33.9 0L7 273c-9.4-9.4-9.4-24.6 0-33.9L201.4 44.7c9.4-9.4 24.6-9.4 33.9 0l22.2 22.2c9.5 9.5 9.3 25-.4 34.3L136.6 216H424c13.3 0 24 10.7 24 24v32c0 13.3-10.7 24-24 24H136.6l120.5 114.8c9.8 9.3 10 24.8.4 34.3z"/></svg></span></span>
</label>
<div class="inside_container" style="max-height: 390px;">
<p><code2>@keyframes passing-reverse { <br>0% {<br>-webkit-transform: translateX(50%);<br>
    transform: translateX(50%);<br>opacity: 0;<br>}<br>50% {<br>-webkit-transform: translateX(0%);<br>transform: translateX(0%);<br>opacity: 1;<br>}<br>100% {<br>-webkit-transform: translateX(-50%);<br>transform: translateX(-50%);<br>opacity: 0;<br>}<br>}<br>
	</code2></p>
<svg id="inside_animation_icon" style="width: 60px; height: 60px; animation: passing-reverse 3s infinite;" fill="black" viewBox="0 0 448 512">
<path d="M134.059 296H436c6.627 0 12-5.373 12-12v-56c0-6.627-5.373-12-12-12H134.059v-46.059c0-21.382-25.851-32.09-40.971-16.971L7.029 239.029c-9.373 9.373-9.373 24.569 0 33.941l86.059 86.059c15.119 15.119 40.971 4.411 40.971-16.971V296z" /> </svg>
</div>
</div>
<div style="margin-bottom: 18px;">
<input type="checkbox" name="myaccordion" id="tab_thirteen">
<label for="tab_thirteen"> <span class="karna_span"><span>13. Burst...!</span><span><svg style="width: 40px; height: 40px; animation: burst 2s infinite;" fill="white" viewbox="0 0 512 512"><path d="M256 8C119 8 8 119 8 256s111 248 248 248 248-111 248-248S393 8 256 8z"/></svg></span></span>
</label>
<div class="inside_container" style="max-height: 320px;">
<p><code2>@keyframes burst { <br>0% {<br>opacity: .6;<br>}<br>50% {<br>-webkit-transform:scale(1.8);<br>transform: scale(1.8);<br>opacity: 0;<br>}<br>100% {<br>opacity: 0;<br>}<br>}<br></code2></p>
<svg id="inside_animation_icon" style="width: 60px; height: 60px; animation: burst 3s infinite;" fill="red" viewBox="0 0 512 512">
<path d="M256 56c110.532 0 200 89.451 200 200 0 110.532-89.451 200-200 200-110.532 0-200-89.451-200-200 0-110.532 89.451-200 200-200m0-48C119.033 8 8 119.033 8 256s111.033 248 248 248 248-111.033 248-248S392.967 8 256 8zm0 168c-44.183 0-80 35.817-80 80s35.817 80 80 80 80-35.817 80-80-35.817-80-80-80z" /> </svg>
</div>
</div>
<div style="margin-bottom: 18px;">
<input type="checkbox" name="myaccordion" id="tab_fourteen">
<label for="tab_fourteen"> <span class="karna_span"><span>14. Falling...</span><span>
<svg style="width: 40px; height: 40px; animation: falling 2s infinite;" fill="white" viewbox="0 0 576 512"><path d="M259.3 17.8L194 150.2 47.9 171.5c-26.2 3.8-36.7 36.1-17.7 54.6l105.7 103-25 145.5c-4.5 26.3 23.2 46 46.4 33.7L288 439.6l130.7 68.7c23.2 12.2 50.9-7.4 46.4-33.7l-25-145.5 105.7-103c19-18.5 8.5-50.8-17.7-54.6L382 150.2 316.7 17.8c-11.7-23.6-45.6-23.9-57.4 0z"/></svg></span></span>
</label>
<div class="inside_container" style="max-height: 390px;">
<p><code2>@keyframes falling { <br>
  0% {<br>-webkit-transform: translateY(-50%);<br>transform: translateY(-50%);<br>opacity: 0;<br>
							}<br>50% {<br>-webkit-transform: translateY(0%);<br>transform: translateY(0%);<br>opacity: 1;<br>}<br>100% {<br>-webkit-transform: translateY(50%);<br>transform: translateY(50%);<br>opacity: 0;<br>}<br>}<br></code2></p>
<svg id="inside_animation_icon" style="width: 60px; height: 60px; animation: falling 4s infinite;" fill="blue" viewBox="0 0 496 512">
<path d="M248 8C111 8 0 119 0 256s111 248 248 248 248-111 248-248S385 8 248 8zM94.6 168.9l34.9-5 15.5-31.6c2.9-5.8 11-5.8 13.9 0l15.5 31.6 34.9 5c6.2 1 8.9 8.6 4.3 13.2l-25.4 24.6 6 34.9c1 6.2-5.3 11-11 7.9L152 233.3l-31.3 16.3c-5.7 3.1-12-1.7-11-7.9l6-34.9-25.4-24.6c-4.6-4.7-1.9-12.3 4.3-13.3zM248 432c-60.6 0-134.5-38.3-143.8-93.3-2-11.8 9.3-21.5 20.7-17.9C155.1 330.5 200 336 248 336s92.9-5.5 123.1-15.2c11.5-3.7 22.6 6.1 20.7 17.9-9.3 55-83.2 93.3-143.8 93.3zm157.7-249.9l-25.4 24.6 6 34.9c1 6.2-5.3 11-11 7.9L344 233.3l-31.3 16.3c-5.7 3.1-12-1.7-11-7.9l6-34.9-25.4-24.6c-4.5-4.6-1.9-12.2 4.3-13.2l34.9-5 15.5-31.6c2.9-5.8 11-5.8 13.9 0l15.5 31.6 34.9 5c6.3.9 9 8.5 4.4 13.1z" /> </svg>
</div>
</div>

{% include googlead4.html %}

<div style="margin-bottom: 18px;">
<input type="checkbox" name="myaccordion" id="tab_fifteen">
<label for="tab_fifteen"> <span class="karna_span"><span>15. TinUpOut.</span><span>
<svg style="width: 40px; height: 40px; animation: tinUpOut 4s infinite;" fill="white" viewbox="0 0 512 512"><path d="M511.988 288.9c-.478 17.43-15.217 31.1-32.653 31.1H424v16c0 21.864-4.882 42.584-13.6 61.145l60.228 60.228c12.496 12.497 12.496 32.758 0 45.255-12.498 12.497-32.759 12.496-45.256 0l-54.736-54.736C345.886 467.965 314.351 480 280 480V236c0-6.627-5.373-12-12-12h-24c-6.627 0-12 5.373-12 12v244c-34.351 0-65.886-12.035-90.636-32.108l-54.736 54.736c-12.498 12.497-32.759 12.496-45.256 0-12.496-12.497-12.496-32.758 0-45.255l60.228-60.228C92.882 378.584 88 357.864 88 336v-16H32.666C15.23 320 .491 306.33.013 288.9-.484 270.816 14.028 256 32 256h56v-58.745l-46.628-46.628c-12.496-12.497-12.496-32.758 0-45.255 12.498-12.497 32.758-12.497 45.256 0L141.255 160h229.489l54.627-54.627c12.498-12.497 32.758-12.497 45.256 0 12.496 12.497 12.496 32.758 0 45.255L424 197.255V256h56c17.972 0 32.484 14.816 31.988 32.9zM257 0c-61.856 0-112 50.144-112 112h224C369 50.144 318.856 0 257 0z"/></svg></span></span>
</label>
<div class="inside_container" style="max-height: 390px;">
<p><code2>@keyframes tinUpOut { <br>0%,<br>20%,<br>40%,<br>50% {<br>opacity: 1;<br>-webkit-transform: scale(1, 1) translateY(0);<br>transform: scale(1, 1) translateY(0);<br>}<br>10%,<br>30% {<br>opacity: 1;<br>-webkit-transform: scale(1.1, 1.1) translateY(0);<br>
	transform: scale(1.1, 1.1) translateY(0);<br>}<br>100% {<br>opacity: 0;<br>-webkit-transform: scale(1, 1) translateY(-900%);<br>transform: scale(1, 1) translateY(-900%);<br>}<br>}<br></code2></p>
<svg id="inside_animation_icon" style="width: 60px; height: 60px; animation: tinUpOut 6s infinite;" fill="#EC0D8A" viewBox="0 0 448 512">
<path d="M368 96h-48V56c0-13.255-10.745-24-24-24H24C10.745 32 0 42.745 0 56v400c0 13.255 10.745 24 24 24h272c13.255 0 24-10.745 24-24v-42.11l80.606-35.977C429.396 365.063 448 336.388 448 304.86V176c0-44.112-35.888-80-80-80zm16 208.86a16.018 16.018 0 0 1-9.479 14.611L320 343.805V160h48c8.822 0 16 7.178 16 16v128.86zM208 384c-8.836 0-16-7.164-16-16V144c0-8.836 7.164-16 16-16s16 7.164 16 16v224c0 8.836-7.164 16-16 16zm-96 0c-8.836 0-16-7.164-16-16V144c0-8.836 7.164-16 16-16s16 7.164 16 16v224c0 8.836-7.164 16-16 16z" /> </svg>
</div>
</div>
<div style="margin-bottom: 18px;">
<input type="checkbox" name="myaccordion" id="tab_sixteen">
<label for="tab_sixteen"> <span class="karna_span"><span>16. TinUpOut.</span><span>
<svg style="width: 40px; height: 40px; animation: tinUpIn 4s infinite;" fill="white" viewbox="0 0 512 512"><path d="M511.988 288.9c-.478 17.43-15.217 31.1-32.653 31.1H424v16c0 21.864-4.882 42.584-13.6 61.145l60.228 60.228c12.496 12.497 12.496 32.758 0 45.255-12.498 12.497-32.759 12.496-45.256 0l-54.736-54.736C345.886 467.965 314.351 480 280 480V236c0-6.627-5.373-12-12-12h-24c-6.627 0-12 5.373-12 12v244c-34.351 0-65.886-12.035-90.636-32.108l-54.736 54.736c-12.498 12.497-32.759 12.496-45.256 0-12.496-12.497-12.496-32.758 0-45.255l60.228-60.228C92.882 378.584 88 357.864 88 336v-16H32.666C15.23 320 .491 306.33.013 288.9-.484 270.816 14.028 256 32 256h56v-58.745l-46.628-46.628c-12.496-12.497-12.496-32.758 0-45.255 12.498-12.497 32.758-12.497 45.256 0L141.255 160h229.489l54.627-54.627c12.498-12.497 32.758-12.497 45.256 0 12.496 12.497 12.496 32.758 0 45.255L424 197.255V256h56c17.972 0 32.484 14.816 31.988 32.9zM257 0c-61.856 0-112 50.144-112 112h224C369 50.144 318.856 0 257 0z"/></svg></span></span>
</label>
<div class="inside_container" style="max-height: 390px;">
<p><code2>@keyframes tinUpIn { <br>0% {<br>opacity: 0;<br>-webkit-transform: scale(1, 1) translateY(-900%);<br>transform: scale(1, 1) translateY(-900%);<br>}<br>50%,<br>70%,<br>90% {<br>opacity: 1;<br>-webkit-transform: scale(1.1, 1.1) translateY(0);<br>transform: scale(1.1, 1.1) translateY(0);<br>}<br>60%,<br>80%,<br>100% {<br>opacity: 1;<br>-webkit-transform: scale(1, 1) translateY(0);<br>transform: scale(1, 1) translateY(0);<br>}<br>}<br></code2></p>
<svg id="inside_animation_icon" style="width: 60px; height: 60px; animation: tinUpIn 7s infinite;" fill="black" viewBox="0 0 448 512">
<path d="M448 384c-28.02 0-31.26-32-74.5-32-43.43 0-46.825 32-74.75 32-27.695 0-31.454-32-74.75-32-42.842 0-47.218 32-74.5 32-28.148 0-31.202-32-74.75-32-43.547 0-46.653 32-74.75 32v-80c0-26.5 21.5-48 48-48h16V112h64v144h64V112h64v144h64V112h64v144h16c26.5 0 48 21.5 48 48v80zm0 128H0v-96c43.356 0 46.767-32 74.75-32 27.951 0 31.253 32 74.75 32 42.843 0 47.217-32 74.5-32 28.148 0 31.201 32 74.75 32 43.357 0 46.767-32 74.75-32 27.488 0 31.252 32 74.5 32v96zM96 96c-17.75 0-32-14.25-32-32 0-31 32-23 32-64 12 0 32 29.5 32 56s-14.25 40-32 40zm128 0c-17.75 0-32-14.25-32-32 0-31 32-23 32-64 12 0 32 29.5 32 56s-14.25 40-32 40zm128 0c-17.75 0-32-14.25-32-32 0-31 32-23 32-64 12 0 32 29.5 32 56s-14.25 40-32 40z" /> </svg>
</div>
</div>
<div style="margin-bottom: 18px;">
<input type="checkbox" name="myaccordion" id="tab_seventeen">
<label for="tab_seventeen"> <span class="karna_span"><span>17. TinRightOut</span><span>
<svg style="width: 40px; height: 40px; animation: tinRightOut 5s infinite;" fill="white" viewbox="0 0 512 512"><path d="M288 167.2v-28.1c-28.2-36.3-47.1-79.3-54.1-125.2-2.1-13.5-19-18.8-27.8-8.3-21.1 24.9-37.7 54.1-48.9 86.5 34.2 38.3 80 64.6 130.8 75.1zM400 64c-44.2 0-80 35.9-80 80.1v59.4C215.6 197.3 127 133 87 41.8c-5.5-12.5-23.2-13.2-29-.9C41.4 76 32 115.2 32 156.6c0 70.8 34.1 136.9 85.1 185.9 13.2 12.7 26.1 23.2 38.9 32.8l-143.9 36C1.4 414-3.4 426.4 2.6 435.7 20 462.6 63 508.2 155.8 512c8 .3 16-2.6 22.1-7.9l65.2-56.1H320c88.4 0 160-71.5 160-159.9V128l32-64H400zm0 96.1c-8.8 0-16-7.2-16-16s7.2-16 16-16 16 7.2 16 16-7.2 16-16 16z"/></svg></span></span>
</label>
<div class="inside_container" style="max-height: 390px;">
<p><code2>@keyframes tinRightOut { <br>0%,<br>20%,<br>40%,<br>50% {<br>opacity: 1;<br>-webkit-transform: scale(1, 1) translateX(0);<br>transform: scale(1, 1) translateX(0);<br>}<br>10%,<br>30% {<br>opacity: 1;<br>-webkit-transform: scale(1.1, 1.1) translateX(0);<br>
	transform: scale(1.1, 1.1) translateX(0);<br>}<br>100% {<br>opacity: 0;<br>-webkit-transform: scale(1, 1) translateX(900%);<br>transform: scale(1, 1) translateX(900%);<br>}<br>}<br></code2></p>
<svg id="inside_animation_icon" style="width: 60px; height: 60px; animation: tinRightOut 7s infinite;" fill="#241D24" viewBox="0 0 368 512">
<path d="M323.1 3H49.9C12.4 3 0 31.3 0 49.1v433.8c0 20.3 12.1 27.7 18.2 30.1 6.2 2.5 22.8 4.6 32.9-7.1C180 356.5 182.2 354 182.2 354c3.1-3.4 3.4-3.1 6.8-3.1h83.4c35.1 0 40.6-25.2 44.3-39.7l48.6-243C373.8 25.8 363.1 3 323.1 3zm-16.3 73.8l-11.4 59.7c-1.2 6.5-9.5 13.2-16.9 13.2H172.1c-12 0-20.6 8.3-20.6 20.3v13c0 12 8.6 20.6 20.6 20.6h90.4c8.3 0 16.6 9.2 14.8 18.2-1.8 8.9-10.5 53.8-11.4 58.8-.9 4.9-6.8 13.5-16.9 13.5h-73.5c-13.5 0-17.2 1.8-26.5 12.6 0 0-8.9 11.4-89.5 108.3-.9.9-1.8.6-1.8-.3V75.9c0-7.7 6.8-16.6 16.6-16.6h219c8.2 0 15.6 7.7 13.5 17.5z" /> </svg>
</div>
</div>
<div style="margin-bottom: 18px;">
<input type="checkbox" name="myaccordion" id="tab_eighteen">
<label for="tab_eighteen"> <span class="karna_span"><span>18. TinRightIn</span><span>
<svg style="width: 40px; height: 40px; animation: tinRightIn 4s infinite;" fill="white" viewBox="0 0 352 512"><path d="M176 352c53.02 0 96-42.98 96-96V96c0-53.02-42.98-96-96-96S80 42.98 80 96v160c0 53.02 42.98 96 96 96zm160-160h-16c-8.84 0-16 7.16-16 16v48c0 74.8-64.49 134.82-140.79 127.38C96.71 376.89 48 317.11 48 250.3V208c0-8.84-7.16-16-16-16H16c-8.84 0-16 7.16-16 16v40.16c0 89.64 63.97 169.55 152 181.69V464H96c-8.84 0-16 7.16-16 16v16c0 8.84 7.16 16 16 16h160c8.84 0 16-7.16 16-16v-16c0-8.84-7.16-16-16-16h-56v-33.77C285.71 418.47 352 344.9 352 256v-48c0-8.84-7.16-16-16-16z"/></svg></span></span>
</label>
<div class="inside_container" style="max-height: 390px;">
<p><code2>@keyframes tinRightIn { <br>0% {<br>opacity: 0;<br>-webkit-transform: scale(1, 1) translateX(900%);<br>transform: scale(1, 1) translateX(900%);<br>}<br>50%,<br>70%,<br>90% {<br>opacity: 1;<br>-webkit-transform: scale(1.1, 1.1) translateX(0);<br>transform: scale(1.1, 1.1) translateX(0);<br>}<br>60%,<br>80%,<br>100% {<br>opacity: 1;<br>-webkit-transform: scale(1, 1) translateX(0);<br>transform: scale(1, 1) translateX(0);<br>}<br>}<br></code2></p>
<svg id="inside_animation_icon" style="width: 60px; height: 60px; animation: tinRightIn 7s infinite;" fill="#CA0A3E" viewBox="0 0 384 512">
<path d="M97.333 506.966c-129.874-129.874-129.681-340.252 0-469.933 5.698-5.698 14.527-6.632 21.263-2.422l64.817 40.513a17.187 17.187 0 0 1 6.849 20.958l-32.408 81.021a17.188 17.188 0 0 1-17.669 10.719l-55.81-5.58c-21.051 58.261-20.612 122.471 0 179.515l55.811-5.581a17.188 17.188 0 0 1 17.669 10.719l32.408 81.022a17.188 17.188 0 0 1-6.849 20.958l-64.817 40.513a17.19 17.19 0 0 1-21.264-2.422zM247.126 95.473c11.832 20.047 11.832 45.008 0 65.055-3.95 6.693-13.108 7.959-18.718 2.581l-5.975-5.726c-3.911-3.748-4.793-9.622-2.261-14.41a32.063 32.063 0 0 0 0-29.945c-2.533-4.788-1.65-10.662 2.261-14.41l5.975-5.726c5.61-5.378 14.768-4.112 18.718 2.581zm91.787-91.187c60.14 71.604 60.092 175.882 0 247.428-4.474 5.327-12.53 5.746-17.552.933l-5.798-5.557c-4.56-4.371-4.977-11.529-.93-16.379 49.687-59.538 49.646-145.933 0-205.422-4.047-4.85-3.631-12.008.93-16.379l5.798-5.557c5.022-4.813 13.078-4.394 17.552.933zm-45.972 44.941c36.05 46.322 36.108 111.149 0 157.546-4.39 5.641-12.697 6.251-17.856 1.304l-5.818-5.579c-4.4-4.219-4.998-11.095-1.285-15.931 26.536-34.564 26.534-82.572 0-117.134-3.713-4.836-3.115-11.711 1.285-15.931l5.818-5.579c5.159-4.947 13.466-4.337 17.856 1.304z" /> </svg>
</div>
</div>

{% include googlead5.html %}

<div style="margin-bottom: 18px;">
<input type="checkbox" name="myaccordion" id="tab_nineteen">
<label for="tab_nineteen"> <span class="karna_span"><span>19. OpenRightOut</span><span><svg style="width: 40px; height: 40px; animation: openUpRightOut 2s infinite;" fill="white" viewbox="0 0 512 512"><path d="M507.73 109.1c-2.24-9.03-13.54-12.09-20.12-5.51l-74.36 74.36-67.88-11.31-11.31-67.88 74.36-74.36c6.62-6.62 3.43-17.9-5.66-20.16-47.38-11.74-99.55.91-136.58 37.93-39.64 39.64-50.55 97.1-34.05 147.2L18.74 402.76c-24.99 24.99-24.99 65.51 0 90.5 24.99 24.99 65.51 24.99 90.5 0l213.21-213.21c50.12 16.71 107.47 5.68 147.37-34.22 37.07-37.07 49.7-89.32 37.91-136.73zM64 472c-13.25 0-24-10.75-24-24 0-13.26 10.75-24 24-24s24 10.74 24 24c0 13.25-10.75 24-24 24z"/></svg></span></span>
</label>
<div class="inside_container" style="max-height: 390px;">
<p><code2>@keyframes openUpRightOut { <br>0% {<br>opacity: 1;<br>-webkit-transform-origin: top right;<br>transform-origin: top right;<br>-webkit-transform: rotate(0deg);<br>transform: rotate(0deg);<br>-webkit-animation-timing-function: ease-out;<br>animation-timing-function: ease-out;<br>}<br>100% {<br>opacity: 0;<br>-webkit-transform-origin: top right;<br>transform-origin: top right;<br>-webkit-transform: rotate(-110deg);<br>
	transform: rotate(-110deg);<br>-webkit-animation-timing-function: ease-in-out;<br>animation-timing-function: ease-in-out;<br>}<br>}<br></code2></p>
<svg id="inside_animation_icon" style="width: 60px; height: 60px; animation: openUpRightOut 3s infinite;" fill="black" viewBox="0 0 576 512">
<path d="M528.12 301.319l47.273-208C578.806 78.301 567.391 64 551.99 64H159.208l-9.166-44.81C147.758 8.021 137.93 0 126.529 0H24C10.745 0 0 10.745 0 24v16c0 13.255 10.745 24 24 24h69.883l70.248 343.435C147.325 417.1 136 435.222 136 456c0 30.928 25.072 56 56 56s56-25.072 56-56c0-15.674-6.447-29.835-16.824-40h209.647C430.447 426.165 424 440.326 424 456c0 30.928 25.072 56 56 56s56-25.072 56-56c0-22.172-12.888-41.332-31.579-50.405l5.517-24.276c3.413-15.018-8.002-29.319-23.403-29.319H218.117l-6.545-32h293.145c11.206 0 20.92-7.754 23.403-18.681z" /> </svg>
</div>
</div>
<div style="margin-bottom: 18px;">
<input type="checkbox" name="myaccordion" id="tab_twenty">
<label for="tab_twenty"> <span class="karna_span"><span>20. DownToUp.</span><span><svg style="width: 40px; height: 40px; animation: perspectiveDownReturn 4s infinite;" fill="white" viewbox="0 0 512 512"><path d="M512 512H0V0h512v512z"/></svg></span></span>
</label>
<div class="inside_container" style="max-height: 410px;">
<p><code2>@keyframes perspectiveDownReturn {<br>0% {<br>-webkit-transform-origin: 0 100%;<br>transform-origin: 0 100%;<br>-webkit-transform: perspective(800px) rotateX(-180deg);<br>transform: perspective(800px) rotateX(-180deg);<br>}<br>100% {<br>-webkit-transform-origin: 0 100%;<br>transform-origin: 0 100%;<br>-webkit-transform: perspective(800px) rotateX(0deg);<br>transform: perspective(800px) rotateX(0deg);<br>}<br>}<br></code2></p>
<svg id="inside_animation_icon" style="width: 60px; height: 60px; animation: perspectiveDownReturn 3s infinite alternate;" fill="black" viewBox="0 0 192 512">
<path d="M96 0c35.346 0 64 28.654 64 64s-28.654 64-64 64-64-28.654-64-64S60.654 0 96 0m48 144h-11.36c-22.711 10.443-49.59 10.894-73.28 0H48c-26.51 0-48 21.49-48 48v136c0 13.255 10.745 24 24 24h16v136c0 13.255 10.745 24 24 24h64c13.255 0 24-10.745 24-24V352h16c13.255 0 24-10.745 24-24V192c0-26.51-21.49-48-48-48z" /> </svg>
</div>
</div>
<div style="margin-bottom: 18px;">
<input type="checkbox" name="myaccordion" id="tab_twentyone">
<label for="tab_twentyone"> <span class="karna_span"><span>21. SpaceOut..</span><span>
<svg style="width: 40px; height: 40px; animation: spaceOutUp 2s infinite alternate;" fill="white" viewbox="0 0 512 512"><path d="M256 256v64h-64v-64h64zm0-256h-64v64h64V0zm0 256h64v-64h-64v64zM384 0h-64v64h64V0zm0 512h64v-64h-64v64zm128-64v-64h-64v64h64zm-384 64h64v-64h-64v64zm0-512H64v64h64V0zm384 192v-64h-64v64h64zm0 128v-64h-64v64h64zM0 512h64v-64H0v64zM0 64v64h64V64H0zm0 128v64h64v-64H0zm0 128v64h64v-64H0zm256 192h64v-64h-64v64zm-64-128v64h64v-64h-64zm64-192v-64h-64v64h64zM64 384v64h64v-64H64zm64-128H64v64h64v-64zm256 128h64v-64h-64v64zM512 0h-64v64h64V0zM384 256h64v-64h-64v64zm0-192v64h64V64h-64zm-64 320v64h64v-64h-64zm-192-64v64h64v-64h-64zm128 0v64h64v-64h-64zm-64-128h-64v64h64v-64zm-64-64H64v64h64v-64zm192 192h64v-64h-64v64zM192 128V64h-64v64h64zm128 0V64h-64v64h64zm0 64h64v-64h-64v64z"/></svg></span></span>
</label>
<div class="inside_container" style="max-height: 430px;">
<p><code2>@keyframes spaceOutUp {<br>0% {<br>opacity: 1;<br>-webkit-transform-origin: 50% 0%;<br>transform-origin: 50% 0%;<br>-webkit-transform: scale(1) translate(0%, 0%);<br>
	transform: scale(1) translate(0%, 0%);<br>}<br>100% {<br>opacity: 0;<br>-webkit-transform-origin: 50% 0%;<br>transform-origin: 50% 0%;<br>-webkit-transform: scale(.2) translate(0%, -200%);<br>transform: scale(.2) translate(0%, -200%);<br>}<br>}<br></code2></p>
<svg id="inside_animation_icon" style="width: 60px; height: 60px; animation: spaceOutUp 3s infinite alternate;" fill="black" viewBox="0 0 640 512">
<path d="M480 96H160C71.6 96 0 167.6 0 256s71.6 160 160 160c44.8 0 85.2-18.4 114.2-48h91.5c29 29.6 69.5 48 114.2 48 88.4 0 160-71.6 160-160S568.4 96 480 96zM256 276c0 6.6-5.4 12-12 12h-52v52c0 6.6-5.4 12-12 12h-40c-6.6 0-12-5.4-12-12v-52H76c-6.6 0-12-5.4-12-12v-40c0-6.6 5.4-12 12-12h52v-52c0-6.6 5.4-12 12-12h40c6.6 0 12 5.4 12 12v52h52c6.6 0 12 5.4 12 12v40zm184 68c-26.5 0-48-21.5-48-48s21.5-48 48-48 48 21.5 48 48-21.5 48-48 48zm80-80c-26.5 0-48-21.5-48-48s21.5-48 48-48 48 21.5 48 48-21.5 48-48 48z" /> </svg>
</div>
</div>

{% include googlead1.html %}

<div style="margin-bottom: 18px;">
<input type="checkbox" name="myaccordion" id="tab_twentytwo">
<label for="tab_twentytwo"> <span class="karna_span"><span>22. PuffIn...</span><span>
<svg style="width: 40px; height: 40px; animation: puffIn 5s infinite;" fill="white" viewbox="0 0 384 512"><path d="M336 0H48C21.49 0 0 21.49 0 48v464l192-112 192 112V48c0-26.51-21.49-48-48-48zm0 428.43l-144-84-144 84V54a6 6 0 0 1 6-6h276c3.314 0 6 2.683 6 5.996V428.43z"/></svg></span></span>
</label>
<div class="inside_container" style="max-height: 410px;">
<p><code2>@keyframes puffIn {<br>0% {<br>opacity: 0;<br>-webkit-transform-origin: 50% 50%;<br>transform-origin: 50% 50%;<br>-webkit-transform: scale(2, 2);<br>transform: scale(2, 2);<br>-webkit-filter: blur(2px);<br>filter: blur(2px);<br>}<br>100% {<br>opacity: 1;<br>-webkit-transform-origin: 50% 50%;<br>transform-origin: 50% 50%;<br>-webkit-transform: scale(1, 1);<br>transform: scale(1, 1);<br>-webkit-filter: blur(0px);<br>filter: blur(0px);<br>}<br>}<br></code2></p>
<svg id="inside_animation_icon" style="width: 60px; height: 60px; animation: puffIn 4s infinite;" fill="black" viewBox="0 0 448 512">
<path d="M0 32v128h128V32H0zm120 120H8V40h112v112zm40-120v128h128V32H160zm120 120H168V40h112v112zm40-120v128h128V32H320zm120 120H328V40h112v112zM0 192v128h128V192H0zm120 120H8V200h112v112zm40-120v128h128V192H160zm120 120H168V200h112v112zm40-120v128h128V192H320zm120 120H328V200h112v112zM0 352v128h128V352H0zm120 120H8V360h112v112zm40-120v128h128V352H160zm120 120H168V360h112v112zm40-120v128h128V352H320z" /> </svg>
</div>
</div>
<div style="margin-bottom: 18px;">
<input type="checkbox" name="myaccordion" id="tab_twentythree">
<label for="tab_twentythree"> <span class="karna_span"><span>23. VanishIn...</span><span>
<svg style="width: 40px; height: 40px; animation: vanishIn 4s infinite alternate;" fill="white" viewbox="0 0 448 512"><path d="M0 32v448h448V32H0zm316.5 325.2L224 445.9l-92.5-88.7 64.5-184-64.5-86.6h184.9L252 173.2l64.5 184z"/></svg></span></span>
</label>
<div class="inside_container" style="max-height: 410px;">
<p><code2>@keyframes vanishIn { <br>0% {<br>opacity: 0;<br>-webkit-transform-origin: 50% 50%;<br>transform-origin: 50% 50%;<br>-webkit-transform: scale(2, 2);<br>transform: scale(2, 2);<br>-webkit-filter: blur(90px);<br>filter: blur(90px);<br>
	}<br>100% {<br>opacity: 1;<br>-webkit-transform-origin: 50% 50%;<br>transform-origin: 50% 50%;<br>-webkit-transform: scale(1, 1);<br>transform: scale(1, 1);<br>-webkit-filter: blur(0px);<br>
	filter: blur(0px);<br>}<br>}<br></code2></p>
<svg id="inside_animation_icon" style="width: 60px; height: 60px; animation: vanishIn 3s infinite alternate;" fill="black" viewBox="0 0 640 512">
<path d="M464.46 246.68L352 179.2V128h48c8.84 0 16-7.16 16-16V80c0-8.84-7.16-16-16-16h-48V16c0-8.84-7.16-16-16-16h-32c-8.84 0-16 7.16-16 16v48h-48c-8.84 0-16 7.16-16 16v32c0 8.84 7.16 16 16 16h48v51.2l-112.46 67.48A31.997 31.997 0 0 0 160 274.12V512h96v-96c0-35.35 28.65-64 64-64s64 28.65 64 64v96h96V274.12c0-11.24-5.9-21.66-15.54-27.44zM0 395.96V496c0 8.84 7.16 16 16 16h112V320L19.39 366.54A32.024 32.024 0 0 0 0 395.96zm620.61-29.42L512 320v192h112c8.84 0 16-7.16 16-16V395.96c0-12.8-7.63-24.37-19.39-29.42z" /> </svg>
</div>
	</div>
</div>

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
				<li><a href="#font-awesome-CDN" class="test"><b>What is Font Awesome CDN?</b></a></li>
				<li><a href="#font-awesome-icons-animation" class="test"><b>Font Awesome Icons Animations With Pure CSS.</b></a></li>
				<li><a href="#discourse-comments" class="test"><b>Throw a comment.</b></a></li>
			</ol>
		</div>
	</div>



<style>
	.accordion_container {
		width: 100%;
	}
.accordion_container label {
			border: 1px solid lightgrey;
			/*			background-color: dodgerblue;*/
			background-color: #046CF4;
			color: white;
			padding: 10px;
			width: 100%;
			margin: auto;
			display: block;
			cursor: pointer;
			height: auto;
			position: relative;
			border-radius: 5px;
		}
	input[type=checkbox] + label::after {
			content: " + ";
			position: absolute;
			right: 15px;
			bottom: 0;
			left: auto;
			top: 10px;
			font-size: 30px;
		}
		input[type=checkbox]:checked + label::after {
			content: "-";
			position: absolute;
			right: 15px;
			bottom: 0;
			left: auto;
			top: -3px;
			font-size: 50px;
		}
		.accordion_container input {
			display: none;
		}
		.accordion_container input:checked ~ .inside_container {
			height: 530px;
			overflow-x: hidden;
			overflow-y: auto;
		}
		.inside_container {
			height: 0px;
			overflow: hidden;
			padding: 0 15px;
			width: 95%;
			margin: auto;
			border-radius: 5px;
			margin-top: 3px;
			background-color: rgba(0, 0, 0, 0.47);
			transition: all .9s ease;
			position: relative;
		}
		.inside_container p {
			border: 1px solid white;
			text-align: center;
			border-radius: 5px;
			background: rgba(244, 244, 244, 0.47);
		}
		code2 {
			background: rgba(244, 244, 244, 0.47);
			color: black;
			margin: 0 30%;
			padding: 10px;
			line-height: 1.22em;
			font-size: 16px;
			text-align: left;
			display: block;
		}
		#inside_animation_icon {
			padding: 0px;
			margin: auto;
			height: auto;
			width: auto;
			position: absolute;
			right: 0px;
			left: 65%;
			top: 0px;
			bottom: 0px;
		}
		#svg_animation_icon {
			width: 40px;
			height: 40px;
			fill: white;
			animation: wrench 3s ease-in-out infinite alternate;
		}
		.karna_span {
			color: white;
			display: flex;
			flex-grow: 1;
			flex-basis: 50px;
			flex-wrap: wrap;
			width: 100%;
			height: auto;
			padding: 0px;
		}
		label span:nth-child(1) {
			flex-grow: 1;
			padding: 5px 0px 0px 20px;
			font-size: 22px;
			text-align: left;
			/*			border: 1px solid black;*/
			font-variant: small-caps;
		}
		label span:nth-child(2) {
			flex-grow: 2;
			/*			border: 1px solid yellow;*/
			text-align: left;
			padding: 0px;
			margin-top: -8px;
		}
@media only screen and (max-width:760px) {
.accordion_container label {
				width: 100%;
				height: auto;
			}
.inside_container {
				width: 100%;
			}
code2 {
				margin: auto;

			}
label span:nth-child(1) {
				padding: 5px;
			}
}

	{% include animation.min.css %}

	</style>
