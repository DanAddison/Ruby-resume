<template>
  <section class="resume-section" id="about">
    <div>
      <h1>
        Ruby
        <span class="text-primary">Bolton</span>
      </h1>
      <div class="subheading">
        <p>Artist / Educator</p>
      </div>
      <p class="lead">I work in education because I have a passion to engage young people, communities and individuals through learning. Giving people the opportunity to explore new things, to be creative and imaginative, is something I really value. I am experienced in curating and delivering exciting learning programmes, and in cultivating a diverse audience. I want to make a lasting impact on others through my work.</p>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.social-icons a {
  cursor: pointer;
  display: inline-block;
  height: 3.5rem;
  width: 3.5rem;
  background-color: var(--secondary);
  color: #fff !important;
  border-radius: 100%;
  text-align: center;
  font-size: 1.5rem;
  line-height: 3.5rem;
  margin-right: 1rem;

  @media (max-width: 380px) {
    margin-right: 0.5rem;
  }

  @media (max-width: 350px) {
    margin-right: 0.2rem;
  }
}

.social-icons a:last-child {
  margin-right: 0;
}

.social-icons a:hover {
  background-color: var(--primary);
}
</style>