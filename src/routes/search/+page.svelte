<div id="search">
    <input placeholder="Search for questions here!">
    <div id="params">
        <div id="parambox">
            <p id="paramheader">Category</p>
            <select id="selectbox">
                <!-- TODO -->
                <option>PLACEHOLDER</option>
            </select>
        </div>
        <div id="parambox">
            <p id="paramheader">Search Type</p>
            <select id="selectbox">
                <!-- TODO -->
                <option>PLACEHOLDER</option>
            </select>
        </div>
        <div id="parambox">
            <p id="paramheader">Difficulty</p>
            <select id="selectbox">
                <!-- TODO -->
                <option>PLACEHOLDER</option>
            </select>
        </div>
    </div>
    <div id="params">
        <div id="parambox">
            <p id="paramheader">Subcategory</p>
            <select id="selectbox">
                <!-- TODO -->
                <option>PLACEHOLDER</option>
            </select>
        </div>
        <div id="parambox">
            <p id="paramheader">Question Type</p>
            <select id="selectbox">
                <!-- TODO -->
                <option>PLACEHOLDER</option>
            </select>
        </div>
        <div id="parambox">
            <p id="paramheader">Tournament</p>
            <select id="selectbox">
                <!-- TODO -->
                <option>PLACEHOLDER</option>
            </select>
        </div>
    </div>
    
</div>

<style>
    #search {
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
    }
    #parambox {
        background-color: gray;
        border-radius: 0.5rem;
        /* padding: 0.4rem; */
    }
    #paramheader {
        background-color: black;
        opacity: 0.5;
        padding: 0.5rem;
        margin: 0;

    }
    #params {
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: space-around;
        width: 100%;
        height: 100%;
    }
    #selectbox{
        margin: 1rem;
        margin-top: 0.8rem;
    }
</style>