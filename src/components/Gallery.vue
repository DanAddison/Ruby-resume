<template>
  <section class="resume-section" id="gallery">
    <h2>gallery</h2>

    <div class="resume-item">
      <div class="gallery-item">
        <g-image
          alt="Ben Fletcher website screenshot in dark mode"
          src="../assets/images/KefaloniaThumb2.jpg"
          class="img-profile"
          height="364"
          width="500"
          fit="cover"
        />
        <div class="gallery-item__overlay">
          <h1>benfletcher.com</h1>
          <p class="subtitle">Uses my flexible WordPress gallery/shop theme for creators.</p>
          <p class="tech-stack">
            <span>Tech stack:</span> WordPress, WooCommerce, Sass, jQuery, Gulp
          </p>
          <div class="links">
            <p>
              <a href="https://github.com/DanAddison/ben-fletcher" target="_blank">
                View code
                <font-awesome :icon="['fab', 'github']" />
              </a>
            </p>
          </div>
        </div>
      </div>

      <div class="gallery-item">
        <g-image
          alt="dan4ruby.com screenshot"
          src="../assets/images/KefaloniaThumb2.jpg"
          class="img-profile"
          height="364"
          width="500"
          fit="cover"
        />
        <div class="gallery-item__overlay">
          <h1>dan4ruby.com</h1>
          <p class="subtitle">Wedding event information website.</p>
          <p class="tech-stack">
            <span>Tech stack:</span> Gatsby, Styled Components, Styled System, Typeform
          </p>
          <div class="links">
            <p>
              <a href="https://dan4ruby.com" target="_blank">
                Visit site
                <font-awesome :icon="['fas', 'external-link-alt']" />
              </a>
            </p>
            <p>
              <a href="https://github.com/DanAddison/dan4ruby-gatsby" target="_blank">
                View code
                <font-awesome :icon="['fab', 'github']" />
              </a>
            </p>
          </div>
        </div>
      </div>

      <div class="gallery-item">
        <g-image
          alt="jm-woodcraft.com screenshot"
          src="../assets/images/KefaloniaThumb2.jpg"
          height="364"
          width="500"
          fit="cover"
        />

        <div class="gallery-item__overlay">
          <h1>jm-woodcraft.com</h1>
          <p class="subtitle">Bespoke brochure/archive site for a carpenter.</p>
          <p class="tech-stack">
            <span>Tech stack:</span> WordPress, Sass, jQuery, Gulp
          </p>
          <div class="links">
            <p>
              <a href="https://jm-woodcraft.com" target="_blank">
                Visit site
                <font-awesome :icon="['fas', 'external-link-alt']" />
              </a>
            </p>
            <p>
              <a href="https://github.com/DanAddison/JM-Woodcraft" target="_blank">
                View code
                <font-awesome :icon="['fab', 'github']" />
              </a>
            </p>
          </div>
        </div>
      </div>

      <div class="gallery-item">
        <g-image
          alt="johnhosking.com screenshot"
          src="../assets/images/KefaloniaThumb2.jpg"
          class="img-profile"
          height="364"
          width="500"
          fit="cover"
        />

        <div class="gallery-item__overlay">
          <h1>johnhosking.com</h1>
          <p class="subtitle">gallery website for an artist.</p>
          <p class="tech-stack">
            <span>Tech stack:</span> Sass, Nunjucks, jQuery, Gulp
          </p>
          <div class="links">
            <p>
              <a href="https://johnhosking.com" target="_blank">
                Visit site
                <font-awesome :icon="['fas', 'external-link-alt']" />
              </a>
            </p>
            <p>
              <a href="https://github.com/DanAddison/John-Hosking" target="_blank">
                View code
                <font-awesome :icon="['fab', 'github']" />
              </a>
            </p>
          </div>
        </div>
      </div>

      <div class="gallery-item">
        <g-image
          alt="jazzbeams.com screenshot"
          src="../assets/images/KefaloniaThumb2.jpg"
          class="img-profile"
          height="364"
          width="500"
          fit="cover"
        />
        <div class="gallery-item__overlay">
          <h1>jazzbeams.com</h1>
          <p class="subtitle">Brochure website for freelance DJs.</p>
          <p class="tech-stack">
            <span>Tech stack:</span> Gridsome, Vue, Sass
          </p>
          <div class="links">
            <p>
              <a href="https://jazzbeams.com" target="_blank">
                Visit site
                <font-awesome :icon="['fas', 'external-link-alt']" />
              </a>
            </p>
            <p>
              <a href="https://github.com/DanAddison/jazz-beams" target="_blank">
                View code
                <font-awesome :icon="['fab', 'github']" />
              </a>
            </p>
          </div>
        </div>
      </div>

      <div class="gallery-item">
        <g-image
          alt="daniel-addison-lyrics-archive screenshot"
          src="../assets/images/KefaloniaThumb2.jpg"
          class="img-profile"
          height="364"
          width="500"
          fit="cover"
        />
        <div class="gallery-item__overlay">
          <h1>lyrics-archive.com</h1>
          <p class="subtitle">Documentation website for a songwriter.</p>
          <p class="tech-stack">
            <span>Tech stack:</span> Markdown, Javascript, Docsify
          </p>
          <div class="links">
            <p>
              <a href="https://daniel-addison-lyrics-archive.netlify.com/#/" target="_blank">
                Visit site
                <font-awesome :icon="['fas', 'external-link-alt']" />
              </a>
            </p>
            <p>
              <a href="https://github.com/DanAddison/Songwriting" target="_blank">
                View code
                <font-awesome :icon="['fab', 'github']" />
              </a>
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
</script>


<style lang="scss" scoped>
section.resume-section {
  max-width: 1400px;
}
.resume-item {
  display: grid;
  grid-gap: 1em;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
}

.gallery-item {
  position: relative;
  width: 100%;
  overflow: hidden;
  box-shadow: 0px 0px 11px -6px rgba(0, 0, 0, 0.75);
  transition: 0.2s;

  &:hover,
  &:focus {
    transform: scale(1.07);
    box-shadow: 0px 0px 11px -2px rgba(0, 0, 0, 0.5);
  }

  img {
    display: block;
    width: 100%;
    height: 100%;
  }
}

.gallery-item__overlay {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  padding: 1rem;
  text-align: center;
  display: flex;
  flex-direction: column;
  flex-grow: 1;
  justify-content: center;
  background-color: $primary;
  transition: 0.3s;
  opacity: 0;

  &:hover,
  &:focus {
    opacity: 1;
  }

  p {
    color: $copy;
    margin: 0;
    line-height: 1;
  }

  h1 {
    font-size: 1.5rem;
    line-height: 1;
    margin: 0;
  }

  .subtitle {
    font-weight: bold;
    margin: 0.5em 0 0.7em;
  }

  .tech-stack {
    color: $copy-light;
    font-size: 0.9rem;
  }

  .links {
    position: absolute;
    bottom: 1rem;
    left: 0;
    width: 100%;
    display: flex;
    // margin-top: 1rem;

    p {
      flex-grow: 1;
      margin-bottom: 0.5em;
      margin-top: 0;
      color: $primary;

      svg {
        padding-left: 0.3em;
      }

      a {
        color: $primary;

        &:hover,
        &:focus {
          color: $secondary;
        }
      }
    }
  }
}
</style>