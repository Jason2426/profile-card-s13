
<script>
    import '../styles/global.css'
    import Description from '../lib/components/Description.svelte';
    import Link from '../lib/components/Links.svelte';
    /** @type {import('./$types').PageData} */
    // export let data;

</script>

<main>
    <section class="about-me">
        <h1>Jason Wong, Poey Yie <strong>[王培宜]</strong></h1>
        <div class="description-layout">
            <Description
                label="I’m a junior UX/UI designer , and currently diving into front-end development to broaden my creative skills. I’m passionate about design, deeply inspired by creative developers, aspiring to become one myself one day."
            />
            <Description
                label="I love traveling to new places, as it fuels my curiosity and inspires my creativity in both design and life."
            />
        </div>
    </section>
    <section class="contact-and-others">
        <h3>[Contact]</h3>
        <section class="contact">
            <ul>
                <Link
                    label="LinkedIn"
                    href="https://www.linkedin.com/in/jason-wong-24b37b243/"
                />
                <Link
                    label="Mail"
                    href="mailto:jason.jpy.wong@gmail.com"
                />
                <Link
                    label="Instagram"
                    href="https://www.instagram.com/jasonw.2004/"
                />
                <Link
                    label="Discord"
                    href=""
                />
            </ul>
        </section>
        <section class="others">
            <h3>[Others]</h3>
            <ul>
                <Link
                label="Github"
                href="https://github.com/Jason2426"
            />
            <Link
                label="Spotify"
                href="https://open.spotify.com/user/jason0448?si=031c7377ca80493a"
            />
            <Link
                label="Reddit"
                href="/"
            />
            <Link
                label="Skincare routine"
                href="/"
            />
            </ul>
        </section>
    </section>
    <section>
        <span>Portfolio Coming Soon</span>
    </section>
</main>

<!-- {#if data.people}
    {#each data.people as person}
        <h1>{person.name}</h1>
    {/each}
{/if} -->