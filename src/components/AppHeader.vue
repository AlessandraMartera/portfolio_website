<script>
export default {
  name: 'AppHeader',

}

</script>

<template>
  <header>

    <!-- logo -->
    <div>
      Alessandra <span class="highlighter"> Martera </span>
    </div>

    <!-- nav list -->
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#About_me">About me</a></li>
        <li><a href="#Projects">Projects</a></li>
        <li><a href="#Contacts">Contacts</a></li>
      </ul>

      <!-- contact me -->
      <div>
        <a href=""><i class="fa-brands fa-linkedin"></i></a>
        <a href=""><i class="fa-brands fa-github"></i></a>
        <a href=""><i class="fa-brands fa-instagram"></i></a>
      </div>
    </nav>
  </header>

  <!-- jumbotrone -->
  <div id="hero">
    <!-- section name -->
    <section id="name">
      <h1>
        Alessandra <br>
        Martera <br>
      </h1>
      <button>
        Contact me
      </button>
    </section>

    <!-- img -->
    <section id="image">
      <img src="foto.jpeg" alt="">
    </section>

    <!-- info about me -->
    <section id="info">
      <h1>
        Junior <br>
        Full-Stack <br>
        Web Developer
      </h1>

      <p>
        Mi piace realizzare siti web, imparare cose nuove e i giochini di logica <i
          class="fa-regular fa-face-grin-wide"></i>
      </p>

      <a href="#">learn more &DownArrow;</a>
    </section>
  </div>
</template>

<style lang="scss" scoped>
@use "./../styles/general.scss" as *;
@use "./../styles/partials/variables.scss" as *;

header {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100px;
  font-size: 24px;
  color: $primary;
  background-color: $background_dark;
  padding: 40px 150px;
  display: flex;
  justify-content: space-between;

  nav {
    width: 80%;
    text-align: end;
    display: flex;
    justify-content: flex-end;
  }

  a {
    margin-left: 20px;
  }

  ul {
    padding: 0 40px;
    display: flex;
    justify-content: flex-start;
    gap: 40px;
  }
}

// Jumbo
#hero {
  // padding-top: 100px;
  height: 100vh;
  background-color: $background_dark;
  padding: 200px 100px;

  display: flex;
  justify-content: center;
  align-items: center;

  section {
    min-width: calc(100%/3);
    padding: 30px;

    img {
      width: 90%;
      margin: 0 auto;
    }
  }

  #image {
    text-align: center;
  }

  #name {
    display: flex;
    flex-direction: column;
    justify-content: space-around;

    h1 {
      font-size: 60px;
    }

    button {
      width: 200px;
    }
  }

  #info {
    font-size: 20px;

    h1 {
      font-size: 40px;
    }

    p {
      margin: 25px 0;
    }

    a {
      color: $highlighter;
    }
  }
}


// DEBUG
// header {
//   border: 1px #1eff00 dashed;

//   div,
//   nav,
//   ul {
//     border: 1px dashed yellow;
//   }
// }

// DEBUG 
// section {
//   border: red 1px dotted;
// }
</style>
