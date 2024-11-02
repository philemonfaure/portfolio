<button class="button body_font">
    <slot>Button</slot>
</button>

<style>
    .button {
        border: 0.5px solid var(--secondary);
        border-radius: 20px;
        background-color: var(--primary);
        color: var(--secondary);

        display: flex;
        flex-direction: row;
        flex-wrap: nowrap;
        align-items: center;
        align-content: stretch;
        justify-content: center;
        padding: 5px 30px 5px 30px;

        transition:
            background-color 0.3s ease,
            color 0.3s ease,
            border-radius 0.3s ease;
    }

    .button:hover {
        background-color: var(--secondary);
        color: var(--primary);
    }
</style>
