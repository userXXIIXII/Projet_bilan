<template>
        <section id="projets">
        <p class="section__text__p1">Parcourez mes</p>
        <h1 class="titre">Projets</h1>
        <div class="experience-details-container">
            <div class="a-propos-containers">
            <div class="details-container color-container">
                <div class="article-container">
                    <img src="./assets/img/Projet 1 img.jpg" alt="Projet 1" class="projet-img">
                </div>
                <h2 class="experience-sous-titre projet-titre">Projet n.1</h2>
                <div class="btn-container">
                    <button class="btn btn-color-2 projet-btn" onclick="location.href='https://github.com/userXXIIXII/CV-CEF'">
                        Github
                    </button>

                    <!-- 2nd projet= Mettre le lien repository du projet bilan CEF -->
                    <button class="btn btn-color-2 projet-btn" onclick="location.href='https://github.com/userXXIIXII/CV-CEF'">
                        Rendu
                    </button>
                </div>
            </div>
            <div class="details-container color-container">
                <div class="article-container">
                    <img src="./assets/img/Projet 2 img.jpg" alt="Projet 2" class="projet-img">
                </div>
                <h2 class="experience-sous-titre projet-titre">Projet n.2</h2>
                <div class="btn-container">
                    <button class="btn btn-color-2 projet-btn" onclick="location.href='https://github.com/userXXIIXII/CV-CEF'">
                        Github
                    </button>

                    <!-- 2nd projet= Mettre le lien repository du projet bilan CEF -->
                    <button class="btn btn-color-2 projet-btn" onclick="location.href='https://github.com/userXXIIXII/CV-CEF'">
                        Rendu
                    </button>
                </div>
            </div>
        </div>
        </div>
    </section>

</template>

<script>
    export default {
        name: 'projets'
    }
</script>

<style scoped>
    #projets{
    position: relative;
}

.color-container{
    border-color: rgb(163, 163, 163);
    background-image: url(./assets/img/Theme/Theme\ NAV.jpg);
}

.projet-img{
    border-radius: 2rem;
    width: 90%;
    height: 90%;
}

.projet-titre{
    margin: 1rem;
    color: white;
}

.projet-btn{
    color: white;
    border-color: white;
}

</style>