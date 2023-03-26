<template>
    <footer id="footer">
        <p>Make Your Burger &copy; {{ new Date().getFullYear() }}</p>
    </footer>
</template>

<script >

    export default {
        name: 'Footer'
    }

</script>

<style scoped>

    #footer {
        height: 450px;
        background-color: #222;
        border-top: 4px solid #111;
        color: #fcba03;
        display: flex;
        align-items: center;
        justify-content: center;
        width: 100%;
    }

</style>