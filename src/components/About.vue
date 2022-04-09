<template>
  <section class="resume-section" id="about">
      <h1>
        Ruby <span class="text-primary">Addison</span>
      </h1>
      <p class="subheading">Artist</p>
      <p class="lead">I'm a freelance artist/ educator from Folkestone. I help arts organisations across Kent to develop and deliver fun workshops and learning programmes. I love encouraging young people and communities to explore new things, and to use their imaginations.</p>

      <div class="social-icons">
        <a href="https://www.instagram.com/bluegoldstudio/" target="_blank" rel="noopener noreferrer">
          <font-awesome :icon="['fab', 'instagram']"/>
        </a>
        <a href="https://www.linkedin.com/in/ruby-bolton-891978174/" target="_blank" rel="noopener noreferrer">
          <font-awesome :icon="['fab', 'linkedin']"/>
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