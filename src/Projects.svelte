<script>
    import Card from './Card.svelte'

</script>

<main>
    <Card title="Website" desc="Created a website with subdomains using svelte-routing."/>
    <Card title="TicTacToe" desc="Made a TicTacToe game using svelte"/>
    <Card title="Library Managment System" desc="Made a library managment system in Java"/>
    <Card title="Alarm App" desc="Made an alarm app using MIT App Inventor" />
</main>

<style>
    main {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        margin: 20px auto;
    }
</style>
