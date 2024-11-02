<script>
    import Button from "../components/button.svelte";
    import Logo from "$lib/assets/logo.png";
</script>

<div class="header">
    <p class="logo body_font">Philemon Faure</p>
    <div class="content">
        <div class="links">
            <a href="" class="body_font">Presentation</a>
            <a href="" class="body_font">Projets</a>
        </div>
        <Button>Contacter</Button>
    </div>
</div>

<style>
    .header {
        position: fixed;
        top: 0;
        left: 0;
        right: 0;
        background: var(--primary);

        display: flex;
        flex-direction: row;
        flex-wrap: nowrap;
        align-items: center;
        align-content: stretch;
        justify-content: start;
        padding: 20px 40px;
    }

    .logo {
        font-size: 1.1em;
        font-weight: 900;
    }

    .content {
        height: 100%;
        display: flex;
        flex-direction: row;
        flex-wrap: nowrap;
        align-items: center;
        align-content: stretch;
        justify-content: end;
        flex: 1;
        gap: 40px;
    }

    .links {
        height: 100%;
        display: flex;
        flex-direction: row;
        flex-wrap: nowrap;
        align-items: center;
        align-content: stretch;
        justify-content: end;
        gap: 30px;
        flex: 1;
    }
</style>
