<template>
        <section id="experience">
        <p class="section__text__p1">Découvrez mes</p>
        <h1 class="titre">Expériences</h1>
        <div class="experience-details-container">
            <div class="a-propos-containers">
                <div class="details-container">
                    <h2 class="experience-sous-titre">Développement Front-End</h2>
                    <div class="article-container">

                        <article>
                            <img src="./assets/img/HTML-icon.png" 
                            alt="icon HTML" 
                            class="icon">

                            <div>
                                <h3>HTML</h3>

                                <p>Expérimenté</p>
                            </div>
                        </article>

                        <article>
                            <img src="./assets/img/CSS-icon.png" 
                            alt="icon CSS" 
                            class="icon">

                            <div>
                                <h3>CSS</h3>

                                <p>Compétent</p>
                            </div>
                        </article>

                        <article>
                            <img src="./assets/img/JS_icon.png" 
                            alt="icon JS" 
                            class="icon">

                            <div>
                                <h3>JavaScript</h3>

                                <p>Habile</p>
                            </div>
                        </article>

                        <article>
                            <img src="./assets/img/VueJS-icon.png" 
                            alt="icon VueJS" 
                            class="icon">

                            <div>
                                <h3>Vue.JS</h3>

                                <p>Expert</p>
                            </div>
                        </article>

                        <article>
                            <img src="./assets/img/Angular-icon.png" 
                            alt="icon Angular" 
                            class="icon">

                            <div>
                                <h3>Angular</h3>

                                <p>Doué</p>
                            </div>
                        </article>

                    </div>
                </div>
                <div class="details-container">
                    <h2 class="experience-sous-titre">Développement Back-End</h2>
                    <div class="article-container">

                        <article>
                            <img src="./assets/img/NodeJS-icon.png" 
                            alt="icon HTML" 
                            class="icon">

                            <div>
                                <h3>Node JS</h3>

                                <p>Chevronné</p>
                            </div>
                        </article>

                        <article>
                            <img src="./assets/img/express-icon.png" 
                            alt="icon Express JS" 
                            class="icon">

                            <div>
                                <h3>Express JS</h3>

                                <p>Intermédiaire</p>
                            </div>
                        </article>

                        <article>
                            <img src="./assets/img/PHP-icon.png" 
                            alt="icon PHP" 
                            class="icon">

                            <div>
                                <h3>PHP</h3>

                                <p>Solide</p>
                            </div>
                        </article>

                        <article>
                            <img src="./assets/img/github_icon.png" 
                            alt="icon git" 
                            class="icon">

                            <div>
                                <h3>Git</h3>

                                <p>Avancé</p>
                            </div>
                        </article>

                        <article>
                            <img src="./assets/img/C-icon.png" 
                            alt="icon C#" 
                            class="icon">

                            <div>
                                <h3>C#</h3>

                                <p>Doué</p>
                            </div>
                        </article>

                    </div>
                </div>
            </div>
        </div>
    </section>

</template>

<script>
    export default {
        name: 'experience'
    }
</script>

<style scoped>
#experiences{
    position: relative;
}

.experience-sous-titre{
    color: white
    font-weight: 600;
    font-size: 1.75rem;
    margin-bottom: 2rem;
}

.experience-details-container{
    display: flex;
    justify-content: center;
    flex-direction: column;
}

.article-container{
    display: flex;
    text-align: initial;
    flex-wrap: wrap;
    flex-direction: row;
    gap: 2.5rem;
    justify-content: space-around;
}

article{
    display: flex;
    width: 10rem;
    justify-content: space-around;
    gap: 0.5rem;
}

article .icon {
    cursor: default;
}

</style>