
<script>


</script>
<div class="default-layout">
    <slot/>
    <div id="footer">
        <a href="/about">About</a>
        <a href="/">Home</a>
    </div>
</div>

<style>
    .default-layout {
        width: 100%;
        height: 100vh;
        padding: 0;
    }
    #footer {
        bottom: 0;
        transform: scale(0.95); 
        /* i dont know how to get the stupid scroll bars to go away but this hack works^^ */
        left: 0;
        display: flex;
        position: absolute;
        border: 0px solid white;
        width: 100%;
        height: 2rem;
        padding: 0.2rem;
        margin: 0;
        display: flex;
        justify-content: space-around;
        

    }
</style>