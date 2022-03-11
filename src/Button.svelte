<script>
    export let type="default";
    export let mode;

</script>
<button class:inversed={mode==="inversed"} class="{type}"><slot/></button>

<style>
button {
    color: white;
    background: var(--default-color);
    padding: 1rem;
    border-radius: 12px;
    transition: all 0.3s;
    cursor: pointer;
}

.primary {
    background: var(--primary-color);
}

.primary:hover {
    color: var(--primary-color);
    background: var(--primary-font-color);
}

.secondary {
    background: var(--secondary-color);
}

.primary.inversed {
    color: var(--primary-color);
    background: var(--primary-font-color);
}

.secondary.inversed {
    color: var(--secondary-color);
    background: var(--primary-font-color);
}

.accent {
    background: var(--accent-color);
}

.ghost {
   background: var(--ghost-color);
   color: black;
}

.link {
    color: var(--primary-color);
    background: var(--primary-font-color);
}

</style>