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
        <li><a href="">Home</a></li>
        <li><a href="">Portfolio</a></li>
        <li><a href="">About me</a></li>
        <li><a href="">Pages</a></li>
      </ul>

      <!-- contact me -->
      <div>
        Contact |
        <a href=""><i class="fa-brands fa-linkedin"></i></a>
        <a href=""><i class="fa-brands fa-github"></i></a>
        <a href=""><i class="fa-brands fa-instagram"></i></a>
      </div>
    </nav>
  </header>
  <!-- jumbotrone -->
  <div id="hero">
    <div class="center_container">
      <section>
        <div id="name">
          Alessandra <br>
          Martera
        </div>
      </section>

      <!-- img -->
      <section>
        <img src="foto.jpeg" alt="">
      </section>

      <!-- info about me -->
      <section>
        <h1>
          Junior <br>
          Full-Stack Web Developer
        </h1>
        <p>
          Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nesciunt eaque magni dignissimos vero, ex
          dicta necessitatibus atque voluptatibus aliquam provident natus, ipsum, doloremque porro!
          Necessitatibus, aliquam? Quis obcaecati veniam dolores?
        </p>
      </section>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use "./../styles/general.scss" as *;
@use "./../styles/partials/variables.scss" as *;

header {
  font-size: 24px;
  color: #fff;
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
    flex-direction: row-reverse;
    justify-content: flex-start;
    gap: 40px;
  }
}

// Jumbo
#hero {
  color: #778899;
  height: 100vh;
  background-color: $background_dark;
  padding: 60px 0;

  .center_container {
    width: 80%;
    margin: 0 auto;
    display: flex;

    section {
      min-width: calc(100%/3);

      img {
        width: 90%;
        margin: 0 auto;
      }
    }
  }

  #name {
    font-size: 60px;
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
section {
  border: red 1px dotted;
}
</style>
