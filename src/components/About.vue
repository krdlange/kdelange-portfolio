<template>
    <section id="intro">
        <div class="about-container">
            <div class="title">
                Mabuhay! 🇵🇭
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
                    technologies such as Node.js, Express.js, RestAPI, and MySQL. Throughout my journey, I have developed a
                    passion for creating dynamic and responsive web applications that provide intuitive and engaging user
                    experiences.
                </p>
                <p>
                    I'm always excited to explore new technologies and work with people who share my passion for creativity
                    and
                    innovation. Take a look at my projects and let's connect!
                </p>
            </div>
            <div class="button-group">
                <div class="button-1">
                    <button>
                        View LinkedIn
                    </button>
                </div>
                <div class="button-2">
                    <button>
                        View Github
                    </button>
                </div>
                <div class="button-3">
                    <button>
                        View Resume
                    </button>
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
    margin: 20px;
}

.button-group {
    display: flex;
    margin-top: 46px;
}

.button-group button {
    height: 40px;
    padding: 10px 20px;
    border: none;
    border-radius: 4px;
    background-color: #282828;
    color: #fff;
    font-size: 18px;
    cursor: pointer;
    margin-right: 16px;

}
</style>