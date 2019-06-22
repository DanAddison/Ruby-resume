<template>
  <section class="resume-section" id="contact">
    <div>
      <h2>Contact</h2>
      <form name="contact" method="POST" data-netlify="true">
        <input type="hidden" name="form-name" value="contact" />
        <p hidden>
          <label>
            Don’t fill this out: <input name="bot-field" />
          </label>
        </p>
        <p>
          <label>Your Name: </label>
          <input type="text" name="name" />   
        </p>
        <p>
          <label>Your Email: </label>
          <input type="email" name="email" />
        </p>
        <p>
          <label>Message: </label>
          <textarea name="message"></textarea>
        </p>
        <p>
          <button type="submit">Send</button>
        </p>
      </form>
    
      <div class="social-icons">
        <a href="https://instagram.com" target="_blank" rel="noopener noreferrer">
          <font-awesome :icon="['fab', 'instagram']"/>
        </a>
        <a href="https://www.facebook.com" target="_blank" rel="noopener noreferrer">
          <font-awesome :icon="['fab', 'facebook']"/>
        </a>
      </div>

    </div>
  </section>
</template>

<style lang="scss" scoped>
label, input, textarea {
  display: block;
  width: 30rem;
}
textarea {
  height: 10rem;
}
.social-icons {
  margin-top: 4rem;
  a {
    cursor: pointer;
    display: inline-block;
    color: $copy-light;
    font-size: 2rem;
    margin-right: 2rem;
  }
}

.social-icons a:last-child {
  margin-right: 0;
}

.social-icons a:hover {
  color: $primary;
}
</style>