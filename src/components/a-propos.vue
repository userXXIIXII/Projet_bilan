<template>
    <section id="a-propos">
        <p class="section__text__p1">Découvrez en plus</p>
        <h1 class="titre">Qui suis-je?</h1>
        <div class="section-container">

            <div class="section__pic-container">
                <img src="./assets/img//IMG_1947_Facetune_17-03-2020-21-54-35.jpg" 
                alt="Photo de profil" 
                class="a-propos-pic">
            </div>

            <div class="a-propos-details-container">

                <div class="a-propos-containers">

                    <div class="details-container">
                        <img src="./assets/img/experience_icon.png" 
                        alt="experience icon"
                        class="icon">

                        <h3 class="section-t">Expériences</h3>
                        <p class="section-t">3+ années <br>Full-Stack développement</p>
                    </div>

                    <div class="details-container">
                        <img src="./assets/img/education_icon.png" 
                        alt="education icon"
                        class="icon">

                        <h3 class="section-t">Education</h3>
                        <p class="section-t">Titre Professionnel Développeur Web et Web Mobile</p>
                    </div>

                    
                </div>
                
                    <div class="text-container">
                        <p>Ayant suivi une formation intensive en développement web et web mobile, 
                            j'ai acquis une solide base de compétences couvrant les principaux
                            langages de programmation, frameworks et technologies nécessaires
                            pour concevoir, développer et déployer des applications web 
                            complètes. Cette formation m'a permis de maîtriser les concepts
                            fondamentaux du développement web, notamment HTML, CSS, JavaScript,
                            ainsi que l'utilisation de frameworks tels que React, Angular 
                            et Node.js. J'ai également acquis une expérience pratique en 
                            travaillant sur des projets réels, ce qui m'a permis d'affiner
                            mes compétences techniques et de développer ma capacité à 
                            résoudre efficacement les problèmes rencontrés lors du 
                            développement d'applications web.</p>
                    </div>
            </div>
        </div>

    </section>
</template>

<script>
    export default {
        name: 'A-propos'
    }
</script>

<style scoped>
    #a-propos{
    position: relative;
} 

.a-propos-containers{
    gap: 2rem;
    margin-bottom: 2rem;
    margin-top: 2rem;
}

.a-propos-details-container{
    justify-content: center;
    flex-direction: column;
}

.a-propos-containers, .a-propos-details-container{
    display: flex;
}

.a-propos-pic{
    border-radius: 12rem;
    height: 400px;
    width: 400px;
    margin: auto 0;
}

.details-container{
    padding: 1.5rem;
    flex: 1;
    background-image: url(./assets/img/Theme/Theme\ NAV.jpg);
    border-radius: 2rem;
    border: rgb(53, 53, 53) 0.1rem solid;
    border-color: rgb(163, 163, 163);
    text-align: center;
}

.section-container{
    gap: 4rem;
    height: 80%;
}

.text-container{
    margin-bottom: 170px;
}

.section__pic-container{
    padding-bottom: 110px;
}

</style>