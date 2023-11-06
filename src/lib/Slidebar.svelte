<!--                                  
╭━━╮╱╱╱╱╭╮╱╱╱╱╱╭╮╱╭╮╱╱╱╱╱╭╮            ━╮ ╭━
╰┫┣╯╱╱╱╱┃┃╱╱╱╱╭╯╰╮┃┃╱╱╱╱╱┃┃             | |
╱┃┃╭━╮╭━╯┣━━┳━┻╮╭╯┃┃╱╱╭━━┫╰━┳━━╮       ╱ o \
╱┃┃┃╭╮┫╭╮┃┃━┫━━┫┃╱┃┃╱╭┫╭╮┃╭╮┃━━┫      ╱_____\
╭┫┣┫┃┃┃╰╯┃┃━╋━━┃╰╮┃╰━╯┃╭╮┃╰╯┣━━┃     ╱    o  \  
╰━━┻╯╰┻━━┻━━┻━━┻━╯╰━━━┻╯╰┻━━┻━━╯    (__o______)  

Yet another science experiment from Indest Labs.

Recommend viewing in Visual Source Code.
-->

<script>
	import fly from './transitions.js';
	export let open = false;
</script>

{#if open}
	<div class="drawer" transition:fly={{ x: '100%' }}>
		<center><h1>Attribution</h1></center>

		<p>
			Attribution is to 🔥 Rafa 🔥, who did a wonderful job on the design and I've learned so much
			from the CSS code which is remarkably extensive. So what did I do? I morphed the code to
			Svelte as an experiment on how to re-write code the Svelte way. I achieved a modest reduction
			in the code, leveraged Svelte's reactivity and declarative style and could probably do more
			(Rafa likes div's 👍) Here is the original codepen <a
				href="https://codepen.io/RAFA3L/pen/PoVYoPN">link</a
			>

			<center><h1>Disclaimer</h1></center>
		</p>
		<h2>TL;DR</h2>
		<p>Disclaimer: I'm not responsible for anything. Period. ⚫️</p>
		<h2>Details</h2>

		<p>
			If you require any more information or have any questions about my site's disclaimer, please
			feel free to contact me via email or
			<a href="https://linkedin.com/in/windest">LinkedIn</a>.
		</p>
		<p>
			All the information on this website is published in good faith and for general information
			purposes only. It does not make any warranties about the completeness, reliability and
			accuracy of this information. Any action you take upon the information you find on this
			website is strictly at your own risk and we will not be liable for any losses and/or damages
			in connection with the use of my website. It may be possible for you to visit other websites
			by following hyperlinks to other external sites. While I strive to provide only quality links
			to useful and ethical websites, I have no control over the content and nature of these sites.
			These links to other websites do not imply a recommendation for all the content found on these
			sites. Site owners and content may change without notice and may occur before I have the
			opportunity to remove a link which may have gone 'bad'. Please be also aware that when you
			leave my website, other sites may have different privacy policies and terms which are beyond
			my control. Please be sure to check the Privacy Policies of these sites as well as their
			"Terms of Service" before engaging in any business or uploading any information.
		</p>
		<h2>Privacy</h2>
		<p>
			This site doesn't track cookies or your personal data because I'm not smart enough to know how
			to do so and I wouldn't anyway. So you are safe.
		</p>
		<h2>Consent</h2>

		<p>By using my website, you hereby consent to my disclaimer and agree to its terms.</p>

		<h2>Update</h2>

		<p>
			Should I update, amend or make any changes to this document, those changes will be prominently
			posted here.
		</p>
		<center><p>...................</p></center>
	</div>
{/if}

<style>
	.drawer {
		position: fixed;
		z-index: 10;
		top: 0;
		right: 0;
		padding: 25px;
		height: 100vh;
		width: 400px;
		border-left: 1px solid rgba(0, 0, 0, 0.1);
		box-shadow: -2px 0px 6px -1px rgba(0, 0, 0, 0.1);
		background: rgba(255, 255, 255, 0.25);
		backdrop-filter: blur(20px);
		overflow: auto;
	}
	div {
		font-size: 20px;
		color: #ffffff;
		font-family: Digitialism, Helvetica Neue, Helvetica, Arial, sans-serif;
	}
</style>
