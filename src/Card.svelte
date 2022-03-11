<script>
    	import Badge from "./Badge.svelte";
        import Button from "./Button.svelte";

</script>
<section class="card-component">
    <div id="green"></div>
    <img src="/images/nike.jpg" alt="nike logo" width="350px">
<div id="title"><h3>Shoes!</h3> <Badge type="secondary">NEW</Badge></div>

   <div class="content"> <p>If a dog chews shoes whose shoes does he choose?</p>
   <div class="category-container"> 
       <p class="category">Fashion</p>
       <p class="category">Products</p>
</div>
<div class="buy-now">
    <Button type="primary">BUY NOW</Button></div>
</section>

<!--<Button type="primary" mode="inversed">Primary</Button>-->

<style>
  
    h3 {
        padding-left: 20px;

    }
    .content {
        padding-left: 20px;
        padding-right: 20px;
        padding-bottom: 20px;
    }
    p {
        font-size: 14px;
    }

    img {
  border-radius: 12px 12px 0px 0px;
    }
.card-component {
    border-radius: 12px;
    width: fit-content;
    box-shadow: 2px 2px 10px 2px #888888;
    margin-top: 20px;
}

.buy-now {
    display: flex;
    flex-direction: row;
    justify-content: flex-end;
}

.category-container {
    display: flex;
    flex-direction: row;
    gap: 0.5rem;
}

.category {
border: 1px solid black;
border-radius: 12px;
padding: 0 0.5rem 0 0.5rem;
}
    #title {
        display: flex;
        gap: 10px;
    }


</style>