<script>
    export let label="";
    export let href="";
</script>

<li>
    <a href={href}>
            {label}
        <svg class="arrow-icon" width="20" height="20" viewBox="0 0 19 19" fill="">
                <path d="M11.2703 13.9599L14.49 10.7401C14.7712 10.4588 14.9292 10.0774 14.9292 9.67963C14.9292 9.28189 14.7712 8.90043 14.49 8.61913L11.2703 5.39938L10.2098 6.45988L12.6795 8.92963L4.4295 8.92963L4.4295 10.4296L12.6795 10.4296L10.2098 12.8994L11.2703 13.9599Z" fill="white"/>
        </svg> 
     </a>
</li>

<style>
    a {
        color: inherit;
        text-decoration: none;
        display: flex;
        justify-content: space-between;
    }

    a:hover {
    color: rgb(182, 182, 186);
    }

a:hover svg {
    transition: .35s;
    transform: rotate(-40deg);
}

</style>