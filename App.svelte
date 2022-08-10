<script>
  import Button from "/components/Button.svelte";
  import Logo from "/components/Logo.svelte";
  import Header from "/components/Header.svelte";
  import Footer from "/components/Footer.svelte";
</script>

<style>
  main {
    font-family: sans-serif;
    text-align: center;
    max-width: 960px;
  }
</style>

<main>
  <Header />
	<h1>Salut Max</h1>
	<h2>Ceci est ma première app Svelte</h2>
  <p>Il faut dire que je me suis basé sur un template Codesanbox. Mais j'ai fait des petites modifications.</p>
  <Button />
  <Footer />
</main>