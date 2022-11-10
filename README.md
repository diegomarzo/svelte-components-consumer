# Svelte Components Consumer

This is just a simple playground to see how we use the Svelte Components

The steps are very basic, 

**Install the dependency**

`npm install -D @diegomarzo/svelte-components`

**And use them!**
```
<script>
    import {WelcomeMessage, StylishButton} from "@diegomarzo/svelte-components"
</script>

<main>
    <WelcomeMessage name="Planet"/>
    <StylishButton bgColor="goldenrod" txtColor="purple" message="I'm even more stylish"/>
</main>

<style>
    main {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
</style>
```
