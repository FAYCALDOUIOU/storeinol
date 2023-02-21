<template>
  <div class="container">
    <div id="programme" class="programme-sect">
      <h1>le programme de la compétition</h1>
      <div class="prog-content">
        <div class="stars-container">
          <div class="star">
            <img src="../assets/img/programme/Star.png" alt="star" />
            <p>
              Inscription à la compétition le 20 février 2023
            </p>
          </div>
          <div class="star">
            <img src="../assets/img/programme/Star.png" alt="star" />
            <p>
              Affichage de la liste finale des participants 27 mars 2023
            </p>
          </div>
          <div class="star">
            <img src="../assets/img/programme/Star.png" alt="star" />
            <p>
              La formation sur marketplace STOREINO :
            </p>
          </div>
          <div class="star-pa">  
            <p>
            La première session de la formation le 01 avril 2023
            </p>
          </div>
          <div class="star-pa">  
            <p>
              La deuxième session de la formation le 08 avril 2023
            </p>
          </div>
          <div class="star">
            <img src="../assets/img/programme/Star.png" alt="star" />
            <p>
              Choix du thématique pour chaque participant 15 avril 2023
            </p>
          </div>
          <div class="star">
            <img src="../assets/img/programme/Star.png" alt="star" />
            <p>
              Lancement de la compétition 17 avril 2023
            </p>
          </div>
          <div class="star">
            <img src="../assets/img/programme/Star.png" alt="star" />
            <p>
              Livraison du projet 15 juillet 2023
            </p>
          </div>
          <div class="star">
            <img src="../assets/img/programme/Star.png" alt="star" />
            <p>
              Cérémonie d'annonce des résultats en octobre.
            </p>
          </div>
        </div>
        <img class="dev" src="../assets/img/programme/dev.png" alt="dev" />
      </div>
    </div>
  </div>
</template>

<style scoped>
.container {
  margin-top: 60px;
  margin-bottom: 60px;
}

.programme-sect {
  text-align: center;
  width: 100%;
  max-width: 600px;
  margin: 0 auto;
}

.programme-sect h1 {
  font-size: 2rem;
  text-transform: uppercase;
  color: var(--cyanColor);
  margin-bottom: 60px;
}

.star {
  display: flex;
  align-items: center;
  gap: 15px;
}

.star p {
  font-size: 16px;
  font-weight: 400;
  line-height: 30px;
}
.star-pa{
    margin-left:10px ;
  }

.dev {
  display: none;
}

@media (min-width: 920px) {
  .programme-sect {
    text-align: center;
    width: 100%;
    max-width: 100%;
  }
  .prog-content {
    display: flex;
    justify-content: space-around;
    align-items: center;
    gap: 20px;
  }

  .stars-container {
    width: 600px;
  }

  .programme-sect h1 {
    font-size: 2.6rem;
  }

  .star {
    gap: 20px;
  }

  .star p {
    font-size: 18px;
  }

  .dev {
    display: block;
    width: 400px;
  }
  .star-pa{
    
  }
}
</style>
