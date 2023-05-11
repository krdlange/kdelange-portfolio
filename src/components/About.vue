<template>
    <section id="intro">
        <div class="about-container">
            <div class="about-left">
                <div class="title">
                    <h2>
                        Mabuhay! 🇵🇭
                    </h2>
                </div>
                <div class="description">
                    <p>
                        I'm Kriska, a Pinoy front-end developer based in the Netherlands.
                    </p>
                    <p>
                        My experience in Marketing and UX/UI design led me to pursue my interest in becoming a front-end
                        developer.
                        I attended a full-stack development program at codeOp to learn the fundamentals of front-end and
                        back-end
                        development and to gain hands-on experience in modern front-end frameworks like React and Vue, and
                        back-end
                        technologies such as Node.js, Express.js, RestAPI, and MySQL. Throughout my journey, I have
                        developed a
                        passion for creating dynamic and responsive web applications that provide intuitive and engaging
                        user
                        experiences.
                    </p>
                    <p>
                        I'm always excited to explore new technologies and work with people who share my passion for
                        creativity
                        and
                        innovation. Take a look at my projects and let's connect!
                    </p>
                </div>
                <div class="button-group">
                    <button class="about-button">
                        View LinkedIn
                    </button>

                    <button class="about-button">
                        View Github
                    </button>

                    <button class="about-button">
                        View Resume
                    </button>
                </div>
            </div>
            <div class="about-right">
                <div class="img-container">
                    <img src="src/assets/profile-img.jpeg" alt="Image description" class="my-image">
                </div>
            </div>
        </div>

    </section>
</template>

<script>
export default {
    name: 'About'
}
</script>

<style>
.about-container {
    display: flex;
    margin: 80px 20px;
    justify-content: center;
  align-items: center;

}

.about-left {
    margin-right: 60px;
}

.button-group {
    display: flex;
    margin-top: 46px;
}

.about-button {
    height: 40px;
    padding: 10px 20px;
    border: none;
    border-radius: 4px;
    background-color: #282828;
    color: #fff;
    font-size: 0.875rem;
    cursor: pointer;
    margin-right: 16px;
}

.my-image {
    width: 200px;
    border: 1px solid #25245A;
    border-radius: 4px;
    padding: 2px;
}
</style>