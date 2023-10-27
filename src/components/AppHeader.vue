<script>
export default {
  name: 'AppHeader',

}

</script>

<template>
  <header>

    <!-- logo -->
    <div>
      Alessandra
    </div>

    <!-- nav list -->
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About me</a></li>
        <li><a href="#">Projects</a></li>
        <li><a href="#">Contacts</a></li>
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
    <div class="center_container">

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
          Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nesciunt eaque magni dignissimos vero, ex
          dicta necessitatibus atque voluptatibus aliquam provident natus, ipsum, doloremque porro!
          Necessitatibus, aliquam? Quis obcaecati veniam dolores?
        </p>

        <a href="#">learn more &DownArrow;</a>
      </section>
    </div>
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
  padding: 50px 150px;
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
  margin-top: 100px;
  color: $primary;
  height: 100vh;
  background-color: $background_dark;
  padding: 60px 0;

  .center_container {
    width: 80%;
    margin: 0 auto;
    display: flex;

    section {
      min-width: calc(100%/3);
      padding: 30px;

      img {
        width: 90%;
        margin: 0 auto;
      }
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
