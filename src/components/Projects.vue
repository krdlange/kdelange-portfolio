<template>
    <section id="projects">
        <h2>Projects</h2>
        <div class="projects-container">
            <div class="arcadia-folder">
                <div class="svg-container">
                    <svg class="svg-arcadia" height="287" viewBox="0 0 409 287" fill="none"
                        xmlns="http://www.w3.org/2000/svg">
                        <path
                            d="M401 286.5H8.00001C3.85787 286.5 0.5 283.142 0.5 279V8.00001C0.5 3.85787 3.85787 0.5 8 0.5H160.5C164.642 0.5 168 3.85786 168 8V45.8125C168 50.5069 171.806 54.3125 176.5 54.3125H401C405.142 54.3125 408.5 57.6704 408.5 61.8125V279C408.5 283.142 405.142 286.5 401 286.5Z"
                            fill="#F0F1EB" stroke="black" />
                    </svg>
                </div>


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
                <div class="svg-container">
                    <svg class="svg-rh" height="287" viewBox="0 0 409 287" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path
                            d="M401 286.5H8.00001C3.85787 286.5 0.5 283.142 0.5 279V8.00001C0.5 3.85787 3.85787 0.5 8 0.5H203.5C207.642 0.5 211 3.85786 211 8V45.8125C211 50.5069 214.806 54.3125 219.5 54.3125H401C405.142 54.3125 408.5 57.6704 408.5 61.8125V279C408.5 283.142 405.142 286.5 401 286.5Z"
                            fill="#F0F1EB" stroke="black" />
                    </svg>
                </div>


                <div class="rh-content">
                    <div class="project-name">
                        <h3 class=""><sup>02</sup>Recipe Haul</h3>
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
    height: 100vh;
    margin: 60px auto;
}

.arcadia-folder {
    display: flex;
    justify-content: center;
    margin-bottom: 16px;
}

.rh-folder {
    display: flex;
    justify-content: center;
}

.arcadia-content {
    display: flex;
    flex-direction: column;
    position: absolute;
    width: 350px;
    margin-top: 20px;
}

.rh-content {
    display: flex;
    flex-direction: column;
    position: absolute;
    width: 350px;
    margin-top: 20px;
}

.project-name h3 {
    margin: 2px;
}

.project-description {
    margin-top: 30px;
    margin-bottom: 50px;
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
@media only screen and (min-width: 780px) {
    .projects-container {
        display: flex;
        justify-content: space-around;
        align-self: baseline;
        margin-top: 130px;
    }
}
</style>