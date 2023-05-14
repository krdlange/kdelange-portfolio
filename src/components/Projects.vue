<template>
    <h2>Projects</h2>
    <section class="projects-container">

        <div class="arcadia-folder">
            <div class="svg-container">
                <svg class="svg-arcadia" height="287" viewBox="0 0 409 287" fill="none" xmlns="http://www.w3.org/2000/svg">
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
/* .projects-container {
    margin-top: 30px;
} */

.arcadia-folder {
    display: flex;
    justify-content: center;
    margin-right: 16px;
}

.rh-folder {
    display: flex;
    justify-content: center;
}

.svg-container {
    width: 100%;
    display: flex;
    justify-content: center;
    /* max-width: 409px; */
    /* set the maximum width of the SVG */
}

.svg-arcadia {
    width: 340px;
}

.svg-rh {
    width: 340px;
}

.arcadia-content {
    display: flex;
    flex-direction: column;
    position: absolute;
    margin: 34px 16px;
    max-width: 300px;
    width: 100%;
}

.rh-content {
    display: flex;
    justify-content: center;
    flex-direction: column;
    position: absolute;
    margin: 34px 16px;
    max-width: 300px;
    width: 100%;
}

.project-name h3 {
    margin: 0;
}

.project-description p {
    margin: 40px 0 0 0;
}

sup {
    font-size: 0.8rem;
    margin-right: 8px;
    vertical-align: super;
}

/* if screen is greater than 768 */
@media only screen and (min-width: 780px) {
    .projects-container {
        display: flex;
        flex-direction: row;
        max-width: 860px;
        width: 100%;
        justify-content: space-between;
        margin: 160px auto;
    }

    .svg-arcadia {
        width: 409px;
    }

    .arcadia-content {
        margin: 14px 26px;
        max-width: 348px;
        width: 100%;
    }

    .svg-rh {
        width: 409px;
    }

    .rh-content {
        margin: 14px 26px;
        max-width: 348px;
        width: 100%;
    }
}

/* 

.project-name {
    position: absolute;
    width: inherited;
    margin-left: 24px;
    font-size: 1.2rem;
    color: #333;
}


.project-description {
    position: absolute;
    top: 80px;
    width: 300px;
    margin-left: 24px;
    font-size: 1.2rem;
    color: #333;
}

sup {
    font-size: 0.8rem;
    margin-right: 8px;
    vertical-align: super;
}

.rh-folder {
    display: flex;
}
@media only screen and (min-width: 768px) {
    .project-folder {
        max-width: 500px;
        width: 100%;
    }
} */
</style>