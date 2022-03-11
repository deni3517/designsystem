<script>
	import Button from "./Button.svelte";
	import Badge from "./Badge.svelte";
	import Footer from "./Footer.svelte";
	import Card from "./Card.svelte";
	import Bb from "./Bb.svelte";
	import Avatar from "./Avatar.svelte";


</script>
<div id="content">
<h3>Badge component</h3>

<section class="badge">

	<Badge>neutral</Badge>


<Badge type="primary">primary</Badge>


<Badge type="secondary">secondary</Badge>

<Badge type="accent">accent</Badge>

<Badge type="ghost">ghost</Badge>

</section>

<div id="doc-section">
	<h4>Dokumentation</h4>
	<p>Button</p>
	<pre><code>{'<Badge>neutral</Badge>'}</code></pre>
	<p>Primary</p>
	<pre><code>{'<Badge type="primary">primary</Badge>'}</code></pre>
	<p>Secondary</p>
	<pre><code>{'<Badge type="secondary">secondary</Badge>'}</code></pre>
	<p>Accent</p>
	<pre><code>{'<Badge type="accent">accent</Badge>'}</code></pre>
	<p>Ghost</p>
	<pre><code>{'<Badge type="ghost">ghost</Badge>'}</code></pre>
	</div>

<h3>Button component</h3>
<section class="button">

<Button>BUTTON</Button>


<Button type="primary">PRIMARY</Button>
<!--<Button type="primary" mode="inversed">Primary</Button>-->


<Button type="secondary">SECONDARY</Button>
<!--<Button type="secondary" mode="inversed">Første knap</Button>-->

<Button type="accent">ACCENT</Button>

<Button type="ghost">GHOST</Button>

<Button type="link">LINK</Button>

</section>


<div id="doc-section">
	<h4>Dokumentation</h4>

	<p>Button</p>
	<pre><code>{'<Button>BUTTON</Button>'}</code></pre>


	<p>Primary</p>
	<pre><code>{'<Button type="primary">PRIMARY</Button>'}</code></pre>


	<p>Secondary</p>
	<pre><code>{'<Button type="secondary">SECONDARY</Button>'}</code></pre>

	<p>Accent</p>
	<pre><code>{'<Button type="accent">ACCENT</Button>'}</code></pre>

	<p>Ghost</p>
	<pre><code>{'<Button type="ghost">GHOST</Button>'}</code></pre>

	<p>Link</p>
	<pre><code>{'<Button type="link">LINK</Button>'}</code></pre>

	</div>
<h3>Card component</h3>

<section class="card"> <Card></Card>
</section>

<div id="doc-section">
	<h4>Dokumentation</h4>
	<pre><code>{'<section class="card"> <Card></Card>'}</code></pre>
	</div>


<h3>Button w Badge component</h3>

<section class="bb"> <Bb></Bb>

</section>

<div id="doc-section">
	<h4>Dokumentation</h4>
	<pre><code>{'<section class="bb">'}</code></pre>
	</div>


<div>
	<h3>Avatar component</h3>
	<Avatar name="Navn" />

</div>
<h3>Footer component</h3>
<div id="doc-section">
	<h4>Dokumentation</h4>
	<pre><code>{'<section class="footer"> <Footer></Footer>'}</code></pre>
	</div>
</div>

<section class="footer"> <Footer></Footer>

</section>

<style>



.footer {
	display: grid;
	grid-template-columns: repeat( auto-fit, minmax(250px, 1fr) );
	background: var(--default-color);
	margin-top: 20px;
	padding: 20px;
}

	.badge {
		display: flex;
		flex-direction: row;
		gap: 1rem;
	}
</style>