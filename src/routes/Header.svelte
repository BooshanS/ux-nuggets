<script>
	import { page } from '$app/stores';
	import logo from '$lib/images/svelte-logo.svg';
	import github from '$lib/images/github.svg';
</script>

<header>
	<nav>
		<span class="cd">cd.</span>
		<ul class="navigation">
			<li aria-current={$page.url.pathname === '/' ? 'page' : undefined}>
				<a href="/">Home</a>
			</li>
			<li aria-current={$page.url.pathname === '/nuggets' ? 'page' : undefined}>
				<a href="/nuggets">Nuggets</a>
			</li>
				<li aria-current={$page.url.pathname === '/analyses' ? 'page' : undefined}>
				<a href="/analyses">Analyses</a>
			</li>
				<li aria-current={$page.url.pathname === '/plugin' ? 'page' : undefined}>
				<a href="/plugin">Plugin</a>
			</li>
			</ul>
			<ul class="submit">
			<li aria-current={$page.url.pathname === '/about' ? 'page' : undefined}>
				<a href="/about">Submit</a>
			</li>
		</ul>
	</nav>
</header>

<style>
nav{
	display:flex;
	width:100vw;
	align-content:stretch;
	border-bottom: 1px solid rgba(53, 56, 70, 0.15);
	background: #FFF;
	justify-content:space-around;
}
.navigation{
	display:flex;
	column-gap:3rem;
	justify-content:space-around;
}
.navigation li{
	all:unset;
	color: #000;
	font-family: Inter;
	font-size: 1rem;
	font-style: normal;
	font-weight: 500;
	line-height: normal;
}
.submit li,.submit a,.navigation a{
	all:unset;
}
.submit{
	all:unset;
	display: inline-flex;
	padding: 0.6875rem 1.9375rem;
	justify-content: center;
	align-items: center;
	gap: 0.5rem;
	border-radius: 0.625rem;
	border: 0.5px solid rgba(255, 255, 255, 0.34);
	background: linear-gradient(180deg, #735EF0 0%, #644EE6 100%);
	box-shadow: 0px 0px 0px 1px #4731C9, 0px 2px 2px 0px rgba(54, 50, 79, 0.46);
	color: #FFF;
	font-family: Inter;
	font-size: 1rem;
	font-style: normal;
	font-weight: 500;
	line-height: normal;
	}
.cd{
	color: #000;
	font-family: Almarai;
	font-size: 2.5rem;
	font-style: normal;
	font-weight: 800;
	line-height: normal;
}
header{
		width: 80rem;
		height: 5.625rem;
		flex-shrink: 0;

		background: #FFF;
}
</style>
