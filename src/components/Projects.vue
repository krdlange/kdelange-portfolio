<template>
    <section class="projects-container" id="projects">
        <div class="section-title">
            <h2>Projects</h2>
        </div>
        <div class="folder-container">
            <div class="arcadia-folder">
                <div class="arcadia-content">
                    <div class="project-name">
                        <h3><sup>01</sup>Arcadia</h3>
                    </div>
                    <div class="project-description">
                        <p>A web application that helps gamers find & discover new games, save them to
                            their personal collection, and track their progress and ratings within the app.</p>
                    </div>
                    <div class="project-bottom">
                        <div class="tools">
                            <p>React.js, MySQL</p>
                        </div>
                        <div class="link-to-project"><a href="https://github.com/krdlange/arcadia"><button
                                    class="text-link">View on GitHub</button></a></div>
                    </div>
                </div>


            </div>

            <div class="rh-folder">
                <div class="rh-content">
                    <div class="project-name">
                        <h3><sup>02</sup>Recipe Haul</h3>
                    </div>
                    <div class="project-description">
                        <p>An e-commerce web application that integrates recipe search with grocery shopping.</p>
                    </div>
                    <div class="project-bottom">
                        <div class="tools">
                            <p>React.js, MySQL</p>
                        </div>
                        <div class="link-to-project"><a href="https://github.com/CodeOp-tech/FSPT12-final-project"><button
                                    class="text-link">View on GitHub</button></a></div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>


<script>
export default {
    name: 'Projects'
}

</script>

<style>
.projects-container {
    width: 100%;
    min-height: 100vh;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
}

.folder-container {
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
}

.arcadia-folder {
    background-image: url(src/assets/folder-1.png);
    background-position: top left;
    background-repeat: no-repeat;
    background-size: contain;
    display: flex;
    max-width: 400px;
    height: 300px;
    margin-right: 16px;
}

.arcadia-content {
    display: flex;
    flex-direction: column;
    margin: 0 20px;
    justify-content: space-between;
}

.rh-folder {
    background-image: url(src/assets/folder-2.png);
    background-position: top left;
    background-repeat: no-repeat;
    background-size: contain;
    display: flex;
    max-width: 400px;
    height: 287px;
}

.rh-content {
    display: flex;
    flex-direction: column;
    margin: -2px 20px;
    justify-content: space-between;
}

sup {
    font-size: 0.8rem;
    margin-right: 8px;
    vertical-align: super;
}

.project-bottom {
    display: flex;
    align-items: center;
    justify-content: space-between;
    align-items: baseline;
    padding-bottom: 80px;
}

a .text-link {
    background: none;
    border: none;
    padding: 0;
    font-size: 0.875rem;
    color: #000;
    text-decoration: underline;
    cursor: pointer;
}

/* if screen is greater than 768 */
@media only screen and (min-width: 820px) {
    .folder-container {
        display: flex;
        flex-direction: row;
        align-items: baseline;
        width: 100%;
        height: 550px;
        margin: auto;
    }

    .project-bottom {
        padding-bottom: 24px;
    }
}
</style>