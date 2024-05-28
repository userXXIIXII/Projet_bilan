<template>

    <nav class="desktop-nav">
        <div class="logoPF"><img class="logoPF" src="./assets/icons/logo.png" alt="logo"></div>
            <div>
                <ul class="nav-liens">
                    <li><a href="#apropos">A propos</a></li>
                    <li><a href="#experiences">Expériences</a></li>
                    <li><a href="#projets">Projets</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
        </div>
    </nav>

    <section id="profile">

        <div class="section__pic-container">
        <img src="./assets/img/IMG_4197.jpg" alt="Aarin Deb photo de profile"
        class="photo-profile">
        </div>

        <div class="section__text s1">

            <p class="section__text__p1">Salut! Je suis</p>

            <h1 class="titre">Aarin DEB</h1>

            <p class="section__text__p2">Développeur Front-End & Back-End</p>

            <div class="btn-container">
                <button class="btn btn-color-2" onclick="window.open('./assets/CV_aarin.pdf')">
                Téléchrgez mon CV
                </button>

                <button class="btn btn-color-1" onclick="location.href='./#contact'">
                Contact Info
                </button>
            </div>

            <div id="socials-container">

                <a href="https://github.com/userXXIIXII" target="_blank">
                <img src="./assets/icons/github_icon.png" 
                alt="Mon profile Github"
                class="icon">
                </a>

                <a href="https://www.linkedin.com/in/aarin-deb" target="_blank">
                <img src="./assets/icons/linkedin_icon.png" 
                alt="Mon profile LinkedIn"
                class="icon">
                </a>

            </div>

        </div>

    </section>

</template>

<script>
    export default {
        name: 'Accueil'
    }
</script>

<style scoped>

    nav{
        display: flex;
        justify-content: space-around;
        align-items: center;
        height: 17vh;
        background-image: url(./assets/img/Theme/Theme\ NAV.jpg);
        background-size: cover;
        background-position: center;
    }

    nav a{
        color: white;
        font-weight: bold;
    }

    a, .btn{
        transition: all 300ms ease
    }

    .nav-liens{
        gap: 2rem;
        list-style: none;
        font-weight: 1.5rem;
    }

    a{
        color: black;
        text-decoration: none;
        text-decoration-color: white;
    }

    a:hover{
        color: grey;
        text-decoration: underline;
        text-underline-offset: 0.5rem;
        text-decoration-color: white;
    }

    .logoPF{
        padding-top: 10px;
        max-width: 150px;
        height: auto;
    }

    .logo:hover{
        cursor: default;
    }

    #profile{
    display: flex;
    justify-content: center;
    gap: 5rem;
    height: 80vh;
    }

    .section__pic-container{
    display: flex;
    height: 400px;
    width: 400px;
    margin: auto 0;
    }

    .photo-profile{
    border-radius: 13rem;
    }

    .section__text{
    align-self: center;
    text-align: center;
    }

    .section__text p{
    font-weight: 600;
    }

    .section__text__p1{
    text-align: center;
    }

    .section__text__p2{
    font-size: 1.75rem;
    margin-bottom: 1rem;
    }

    .titre{
    font-size: 3rem;
    text-align: center;
    }

    #socials-container{
    display: flex;
    justify-content: center;
    margin-top: 1rem;
    gap: 1rem;
    }


</style>