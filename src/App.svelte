<script>
	import Button from "./Button.svelte";
	import Badge from "./Badge.svelte";
	import Footer from "./Footer.svelte";
	import Card from "./Card.svelte";
	import Bb from "./Bb.svelte";
	import Avatar from "./Avatar.svelte";


</script>

<h3>Badge component</h3>

<section class="badge">

	<div id="badge-section">
	<Badge>neutral</Badge>
	<pre><code>{'<Badge>neutral</Badge>'}</code></pre>
	</div>


<div id="badge-section">
<Badge type="primary">primary</Badge>
<pre><code>{'<Badge type="primary">primary</Badge>'}</code></pre>
</div>

<div id="badge-section">
<Badge type="secondary">secondary</Badge>
<pre><code>{'<Badge type="secondary">secondary</Badge>'}</code></pre>
</div>

<div id="badge-section">
<Badge type="accent">accent</Badge>
<pre><code>{'<Badge type="accent">accent</Badge>'}</code></pre>
</div>

<div id="badge-section">
<Badge type="ghost">ghost</Badge>
<pre><code>{'<Badge type="ghost">ghost</Badge>'}</code></pre>
</div>
</section>

<h3>Button component</h3>
<section class="button">

	<div id="button-section">
<Button>BUTTON</Button>
<pre><code>{'<Button>BUTTON</Button>'}</code></pre>

</div>

<div id="button-section">
<Button type="primary">PRIMARY</Button>
<pre><code>{'<Button type="primary">PRIMARY</Button>'}</code></pre>
<!--<Button type="primary" mode="inversed">Primary</Button>-->
</div>


<div id="button-section">
<Button type="secondary">SECONDARY</Button>
<pre><code>{'<Button type="secondary">SECONDARY</Button>'}</code></pre>
<!--<Button type="secondary" mode="inversed">Første knap</Button>-->
</div>

<div id="button-section">
<Button type="accent">ACCENT</Button>
<pre><code>{'<Button type="accent">ACCENT</Button>'}</code></pre>
</div>

<div id="button-section">
<Button type="ghost">GHOST</Button>
<pre><code>{'<Button type="ghost">GHOST</Button>'}</code></pre>
</div>

<div id="button-section">
<Button type="link">LINK</Button>
<pre><code>{'<Button type="link">LINK</Button>'}</code></pre>
</div>
</section>
<h3>Card component</h3>

<section class="card"> <Card></Card>
</section>
<h3>Button w Badge component</h3>

<section class="bb"> <Bb></Bb>
</section>

<div>
	<h3>Avatar component</h3>
	<Avatar name="Navn" />

</div>

<h3>Footer component</h3>

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