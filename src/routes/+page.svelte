<script>
  import Header from '$lib/Header.svelte'
  import Footer from '$lib/Footer.svelte'
  import Nav from '$lib/Nav.svelte' 
  import Card from '$lib/Card.svelte'
  import Image from '$lib/Image.svelte';
</script>

<Header />
<Nav />

<main>
  <h2>About Me</h2>

  <div class="column is-four-fifths"><p>Welcome to my site. My name is Beth Savage and I take level 2 digi. This is my site about me</p></div>
  <div class="column is-one-fifth"><Image src= "Beth-with-Clara.jpg"/></div>
</main>
<Card />
<Footer />
