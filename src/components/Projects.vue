<template>
    <section class="projects-container">
        <div class="title">
             <h2>Projects</h2>
        </div>
           <div class="arcadia-folder">
            <div class="svg-container">
               <svg class="folder-arcadia" width="409" height="287" viewBox="0 0 409 287" fill="none"
                xmlns="http://www.w3.org/2000/svg">
                <path
                    d="M401 286.5H8.00001C3.85787 286.5 0.5 283.142 0.5 279V8.00001C0.5 3.85787 3.85787 0.5 8 0.5H160.5C164.642 0.5 168 3.85786 168 8V45.8125C168 50.5069 171.806 54.3125 176.5 54.3125H401C405.142 54.3125 408.5 57.6704 408.5 61.8125V279C408.5 283.142 405.142 286.5 401 286.5Z"
                    fill="#F0F1EB" stroke="black" />
            </svg> 
            </div>
            

            <div class="project-container">
             <div class="project-name">
                <h3 class=""><sup>01</sup>Arcadia</h3>
            </div>
            <div class="project-description">
                                <p>A web application that helps gamers find & discover new games, save them to
                    their personal collection, and track their progress and ratings within the app.</p>
            </div>   
            </div>
            

            </div> 

            <div class="rh-folder">
                <svg width="409" height="287" viewBox="0 0 409 287" fill="none" xmlns="http://www.w3.org/2000/svg">
  <path d="M401 286.5H8.00001C3.85787 286.5 0.5 283.142 0.5 279V8.00001C0.5 3.85787 3.85787 0.5 8 0.5H203.5C207.642 0.5 211 3.85786 211 8V45.8125C211 50.5069 214.806 54.3125 219.5 54.3125H401C405.142 54.3125 408.5 57.6704 408.5 61.8125V279C408.5 283.142 405.142 286.5 401 286.5Z" fill="#F0F1EB" stroke="black" />
</svg>
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

} */

.arcadia-folder {
    position: relative;
}

.folder-arcadia {
    position: absolute;
    left: 0;
    top: 0;
}

.project-container {
    display: flex;
    position: absolute;
    /* width: inherited; */
}

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
}
</style>