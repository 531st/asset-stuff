<script>
    import Navbar from "../components/Navbar.svelte";
</script>

<div class="container">
    
</div>
<div class="wrap">
    <Navbar/>
    <slot/>
</div>


<style>
    .container{
        background-image: url("../lib/img/cog.png");
        background-size: 70px;
        position:absolute;
        inset: 0;
        isolation: isolate;
    }

    .container:after{
        content: ' ';
        position: absolute;
        inset: 0;
        background-color: rgb(213, 211, 211);
        z-index: -1;
        opacity: 96%;
    }

    .wrap{
        position: relative;
    }
    
</style>