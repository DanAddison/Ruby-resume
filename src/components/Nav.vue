<template>
  <nav class="navbar" id="sideNav">
    <div v-on:click.prevent="$scrollTo('#about')" class="navbar-brand">
      <span class="name">Ruby Bolton</span>
      <span class="avatar">
        <g-image
          alt="Image of Loke"
          src="../assets/images/KefaloniaThumb2.jpg"
          class="img-profile"
        />
      </span>
    </div>

    <div id="navbarSupportedContent">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link" v-on:click.prevent="$scrollTo('#about')">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" v-on:click.prevent="$scrollTo('#experience')">Experience</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" v-on:click.prevent="$scrollTo('#skills')">Skills</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" v-on:click.prevent="$scrollTo('#training')">Training</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" v-on:click.prevent="$scrollTo('#education')">Education</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" v-on:click.prevent="$scrollTo('#interests')">Interests</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" v-on:click.prevent="$scrollTo('#contact')">Contact</a>
        </li>
      </ul>
    </div>
  </nav>
</template>

<style scoped lang="scss">
.navbar-brand,
.nav-item {
  cursor: pointer;
}
#sideNav {
  background-color: $primary;
  .nav-link {
    font-weight: 800;
    letter-spacing: 0.05rem;
    text-transform: uppercase;
  }
  .navbar-toggler:focus {
    outline-color: #d48a6e;
  }
  #navbarSupportedContent,
  .avatar {
    display: none;
  }
}
@media (min-width: $bp-sidebar) {
  #sideNav {
    text-align: center;
    position: fixed;
    top: 0;
    left: 0;
    display: flex;
    flex-direction: column;
    // align-items: flex-start;
    // flex-grow: 0;
    width: 17rem;
    height: 100vh;

    .navbar-brand {
      display: flex;
      margin: auto auto 0;
      padding: 0.5rem;
      .name {
        display: none;
      }
      .avatar {
        display: block;
        .img-profile {
          max-width: 10rem;
          max-height: 10rem;
          border: 0.5rem solid $white-overlay2;
          border-radius: 50%;
        }
      }
    }
  
    #navbarSupportedContent {
      display: flex;
      width: 100%;
      margin-bottom: auto;
      .navbar-nav {
        flex-direction: column;
        width: 100%;
        padding-left: 0;
      }
      .nav-item, .nav-link {
        display: block;
        padding: .25rem 0;
        color: $white-overlay1;
      }
    }
  }
}
</style>