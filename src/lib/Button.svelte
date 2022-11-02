<script>
    export let link = '/';
    export let label = 'Boton';
</script>

<a href={link}>{label}</a>

<style>
    a{
        display: inline-block;
        color: black;
        background-color: #ffe644;
        padding: 1rem 3rem;
        border-radius: 3rem;
        letter-spacing: .5px;
    }
    a:hover {
        
    }

</style>