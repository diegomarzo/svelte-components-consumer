<script>
  import WelcomeMessage from "@diegomarzo/svelte-components"
  import StylishButton from "@diegomarzo/svelte-components"
</script>

<main>
  <WelcomeMessage name="World"/>
  <StylishButton bgColor="pink" txtColor="darkblue" message="I'm very stylish"></StylishButton>
</main>

<style>
  main {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
</style>
