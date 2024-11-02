<div class="carrousel">
    <div class="card"></div>
    <div class="card"></div>
    <div class="card"></div>
</div>

<style>
    .carrousel {
        display: flex;
        overflow-x: auto;
        gap: 40px;

        scroll-snap-type: both mandatory;
    }

    .card {
        flex-basis: 90%;
        flex-shrink: 0;
        height: 500px;
        background-color: var(--tertiary);

        scroll-snap-align: center;

        border: 0.5px solid var(--lightgrey);
        border-radius: 20px;
        background-color: var(--darkgrey);
        color: var(--secondary);
    }
</style>
