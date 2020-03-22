<template>
  <div>
    <section class="hero is-success is-fullheight">
      <div class="hero-head">
        <header class="navbar">
          <div class="container">
            <div class="navbar-brand">
              <a class="navbar-item">
                <img src="../assets/boy.png" alt="Logo" />
              </a>
              <span class="navbar-burger burger" data-target="navbarMenuHeroC">
                <span></span>
                <span></span>
                <span></span>
              </span>
            </div>
            <div id="navbarMenuHeroC" class="navbar-menu">
              <div class="navbar-end">
                <a class="navbar-item is-active">Home</a>
              </div>
            </div>
          </div>
        </header>
      </div>

      <div class="hero-body">
        <div class="container has-text-centered">
          <h1 class="title is-1 judul">Hello, I' Am</h1>
          <h2 class="subtitle judul">Helmy Agta Al Fatah ;</h2>
        </div>
      </div>

      <div class="hero-foot">
        <nav class="tabs is-boxed is-fullwidth">
          <div class="container">
            <ul>
              <li class="is-active" style="background-color: whitesmoke;">
                <a>About</a>
              </li>
            </ul>
          </div>
        </nav>
      </div>
    </section>
    <div>
      <section class="hero">
        <div class="hero-body">
          <div class="container">
            <h3 class="judul-top">About Me</h3>
            <br />
            <div class="columns is-centered">
              <div class="column is-4">
                <div class="content">
                  <div class="columns is-flex is-centered">
                    <figure class="image is-128x128">
                      <img src="../assets/me.png" alt="logo" />
                    </figure>
                  </div>
                  <p>
                    Hi, My name is
                    <strong>Helmy Agta Al Fatah</strong>, I'm 19 years old boy. i learn coding from 15 years old,
                    I'm junior full stack developer. and i'll still grow up to be advance proggramer,
                    IT is my passion, everything about it i love it;
                  </p>
                </div>
              </div>
            </div>
            <!-- down -->
            <h3 class="judul-top">Everything's About me</h3>
            <br />
            <div class="columns">
              <div class="column">
                <span class="tag is-light">
                  <h3 class="judul-skill">Back End</h3>
                </span>
                <h4 class="item-skill">> PHP</h4>
                <h4 class="item-skill">> NodeJS</h4>
              </div>
              <div class="column">
                <span class="tag is-light">
                  <h3 class="judul-skill">Front End</h3>
                </span>
                <h4 class="item-skill">> VueJS</h4>
              </div>
              <div class="column">
                <span class="tag is-light">
                  <h3 class="judul-skill">Mobile</h3>
                </span>
                <h4 class="item-skill">> Flutter (iOS & Android)</h4>
              </div>
              <div class="column">
                <span class="tag is-light">
                  <h3 class="judul-skill">My OS</h3>
                </span>
                <h4 class="item-skill">> Linux</h4>
                <h4 class="item-skill">> Windows</h4>
                <h4 class="item-skill">> MacOS</h4>
              </div>
            </div>
            <h3 class="judul-top">Hire Me</h3>
            <br/>
            <span class="tag is-light">
              <h3 class="judul-skill">Contact</h3>
            </span>
            <h4 class="item-skill">Email : helmibaran20@gmail.com</h4>
            <h4 class="item-skill">Github : xzagta</h4>
          </div>
        </div>
      </section>
    </div>
    <footer class="footer">
      <div class="content has-text-centered">
        <p>Made With &#10084; by Helmy Agta Al Fatah</p>
      </div>
    </footer>
  </div>
</template>
<style>
p {
  font-family: "IBM Plex Mono", monospace;
}
.judul-skill {
  font-family: "IBM Plex Mono", monospace;
  font-weight: bold;
}
.item-skill {
  font-family: "IBM Plex Mono", monospace;
  font-weight: bold;
}
.judul-top {
  font-family: "IBM Plex Mono", monospace;
  font-weight: bold;
}
.judul {
  font-family: "Quantico", monospace;
}
</style>
<script>
export default {};
</script>