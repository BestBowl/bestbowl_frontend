
<div id="about">
    <h2>What is BestBowl?</h2>
    <p>BestBowl is inspired by Protobowl, and is meant to be similar to Anki and other SRS programs in functionality, while being specialized for quizbowl purposes. </p>

    <h3>Where are these questions sourced?</h3>
    <div id="sameline"> 
        <p>These questions were taken straight from</p> <a href="http://nocard.org"> nocard.org</a> <p>
            
        </p>
        <!-- <br> -->
    </div>
    <p>After filtering out the non-standard ones, they were put through a program to enhance them. In brief, this program adds a picture from Wikipedia if possible onto the flashcard, and creates a linked LLM-generated "inverted" card, which has the exact same information as the original flashcard, but with the answer and question switched. (these inverted cards can be disabled, they're completely optional). </p>
    <h2>Contact</h2>
    <a href="https://github.com/ironon">Github</a>
    <!-- <p>Discord: ironwastaken</p> -->
</div>
    
<style>
    #about{ 
        display: flex;
        justify-content: center;
        flex-direction: column;
        align-items: center;
    }
    #sameline {
        display: flex;
        margin-bottom: 1rem;
    }
    p, a {
        margin: 0;
        margin-right: 0.3rem;
        /* text-align: center; */
    }
    #about {
        padding-right: 12rem;
        padding-left: 12rem;
    }
</style>