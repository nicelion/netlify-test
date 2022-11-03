<svelte:head>
	<title>About</title>
	<meta name="description" content="About this app" />
</svelte:head>

<div class="text-column">
	<h1>About this app</h1>

	<p>
		This is a <a href="https://kit.svelte.dev">SvelteKit</a> app. You can make your own by typing the
		following into your command line and following the prompts:
	</p>

	<pre>npm create svelte@latest</pre>

	<p>
		The page you're looking at is purely static HTML, with no client-side interactivity needed.
		Because of that, we don't need to load any JavaScript. Try viewing the page's source, or opening
		the devtools network panel and reloading.
	</p>

	<p>
		The <a href="/sverdle">Sverdle</a> page illustrates SvelteKit's data loading and form handling. Try
		using it with JavaScript disabled!
	</p>
</div>

<form name="netlify-form-example" method="POST" netlify-honeypot="bot-field" data-netlify="true">
	<input type="hidden" name="form-name" value="netlify-form-example" />
	<label for="name">Name</label>
	<input name="name" id="name" required placeholder="Name" type="text" />
	<label for="email">Email</label>
	<input name="email" id="email" required placeholder="Email" type="email" />
	<label for="message">Message</label>
	<input name="message" id="message" required placeholder="Message" type="text" />
	<input type="text" value="about" hidden>

	<input type="submit" value="Submit" />
  </form>