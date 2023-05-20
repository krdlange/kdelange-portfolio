<template>
    <section class="contact-container">
        <div class="contact-title">
            <h2>Contact</h2>
        </div>
        <div class="contact-content">
            <div class="img-content">
                <img class="img-contact" src="src/assets/getintouch.png">
            </div>
            <div class="contact-form">
                <div class="form-container">
                    <h2>Send an email</h2>
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
                            <button type="submit" class="primary-button">Submit Form</button>
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
    height: 100vh;
    margin: 0 auto;
}

.contact-content {
    margin: 80px 30px 30px;
}

.img-content {
    display: flex;
    justify-content: center;
    margin-bottom: 16px;
}

.img-contact {
    width: 340px;
}

.form-container h2 {
    font-size: 24px;
    margin-bottom: 20px;
    text-align: left;
}

.form-control {
    width: 100%;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 4px;
    font-size: 16px;
    margin-bottom: 4px;
}

textarea {
    width: 100%;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 4px;
    font-size: 16px;
    resize: vertical;
}



@media only screen and (min-width: 780px) {
    .contact-container {
        display: flex;
        flex-direction: column;
        width: 100%;
    }

    .contact-form {
        width: 30%;
        display: flex;
        align-items: center;

    }

    .contact-content {
        display: flex;
        flex-direction: row;
        width: 100%;
        height: 100vh;
    }

    .img-content {
        display: flex;
        align-self: center;
        width: 60%;
    }


}
</style>