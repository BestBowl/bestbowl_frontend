<div id="search">
    <div id="widget">
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
    <div id="results">
        
    </div>
</div>

<style>
    #search {
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        width: 100%;
        height: 100%;
    }
    #widget {
        display: flex;
        flex-direction: column;

    }
    #results {
        min-height: 40%;
    }
    #parambox {
        border: 1px solid lightgray;
        border-radius: 0.5rem;
        margin: 1rem;
        /* padding: 0.4rem; */
    }
    #paramheader {
        color: black;
        opacity: 0.7;
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