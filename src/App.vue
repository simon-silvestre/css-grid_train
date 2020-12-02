<template>
  <div id="app">
    <div class="grid__container">

      <div class="grid__item Daniel__card">
        
        <div class="profil">
          <div class="img__container">
            <img src="@/assets/image-daniel.jpg" alt="">
          </div>
          <p>Daniel Clifford</p>
          <small>Verified Graduate</small>
        </div>
          <p class="experiences_header"><strong>
            I received a job offer mid-course, and the subjects I learned were current, if not more so, in the company I joined. I honestly feel I got every penny’s worth.
          </strong></p>
          <p>
            “ I was an EMT for many years before I joined the bootcamp. I’ve been looking to make a transition and have heard some people who had an amazing experience here. 
            I signed up for the free intro course and found it incredibly fun! I enrolled shortly thereafter. The next 12 weeks was the best - and most grueling - time of my life. 
            Since completing the course, I’ve successfully switched careers, working as a Software Engineer at a VR startup. ”
          </p>
      </div>

      <div class="grid__item Jonathan__card">
         <div class="profil">
          <div class="img__container">
            <img src="@/assets/image-jonathan.jpg" alt="">
          </div>
          <p>Jonathan Walters</p>
          <small>Verified Graduate</small>
        </div>
          <p class="experiences_header"><strong>
            The team was very supportive and kept me motivated
          </strong></p>
          <p>
            “ I started as a total newbie with virtually no coding skills. I now work as a mobile engineer for a big company. 
            This was one of the best investments I’ve made in myself. ”
          </p>
      </div>

      <div class="grid__item Kira__card">
         <div class="profil">
          <div class="img__container">
            <img src="@/assets/image-kira.jpg" alt="">
          </div>
          <p>Kira Whittle</p>
          <small>Verified Graduate</small>
        </div>
          <p class="experiences_header"><strong>
            Such a life-changing experience. Highly recommended!
          </strong></p>
          <p>
            “ Before joining the bootcamp, I’ve never written a line of code. I needed some structure from professionals who can help me learn programming step by step. 
            I was encouraged to enroll by a former student of theirs who can only say wonderful things about the program. The entire curriculum and staff did not disappoint. 
            They were very hands-on and I never had to wait long for assistance. The agile team project, in particular, was outstanding. It took my learning to the next level 
            in a way that no tutorial could ever have. In fact, I’ve often referred to it during interviews as an example of my developent experience. It certainly helped me land 
            a job as a full-stack developer after receiving multiple offers. 100% recommend! ”
          </p>

      </div>

      <div class="grid__item Jeanette__card">
         <div class="profil">
          <div class="img__container">
            <img src="@/assets/image-jeanette.jpg" alt="">
          </div>
          <p>Jeanette Harmon</p>
          <small>Verified Graduate</small>
        </div>
          <p class="experiences_header"><strong>
            An overall wonderful and rewarding experience
          </strong></p>
          <p>
            “ Thank you for the wonderful experience! I now have a job I really enjoy, and make a good living while doing something I love. ”
          </p>
      </div>

      <div class="grid__item Patrick__card">
         <div class="profil">
          <div class="img__container">
            <img src="@/assets/image-patrick.jpg" alt="">
          </div>
          <p>Patrick Abrams</p>
          <small>Verified Graduate</small>
        </div>
          <p class="experiences_header"><strong>
             Awesome teaching support from TAs who did the bootcamp themselves. Getting guidance from them and learning from their experiences was easy.
          </strong></p>
          <p>
            The staff seem genuinely concerned about my progress which I find really refreshing. The program gave me the confidence necessary to be able 
            to go out in the world and present myself as a capable junior developer. 
            The standard is above the rest. You will get the personal attention you need from an incredible community of smart and amazing people. ”
          </p>
      </div>

    </div>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {
  }
}
</script>

<style>
  @import url('https://fonts.google.com/specimen/Barlow+Semi+Condensed');
  * {
    padding: 0;
    margin: 0;
  }
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    background-color: #8BC6EC;
    background-image: linear-gradient(135deg, #8BC6EC 0%, #9599E2 100%);
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 13px;
    font-family: 'Barlow Semi Condensed', sans-serif;
  }
  .grid__container {
    display: grid;
    width: 1110px;
    height: 574px;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    grid-gap: 30px;
  }
  .grid__item {
    position: relative;
    border-radius: 8px;
    padding: 25px 30px;
    color: #fff
  }
  .grid__item .profil {
    position: relative;
  }
  .profil .img__container {
    width: 32px;
    height: 32px;
    border-radius: 50%;
    border: 1px solid red;
    overflow: hidden;
  }
  .profil .img__container img {
    width: 100%;
  }
  .grid__item .profil p, .profil small {
    position: absolute;
    top: 0;
    left: 50px;
  }
  .grid__item .profil small {
    top: 18px;
    left: 50px;
    opacity: .5;
  }
  .grid__item .experiences_header {
    margin: 20px 0;
    font-size: 17px;
    line-height: 23px;
  }
  .grid__item p:last-child {
    font-size: 12px;
    opacity: .7;
    line-height: 17px;
  }
  .Kira__card .experiences_header, .Jeanette__card .experiences_header {
    margin: 20px 0 25px 0;
  }
  .Daniel__card {
    grid-column: 1 / 3;
    background-color: hsl(263, 55%, 52%);
    background-image: url(assets/bg-pattern-quotation.svg);
    background-repeat: no-repeat;
    background-position: 365px 0px;
  }
  .Daniel__card .img_quote {
    position: absolute;
    top: 0;
    right: 75px;
  }
  .Jonathan__card {
    background-color: hsl(217, 19%, 35%);
  }
  .Kira__card {
    grid-area: 1 / 4 / 3 / 4;
    background-color: hsl(0, 0%, 100%);
      color: #74777b;
  }
  .Jeanette__card {
    background-color: hsl(0, 0%, 100%); 
      color: #74777b;
  }
  .Patrick__card {
    grid-column: 2 / 4;
    background-color: hsl(219, 29%, 14%);
  }
  @media screen and (max-width: 1125px) {
    #app {
      height: 100%;
    }
    .grid__container {
      width: 825px;
      height: 100%;
      margin: 75px 0;
      grid-template-columns: 1fr 1fr 1fr;
    }
    .Daniel__card {
      grid-column: 1 / 3;
    }
    .Kira__card {
      grid-column: 1 / 4;
      grid-row: 3 / 4;
    }
    .Jeanette__card {
      grid-column: 1 / 2;
    }
    .Patrick__card {
      grid-column: 2 / 4;
    }
  }
  @media screen and (max-width: 850px) {
    .grid__container {
      width: 540px;
      height: 100%;
      grid-template-columns: 1fr 1fr;
    }
    .Jonathan__card {
      grid-row: 2 / 3;
      grid-column: 1 / 2;
    }
    .Jeanette__card {
      grid-column: 2 / 3;
    }
    .Patrick__card {
      grid-column: 1 / 3;
      grid-row: 3 / 4;
    }
    .Kira__card {
      grid-row: 4 / 4;
      grid-column: 1 / 3;
    }
  }
  @media screen and (max-width: 565px) {
    .grid__container {
      width: 90%;
    }
    .Jonathan__card {
      grid-column: 1 / 3;
    }
    .Jeanette__card {
      grid-column: 1 / 3;
    }
    .Patrick__card {
      grid-column: 1 / 3;
    }
    .Kira__card {
      grid-row: 5 / 6;
      grid-column: 1 / 3;
    }
  }
</style>
