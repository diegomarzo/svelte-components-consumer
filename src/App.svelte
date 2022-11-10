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
