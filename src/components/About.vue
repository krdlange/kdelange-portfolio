<template>
    <section id="intro" class="intro-container">
        <div class="intro-content">
            <div class="img-container">
                <img src="src/assets/profile-img-min.jpg" alt="profile-img" class="my-image">
            </div>
            <div class="intro-text">
                <h2>Mabuhay! 🇵🇭</h2>
                <p>I'm Kriska, a Pinoy front-end developer based in the Netherlands.<br><br>
                    My experience in Marketing and UX/UI design led me to pursue my interest
                    in becoming a front-end developer. I attended a full-stack development
                    program at codeOp to learn the fundamentals of front-end and back-end
                    development and to gain hands-on experience in modern front-end
                    frameworks like React and Vue, and back-end technologies such as
                    Node.js, Express.js, RestAPI, and MySQL. Throughout my journey, I have
                    developed a passion for creating dynamic and responsive web applications
                    that provide intuitive and engaging user experiences.
                    <br><br>
                    I'm always excited to explore new technologies and work with people who
                    share my passion for creativity and innovation. Take a look at my
                    projects and let's connect!
                </p>
                <div class="buttons-container">
                    <a href="https://www.linkedin.com/in/kriskadl/">
                        <button class="primary-button">View LinkedIn </button>
                    </a>
                    <a href="https://github.com/krdlange">
                        <button class="primary-button">View Github</button>
                    </a>
                    <a href="https://drive.google.com/file/d/1WCBpxCFxjp-pgVqnz8uar7NLLM3WHzuc/view?usp=share_link"
                        target="_blank" rel="noreferrer">
                        <button class="primary-button">View Resume</button>
                    </a>

                </div>

            </div>


        </div>
    </section>
</template>

<script>
import { gsap } from 'gsap'

// Wait for the document to load
document.addEventListener("DOMContentLoaded", () => {
    // Select the contact container element
    const introContainer = document.querySelector(".intro-container");

    // Animate the contact container
    gsap.from(introContainer, {
        opacity: 0,
        y: 50,
        duration: 2,
        ease: "power2.out",
    });
});
</script>

<style>
.intro-container {
    display: flex;
    justify-content: center;
    align-items: baseline;
    min-height: 100vh;
    height: 100vh;
    width: 100%;
}

.intro-content {
    padding: 8px;
}

.my-image {
    width: 35%;
    max-width: 230px;
    border: 1px solid #25245a;
    border-radius: 4px;
}


.buttons-container {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    margin: 24px 0px;
}

@media only screen and (min-width: 768px) {
    .intro-content {
        display: flex;
        flex-direction: row-reverse;
        justify-content: space-between;
        align-items: center;
        padding: 40px;
        margin-top: 40px;

    }

    .img-container {
        width: 30%;
        display: flex;
        height: fit-content;
        justify-content: center;
        align-items: center;
    }

    .my-image {
        width: 100%;
    }

    .intro-text {
        width: 60%;
    }
}
</style>