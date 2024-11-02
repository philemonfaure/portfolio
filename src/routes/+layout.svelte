<script>
    import Header from "../blocks/header.svelte";
</script>

<svelte:head>
    <link rel="stylesheet" type="text/css" href="./src/lib/global.css" />
</svelte:head>

<Header />
<div class="page_content">
    <slot />
</div>

<style>
    .page_content {
        display: flex;
        flex-direction: column;
        flex-wrap: nowrap;
        align-items: left;
        align-content: stretch;
        justify-content: start;
        padding: 80px 40px;
        gap: 40px;
    }
</style>
