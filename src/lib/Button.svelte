<script>
    export let link = '/';

    export let className = 'primary';
    export let label = 'Boton';
</script>

<a href={link} class={className}>{label}</a>

<style>
    a{
        display: inline-block;
        color: black;
        background-color: #ffe644;
        padding: 1rem 3rem;
        border-radius: 3rem;
        letter-spacing: .5px;
        transition: background-color 1s ease;
    }
    a:hover {
        transition: background-color 300ms ease;
        background-color: #ffed77;
    }

</style>