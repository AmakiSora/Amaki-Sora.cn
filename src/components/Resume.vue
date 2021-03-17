<template>
  <div class="col-12 col-md-12 col-lg-10">
    <div class="box box-content">
      <div class="pb-2">
        <h1 class="title title--h1 first-title title__separate">Resume</h1>
      </div><!-- Experience -->
      <div class="row">
        <div class="col-12">
          <h2 class="title title--h3"><img class="title-icon"
                                           src="static/picture/icon-education.svg" alt="">教育经历</h2>
          <div class="timeline">
            <!-- Item -->
            <article class="timeline__item">
              <h5 class="title title--h5 timeline__title">xxxxxxxxxxxxxxxx中学</h5>
              <span class="timeline__period">2077 — 2098</span>
              <p class="timeline__description">xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx</p>
            </article><!-- Item -->
            <article class="timeline__item">
              <h5 class="title title--h5 timeline__title">xxxxxxxxxxxxx大学</h5><span
              class="timeline__period">2000 — 2021</span>
              <p class="timeline__description">xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx</p>
            </article><!-- Item -->
            <article class="timeline__item">
              <h5 class="title title--h5 timeline__title">xxxxxxxxxxxxxx大学</h5>
              <span class="timeline__period">2023 — 2075</span>
              <p class="timeline__description">xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx</p>
            </article>
          </div>
        </div>
        <div class="col-12">
          <h2 class="title title--h3"><img class="title-icon"
                                           src="static/picture/icon-experience.svg" alt="">Experience</h2>
          <div class="timeline">
            <!-- Item -->
            <article class="timeline__item">
              <h5 class="title title--h5 timeline__title">Creative Director</h5><span
              class="timeline__period">2015 — Present</span>
              <p class="timeline__description">xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx</p>
            </article><!-- Item -->
            <article class="timeline__item">
              <h5 class="title title--h5 timeline__title">Art Director</h5><span
              class="timeline__period">2013 — 2015</span>
              <p class="timeline__description">xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx</p>
            </article><!-- Item -->
            <article class="timeline__item">
              <h5 class="title title--h5 timeline__title">Web Designer</h5><span
              class="timeline__period">2010 — 2013</span>
              <p class="timeline__description">xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx</p>
            </article>
          </div>
        </div>
      </div><!-- Skills -->
      <div class="row">
        <div class="col-12">
          <h2 class="title title--h3">My Skills</h2>
          <div class="box box__border">
            <!-- Progress -->
            <div class="progress">
              <div class="progress-bar" role="progressbar" aria-valuenow="80"
                   aria-valuemin="0" aria-valuemax="100">
                <div class="progress-text"><span>Web Design</span><span>80%</span></div>
              </div>
              <div class="progress-text"><span>Web Design</span></div>
            </div><!-- Progress -->
            <div class="progress">
              <div class="progress-bar" role="progressbar" aria-valuenow="75"
                   aria-valuemin="0" aria-valuemax="100">
                <div class="progress-text"><span>Graphic Design</span><span>75%</span></div>
              </div>
              <div class="progress-text"><span>Graphic Design</span></div>
            </div><!-- Progress -->
            <div class="progress">
              <div class="progress-bar" role="progressbar" aria-valuenow="90"
                   aria-valuemin="0" aria-valuemax="100">
                <div class="progress-text"><span>Photoshop</span><span>90%</span></div>
              </div>
              <div class="progress-text"><span>Photoshop</span></div>
            </div><!-- Progress -->
            <div class="progress">
              <div class="progress-bar" role="progressbar" aria-valuenow="50"
                   aria-valuemin="0" aria-valuemax="100">
                <div class="progress-text"><span>Illustrator</span><span>50%</span></div>
              </div>
              <div class="progress-text"><span>Illustrator</span></div>
            </div>
          </div>
        </div>
      </div>
    </div><!-- Footer -->
    <footer class="footer">© 2021 AmakiSora &nbsp
      <a href="https://beian.miit.gov.cn/" target="_blank">桂ICP备2021001942号</a>
    </footer>  </div>
</template>

<script>
export default {
  name: "Resume"
}
</script>

<style scoped>

</style>
