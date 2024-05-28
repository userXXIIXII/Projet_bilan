<template>
        <section id="contact">
        <p class="section__text__p1">Entrez en communication</p>
        <h1 class="titre">Contactez moi</h1>
        <div class="contact-info-upper-container">

            <div class="contact-info-container">
                <img src="./assets/img/email-icon-2.png" 
                alt="email icon" 
                class="icon contact-icon">
                <p><a href="mailto:aarindeb2003@gmail.com">aarindeb2003@gmail.com</a></p>
            </div>

            <div class="contact-info-container">
                <img src="./assets/img/linkedin_icon.png" 
                alt="linkedIn icon" 
                class="icon contact-icon">
                <p><a href="www.linkedin.com/in/aarin-deb">LinkedIn</a></p>
            </div>

        </div>
    </section>

    <footer>
        <nav class="nav2">
            <div class="nav-liens-container">
                <ul class="nav-liens">
                    <li><a href="#apropos">A propos</a></li>
                    <li><a href="#experiences">Expériences</a></li>
                    <li><a href="#projets">Projets</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </div>
        </nav>
        <p>Copyright &#169; 2027 Aarin Deb. Tous droits réservés.</p>
    </footer>

</template>

<script>
    export default {
        name: 'contact'
    }
</script>

<style scoped>
    #contact a{
    color: white;
}

#contact{
    display: flex;
    justify-content: center;
    flex-direction: column;
    height: 70vh;
}

.contact-info-upper-container{
    display: flex;
    justify-content: center;
    border-radius: 2rem;
    border: rgb(53, 53, 53) 0.1rem solid;
    border-color: rgb(163, 163, 163);
    background-image: url(./assets/img/Theme/Theme\ NAV.jpg);
    margin: 2rem auto;
    padding: 0.5rem;
}

.contact-info-container{
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 0.5rem;
    margin: 1rem;
}

.contact-info-container p{
    font-size: larger;
}

.contact-icon {
    cursor: default;
}

/* FOOTER */

.nav2{
    background: none;
}

footer{
    height: 26vh;
    margin: 0 1rem;
}

footer p{
    text-align: center;
}
</style>