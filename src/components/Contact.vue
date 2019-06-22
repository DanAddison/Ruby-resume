<template>
  <section class="resume-section" id="contact">
    <div>
      <h1>Form to go here</h1>
      <p class="lead">Hit me up via the form, or get at me via the usual socials</p>
  
      <div class="social-icons">
        <a href="https://linkedin.com/in/lokecarlsson" target="_blank" rel="noopener noreferrer">
          <!-- <font-awesome :icon="['fab', 'linkedin']"/> -->
        </a>
        <a href="https://github.com/LokeCarlsson" target="_blank" rel="noopener noreferrer">
          <!-- <font-awesome :icon="['fab', 'github']"/> -->
        </a>
        <a href="https://twitter.com/carlssonloke" target="_blank" rel="noopener noreferrer">
          <!-- <font-awesome :icon="['fab', 'twitter']"/> -->
        </a>
        <a href="https://www.facebook.com/carlssonloke" target="_blank" rel="noopener noreferrer">
          <!-- <font-awesome :icon="['fab', 'facebook']"/> -->
        </a>
      </div>
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