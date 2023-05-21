<template>
    <section id="contact" class="contact-container">
        <div class="contact-title">
            <h2>Contact</h2>
        </div>
        <div class="contact-content">
            <div class="img-content">
                <img class="img-contact" src="/public//assets/getintouch.png">
            </div>
            <div class="contact-form">
                <div class="form-container">
                    <form target="_blank" action="https://formsubmit.co/kriska.delange@gmail.com" method="POST">
                        <div class="form-group">

                            <div class="name">
                                <input type="text" name="name" class="form-control" placeholder="Full Name" required>
                            </div>
                            <div class="email">
                                <input type="email" name="email" class="form-control" placeholder="Email Address" required>
                            </div>
                            <div>
                                <textarea placeholder="Your Message" class="form-control" name="message" rows="10"
                                    required></textarea>
                            </div>

                        </div>
                        <div class="form-btn-container">
                            <button type="submit" class="primary-button">Submit</button>
                        </div>

                    </form>
                </div>
            </div>
        </div>


    </section>
</template>

<script>
export default {
    name: 'Contact'
}


</script>

<style>
.contact-container {
    width: 100%;
    min-height: 100vh;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
}

.contact-content {
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
}

.img-content {
    display: flex;
    justify-content: flex-start;
    margin-bottom: 16px;
}

.img-contact {
    width: 280px;
}

.contact-form {
    width: 90%;
}

.form-container h2 {
    font-size: 24px;
    margin-bottom: 20px;
    text-align: left;
}

.form-control,
textarea {
    width: 100%;
    padding: 10px;
    border: 1px solid #333;
    border-radius: 4px;
    font-size: 16px;
    margin-bottom: 4px;
    background-color: #F0F1EB;
    color: #fff;
}

textarea {
    resize: vertical;
}

@media only screen and (min-width: 780px) {
    .contact-container {
        width: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
    }

    .contact-form {
        width: 100%;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .form-container {
        width: 60%;
    }

    .contact-content {
        display: flex;
        flex-direction: row;
        width: 100%;
        height: 600px;
    }

    .img-content {
        display: flex;
        align-self: center;
        width: 60%;
    }

    .img-contact {
        width: 340px;
    }
}
</style>