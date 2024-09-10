<script>
    export let label="";
    export let href="";
</script>

<li>
    <a href={href}>
        {label}
    </a>
</li>

<style>
    a {
        color: inherit;
        text-decoration: none;
    }
</style>