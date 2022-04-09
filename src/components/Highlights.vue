<template>
  <section class="resume-section" id="highlights">
    <h2>Highlights</h2>

    <div class="resume-item">
      <div class="highlight-item">
        <g-image
          alt="Video thumbnail showing the process of a carnival build."
          src="../assets/images/KefaloniaThumb2.jpg"
          class="img-profile"
          height="364"
          width="500"
          fit="cover"
        />
        <div class="highlight-item__overlay">
          <h3>'Virtual Tim' carnival build</h3>
          <p class="organisation">for Strange Cargo</p>
          <p class="highlight-copy">
            I have lead dozens of wacky carnival builds with school children and teachers. Here's an insight into the process, in time-lapse form. 
          </p>
          <div class="links">
            <p>
              <a href="https://dan4ruby.com" target="_blank">
                Watch video
                <font-awesome :icon="['fas', 'external-link-alt']" />
              </a>
            </p>
          </div>
        </div>
      </div>

      <div class="highlight-item">
        <g-image
          alt="dan4ruby.com screenshot"
          src="../assets/images/KefaloniaThumb2.jpg"
          class="img-profile"
          height="364"
          width="500"
          fit="cover"
        />
        <div class="highlight-item__overlay">
          <h3>'Personal Archive' video tutorial</h3>
          <p class="organisation">for Creative Folkestone</p>
          <p class="highlight-copy">
            During lockdown I became adept at producing video workshop tutorials. Here's an example of an idea that I delivered as part of CF's blah blah...
          </p>
          <div class="links">
            <p>
              <a href="https://dan4ruby.com" target="_blank">
                Visit site
                <font-awesome :icon="['fas', 'external-link-alt']" />
              </a>
            </p>
          </div>
        </div>
      </div>

      <div class="highlight-item">
        <g-image
          alt="jm-woodcraft.com screenshot"
          src="../assets/images/KefaloniaThumb2.jpg"
          height="364"
          width="500"
          fit="cover"
        />

        <div class="highlight-item__overlay">
          <h3>Something</h3>
          <p class="organisation">for Lanterns Project</p>
          <p class="highlight-copy">
            Something I did for the Sea Gooseberries public event while serving as their Engagement Producer.
          </p>
          <div class="links">
            <p>
              <a href="https://jm-woodcraft.com" target="_blank">
                Visit site
                <font-awesome :icon="['fas', 'external-link-alt']" />
              </a>
            </p>
          </div>
        </div>
      </div>

      <div class="highlight-item">
        <g-image
          alt="johnhosking.com screenshot"
          src="../assets/images/KefaloniaThumb2.jpg"
          class="img-profile"
          height="364"
          width="500"
          fit="cover"
        />

        <div class="highlight-item__overlay">
          <h3>Something</h3>
          <p class="organisation">for Sidney Cooper Gallery</p>
          <p class="highlight-copy">
            a particular exhibition?
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

      <div class="highlight-item">
        <g-image
          alt="jazzbeams.com screenshot"
          src="../assets/images/KefaloniaThumb2.jpg"
          class="img-profile"
          height="364"
          width="500"
          fit="cover"
        />
        <div class="highlight-item__overlay">
          <h3>Something</h3>
          <p class="organisation">for Animate Arts</p>
          <p class="highlight-copy">
            A particular learning materials pack?
          </p>
          <div class="links">
            <p>
              <a href="https://jazzbeams.com" target="_blank">
                Visit site
                <font-awesome :icon="['fas', 'external-link-alt']" />
              </a>
            </p>
          </div>
        </div>
      </div>

      <div class="highlight-item">
        <g-image
          alt="daniel-addison-lyrics-archive screenshot"
          src="../assets/images/KefaloniaThumb2.jpg"
          class="img-profile"
          height="364"
          width="500"
          fit="cover"
        />
        <div class="highlight-item__overlay">
          <h3>Something</h3>
          <p class="organisation">for Folkestone Fringe</p>
          <p class="highlight-copy">
            A particular workshop?
          </p>
          <div class="links">
            <p>
              <a href="https://daniel-addison-lyrics-archive.netlify.com/#/" target="_blank">
                Visit site
                <font-awesome :icon="['fas', 'external-link-alt']" />
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

.highlight-item {
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

.highlight-item__overlay {
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
  color: $white;
  transition: 0.3s;
  opacity: 0;

  &:hover,
  &:focus {
    opacity: 1;
  }

  p {
    margin: 0;
    line-height: 1;
    color: $white;
  }

  h3 {
    font-size: 1.5rem;
    line-height: 1;
    margin: 0;
    color: $white;
  }

  .organisation {
    font-weight: bold;
    margin: 0.5em 0 0.7em;
  }

  .highlight-copy {
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

      svg {
        padding-left: 0.3em;
      }

      a {
        color: $white;
        &:hover,
        &:focus {
          color: $secondary;
        }
      }
    }
  }
}
</style>