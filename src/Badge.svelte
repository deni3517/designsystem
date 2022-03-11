<script>
    export let type="default";
    export let mode;

</script>
<p class:inversed={mode==="inversed"} class="{type}"><slot/></p>

<style>


p {
    color: white;
    background: var(--default-color);
    width: fit-content;
    padding-left: 0.6rem;
    padding-right: 0.6rem;
    padding-top: 0.2rem;
    padding-bottom: 0.2rem;
    border-radius: 12px;
    
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