<!DOCTYPE html>
<html lang="en">
<head>
	<title>Shower Presentation Engine</title>
	<meta charset="utf-8">
	<meta http-equiv="x-ua-compatible" content="ie=edge">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="stylesheet" href="shower/themes/ribbon/styles/screen-16x10.css">
</head>
<body class="shower list">

	<header class="caption">
		<h1>Shower Presentation Engine</h1>
		<p>Yours Truly, Famous Inc.</p>
	</header>

	<section class="slide" id="cover">
		<h2>Shower Presentation Engine</h2>
		<p>Brought to you by <a href="http://pepelsbey.net">Vadim Makeev</a></p>
		<figure>
			<img class="cover" src="pictures/cover.jpg" alt="Hands on the orange typewriter in a park">
			<figcaption class="white">
				<a href="http://fiftyfootshadows.net/">© John Carey</a>
			</figcaption>
		</figure>
		<style>
			#cover h2 {
				margin:30px 0 0;
				color:#FFF;
				text-align:center;
				font-size:70px;
				}
			#cover p {
				margin:10px 0 0;
				text-align:center;
				color:#FFF;
				font-style:italic;
				font-size:20px;
				}
				#cover p a {
					color:#FFF;
					}
		</style>
	</section>

	<section class="slide">
		<h2>Shower key features</h2>
		<ol>
			<li>Built on HTML, CSS and vanilla JavaScript</li>
			<li>Works in all modern browsers</li>
			<li>Themes are separated from engine</li>
			<li>Modular and extensible</li>
			<li>Fully keyboard accessible</li>
			<li>Printable to PDF</li>
		</ol>
		<p class="note">Shower ['ʃəuə] noun. A person or thing that shows.</p>
	</section>

	<section class="slide">
		<h2>Plain text on your slides</h2>
		<p>Lorem ipsum dolor sit amet, consectetur <a href="#4">adipisicing</a> elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, <em>quis nostrud</em> exercitation ullamco laboris <strong>nisi ut aliquip</strong> ex ea commodo consequat. Duis aute irure <i>dolor</i> in reprehenderit in voluptate velit esse cillum <b>dolore</b> eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in <code>&lt;culpa&gt;</code> qui officia deserunt mollit anim id est laborum.</p>
	</section>

	<section class="slide">
		<h2>Two columns if you like</h2>
		<p class="double">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia.</p>
	</section>

	<section class="slide">
		<h2>All kind of lists</h2>
		<ol>
			<li>Simple lists are marked with bullets</li>
			<li>Ordered lists begin with a number</li>
			<li>You can even nest lists one inside another
				<ul>
					<li>Or mix their types</li>
					<li>But do not go too far</li>
					<li>Otherwise audience will be bored</li>
				</ul>
			</li>
			<li>Look, seven rows exactly!</li>
		</ol>
	</section>

	<section class="slide">
		<h2>Serious citations</h2>
		<figure>
			<blockquote>
				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia.</p>
			</blockquote>
			<figcaption>Marcus Tullius Cicero</figcaption>
		</figure>
	</section>

	<section class="slide">
		<h2>Code samples</h2>
		<pre>
			<code>&lt;!DOCTYPE html&gt;</code>
			<code class="mark">&lt;html lang="en"&gt;</code>
			<code><mark>&lt;head&gt;</mark> <span class="comment">&lt;!--Comment--&gt;</span></code>
			<code>    &lt;title&gt;Shower&lt;/title&gt;</code>
			<code>    &lt;meta charset="<mark class="important">UTF-8</mark>"&gt;</code>
			<code>    &lt;link rel="stylesheet" href="screen.css"&gt;</code>
			<code><mark>&lt;/head&gt;</mark></code>
		</pre>
	</section>

	<section class="slide">
		<h2>Even tables</h2>
		<table>
		<tr>
			<th scope="col">Locavore</th>
			<th>Umami</th>
			<th>Helvetica</th>
			<th>Vegan</th>
		</tr>
		<tr>
			<th scope="row">Fingerstache</th>
			<td>Kale</td>
			<td>Chips</td>
			<td>Keytar</td>
		</tr>
		<tr>
			<th scope="row">Sriracha</th>
			<td>Gluten-free</td>
			<td>Ennui</td>
			<td>Keffiyeh</td>
		</tr>
		<tr>
			<th scope="row">Thundercats</th>
			<td>Jean</td>
			<td>Shorts</td>
			<td>Biodiesel</td>
		</tr>
		<tr>
			<th scope="row">Terry</th>
			<td>Richardson</td>
			<td>Swag</td>
			<td>Blog</td>
		</tr>
		</table>
		<p>It’s good to have information organized.</p>
	</section>

	<section class="slide" id="picture">
		<h2>Pictures</h2>
		<figure>
			<img class="cover" src="pictures/picture.jpg" alt="Orange typewriter on a wooden table close-up">
			<figcaption class="white">
				<a href="http://fiftyfootshadows.net/">© John Carey</a>
			</figcaption>
		</figure>
		<style>
			#picture h2 {
				color:#FFF;
				}
		</style>
	</section>

	<section class="slide">
		<h2 class="shout shrink">You can even shout this way</h2>
	</section>

	<section class="slide">
		<h2>Inner navigation</h2>
		<ol>
			<li>Lets you reveal list items one by one</li>
			<li class="next">To keep some key points</li>
			<li class="next">In secret from audience</li>
			<li class="next">But it will work only once</li>
			<li class="next">Nobody wants to see the same joke twice</li>
		</ol>
	</section>

	<section class="slide grid">
		<h2>All nicely aligned to grid</h2>
	</section>

	<section class="slide" id="see-more">
		<h2 class="shout">
			<img src="pictures/logo.svg" alt="Shower logo">
			<a href="https://github.com/shower/shower">See more on GitHub</a>
		</h2>
		<style>
			#see-more h2 {
				font-size:100px
				}
			#see-more img {
				width:0.72em;
				height:0.72em;
				}
		</style>
	</section>

	<footer class="badge">
		<a href="https://github.com/shower/shower">Fork me on GitHub</a>
	</footer>

	<div class="progress"></div>

	<script src="shower/shower.min.js"></script>
	<!-- Copyright © 2017 Yours Truly, Famous Inc. -->

</body>
</html>

