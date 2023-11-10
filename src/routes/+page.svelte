<script>
    // import { onMount } from "svelte";
 
    
</script>
<div id="main-menu">
    <button id="main-button" on:click={() => window.location.href = "/search"}>
    <img src="searchicon.png" alt="Search for cards">
    <p>SEARCH</p>
    </button>
    <button id="main-button" on:click={() => window.location.href = "/practice"}>
    <img src="practiceicon.png" alt="Practice cards">
    <p>PRACTICE</p>
    </button>
    <button id="main-button" on:click={() => window.location.href = "/add"}>
    <img src="addicon.png" alt="Add cards">
    <p>SEARCH</p>
    </button>
</div>

  
  <style>
    #main-menu {
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: row;
    }
    #main-button {
      height: 15ch;
      width: 15ch;
      margin: 2rem;
    }
  </style>