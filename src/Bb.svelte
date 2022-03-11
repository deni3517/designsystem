<script>
import Button from "./Button.svelte";
import Badge from "./Badge.svelte";</script>
<section>
<div class="button"><Button>INBOX</Button></div>
<div class="badge">
<Badge type="secondary">99+</Badge></div>
</section>
<style>
    section {
        margin:20px;
        width: fit-content;

        }
    .badge {
display: flex;
flex-direction: row;
justify-content: end;
margin-top: -80px;
margin-right: -20px;
        }

</style>