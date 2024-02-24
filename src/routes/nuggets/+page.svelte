<script>
import Card from './Card.svelte';
import Cardsmall from './Cardsmall.svelte'
</script>
<svelte:head>
	<link rel="preconnect" href="https://fonts.googleapis.com">
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
	<link href="https://fonts.googleapis.com/css2?family=Inter:wght@700&display=swap" rel="stylesheet">
	<title>About</title>
	<meta name="description" content="About this app" />
</svelte:head>

<section class="nuggets-container">
<div class="hero-text">
	<h1>UX Nuggets</h1>
	<h2><span>Byte sized UX design examples from the best design teams in the world curated for you.</span></h2>
</div>
<div class="carousel">
<Cardsmall/>
<Cardsmall/>
<Cardsmall/>
</div>
<div class= "card-heading">
<h3 class="examples">340 examples of Clever Design</h3>
<h3 class="sort">SORT</h3>
</div>
<div class="cards">
<Card/>
<Card/>
<Card/>
</div>
</section>

<style>
.examples{
	color: #353846;
	font-family: Inter;
	font-size: 1.5rem;
	font-style: normal;
	font-weight: 700;
	line-height: normal;
	letter-spacing: -0.015rem;
}
.sort{
	width: 3.4375rem;
	height: 1.25rem;
	color: #65697E;
	font-family: Inter;
	font-size: 1rem;
	font-style: normal;
	font-weight: 600;
	line-height: 1.25rem; /* 125% */
	letter-spacing: 0.22rem;
	text-transform: uppercase;
}
.carousel{
	display: inline-flex;
	align-items: flex-start;
	gap: 0.73456rem;
}
.card-heading{
	display: inline-flex;
	padding: 2rem 10rem;
	justify-content: space-around;
	border-bottom: 1px solid rgba(53, 56, 70, 0.15);
	background: #FFF;
	box-shadow: 0px -2px 17.1px 0px rgba(40, 38, 56, 0.25);
	display: flex;
	align-items: center;
	gap: 15.75rem;
	}
.cards{
	display:flex;
	flex-direction: column;
	align-items:center;
	gap: 3.5rem;

}
h1{
	color: #111115;
	font-family: Inter;
	font-size: 3.5rem;
	font-style: normal;
	font-weight: 800;
	line-height: normal;

}
h2{
	color: #65697E;
	text-align: center;
	font-family: Inter;
	font-size: 1.25rem;
	font-style: normal;
	font-weight: 500;
	line-height: 1.8125rem; /* 145% */

}
.nuggets-container { 
	background: #FFF;
	display:flex;
	flex-direction:column;
	row-gap:5rem;
}
</style>