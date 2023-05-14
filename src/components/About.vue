<template>
    <section class="intro-container">
        <div class="top">
           <div class="img-container">
            <img src="src/assets/profile-img.jpeg" alt="Image description" class="my-image">
        </div>
        <div class="intro-text">
        <h2>Mabuhay! 🇵🇭</h2>
        <p>I'm Kriska, a Pinoy front-end developer based in the Netherlands.</p>            
        </div> 
        </div>
        

        <p>
            My experience in Marketing and UX/UI design led me to pursue my interest
            in becoming a front-end developer. I attended a full-stack development
            program at codeOp to learn the fundamentals of front-end and back-end
            development and to gain hands-on experience in modern front-end
            frameworks like React and Vue, and back-end technologies such as
            Node.js, Express.js, RestAPI, and MySQL. Throughout my journey, I have
            developed a passion for creating dynamic and responsive web applications
            that provide intuitive and engaging user experiences.
        </p>
        <p>
            I'm always excited to explore new technologies and work with people who
            share my passion for creativity and innovation. Take a look at my
            projects and let's connect!
        </p>
        <div class="buttons">
            <button>View LinkedIn</button>
            <button>View Github</button>
            <button>View Resume</button>
        </div>
    </section>
</template>

<script>
</script>

<style>
.intro-container {
    display: flex;
        flex-wrap: wrap;
        align-items: center;
        justify-content: space-between;
        /* max-width: 960px; */
        padding: 40px 20px;
}

.top {
    display: flex;
    margin-bottom: 8px;
}
.intro-text {
    display: flex;
    flex-direction: column;
    align-self: center;
    width: 240px;
    margin-left: 24px;
}
/* .img-container {
    margin: 0 auto;
} */

.my-image {
    width: 100%;
    max-width: 130px;
    border: 1px solid #25245a;
    border-radius: 4px;
    padding: 2px;
    margin-top: 20px;
}

.buttons {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    margin: 24px 0px;
}

button {
    padding: 10px 16px;
    border: none;
    border-radius: 4px;
    background-color: #282828;
    color: #fff;
    font-size: 0.875rem;
    cursor: pointer;
}

@media only screen and (min-width: 768px) {
    .intro-container {
        max-width: 500px;
        width: 100%;
        margin: 20px auto;
    }
}
</style>