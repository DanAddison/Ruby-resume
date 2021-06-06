<template>
  <section class="resume-section" id="about">
      <h1>
        Blue<span class="text-primary">Gold</span>
      </h1>
      <p class="subheading">Ruby Addison</p>
      <p class="lead">I'm a freelance artist/ educator from Folkerstone. I am experienced in curating and delivering exciting learning programmes, and in cultivating a diverse audience. I want to make a lasting impact on others through my work. I work in education because I have a passion to engage young people, communities and individuals through learning. I want to give people the opportunity to explore new things and to use their imaginations.
      I particularly enjoy making collages, hand-made jewellery and paper-cut crafts.</p>

      <div class="social-icons">
        <a href="https://instagram.com" target="_blank" rel="noopener noreferrer">
          <font-awesome :icon="['fab', 'instagram']"/>
        </a>
        <a href="https://www.facebook.com" target="_blank" rel="noopener noreferrer">
          <font-awesome :icon="['fab', 'facebook']"/>
        </a>
      </div>
  </section>
</template>

<style lang="scss" scoped>
#about {
  max-width: 40rem;
}
h1 {
  margin-bottom: 0;
}
section.resume-section {

  .subheading {
    margin-bottom: 4rem;
  }
}

.social-icons {
  margin-top: 4rem;
  a {
    cursor: pointer;
    display: inline-block;
    color: $primary;
    font-size: 1.75rem;
    margin-right: 1rem;
  }
}

.social-icons a:last-child {
  margin-right: 0;
}

.social-icons a:hover {
  color: $secondary;
}
</style>