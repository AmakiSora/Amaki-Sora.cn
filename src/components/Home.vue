<template>
  <div>
    <div class="preloader">
      <div class="preloader__wrap">
        <div class="circle-pulse">
          <div class="circle-pulse__1"></div>
          <div class="circle-pulse__2"></div>
        </div>
        <div class="preloader__progress"><span></span></div>
      </div>
    </div>
    <main class="main"><!-- Header Image -->
      <div class="header-image">
        <div class="js-parallax" style="background-image: url(static/image/IMG_1071.PNG);"></div>
      </div>
      <div class="container gutter-top"><!-- Header -->
        <header class="header box">
          <div class="header__left">
            <div class="header__photo"><img class="header__photo-img" src="static/image/miu.jpg"
                                            alt="Ronald Robertson"></div>
            <div class="header__base-info"><h4 class="title titl--h4">AmakiSora</h4>
              <div class="status">个人网站</div>
              <ul class="header__social">
                <li><a href="#"><i class="font-icon icon-facebook1"></i></a></li>
                <li><a href="#"><i class="font-icon icon-twitter1"></i></a></li>
                <li><a href="#"><i class="font-icon icon-instagram1"></i></a></li>
              </ul>
            </div>
          </div>
          <div class="header__right">
            <ul class="header__contact">
              <li><span class="overhead">邮箱</span>xxxxxxxxxx@qq.com</li>
              <li><span class="overhead">手机</span>不告诉你</li>
            </ul>
            <ul class="header__contact">
              <li><span class="overhead">生日</span>2021年3月16日</li>
              <li><span class="overhead">github</span><a>github.com/AmakiSora</a></li>
            </ul>
          </div>
        </header>
        <div class="row sticky-parent"><!-- Sidebar nav -->
          <aside class="col-12 col-md-12 col-lg-2">
            <div class="sidebar box sticky-column">
              <ul class="nav">
                <li class="nav__item"><a class="active" href=""><i class="icon-user"></i>About</a></li>
                <li class="nav__item"><a href="resume.html"><i class="icon-file-text"></i>Resume</a></li>
                <li class="nav__item"><a href="works.html"><i class="icon-codesandbox"></i>Works</a></li>
                <li class="nav__item"><a href="blog.html"><i class="icon-book-open"></i>Blog</a></li>
                <li class="nav__item"><a href="contact.html"><i class="icon-book"></i>Contact</a></li>
              </ul>
            </div>
          </aside><!-- Content -->
          <div class="col-12 col-md-12 col-lg-10">
            <div class="box box-content"><!-- About -->
              <div class="pb-0 pb-sm-2">
                <h1 class="title title--h1 first-title title__separate">留空</h1>
                <p>无介绍.</p>
              </div>

              <!-- What -->
              <div class="mt-1">
                <h2 class="title title--h3">你在干什么？</h2>
                <div class="row"><!-- Case Item -->
                  <div class="col-12 col-lg-6">
                    <div class="case-item"><img class="case-item__icon"
                                                src="static/picture/icon-design.svg" alt="">
                      <div>
                        <h3 class="title title--h4">网页设计</h3>
                        <p class="case-item__caption">
                          emmmmmmmmmmmm.............
                        </p>
                      </div>
                    </div>
                  </div><!-- Case Item -->
                  <div class="col-12 col-lg-6">
                    <div class="case-item"><img class="case-item__icon"
                                                src="static/picture/icon-dev.svg" alt="">
                      <div>
                        <h3 class="title title--h4">网站开发</h3>
                        <p class="case-item__caption">
                          emmmmmmmmmmmm.............
                        </p>
                      </div>
                    </div>
                  </div><!-- Case Item -->
                  <div class="col-12 col-lg-6">
                    <div class="case-item"><img class="case-item__icon"
                                                src="static/picture/icon-app.svg" alt="">
                      <div>
                        <h3 class="title title--h4">移动端应用</h3>
                        <p class="case-item__caption">
                          emmmmmmmmmmmm.............
                        </p>
                      </div>
                    </div>
                  </div><!-- Case Item -->
                  <div class="col-12 col-lg-6">
                    <div class="case-item"><img class="case-item__icon"
                                                src="static/picture/icon-photo.svg" alt="">
                      <div>
                        <h3 class="title title--h4">图片处理</h3>
                        <p class="case-item__caption">
                          emmmmmmmmmmmm.............
                        </p>
                      </div>
                    </div>
                  </div>
                </div>
              </div><!-- Testimonials -->
              <!--                        <div class="mt-2"><h2 class="title title&#45;&#45;h3">Testimonials</h2>-->
              <!--                            <div class="swiper-container js-carousel-review">-->
              <!--                                <div class="swiper-wrapper">&lt;!&ndash; Item review &ndash;&gt;-->
              <!--                                    <div class="swiper-slide review-item">-->
              <!--                                        <svg class="avatar avatar&#45;&#45;80" viewbox="0 0 84 84">-->
              <!--                                            <g class="avatar__hexagon">-->
              <!--                                                <image xlink:href="assets/img/avatar-2.jpg" height="100%"-->
              <!--                                                       width="100%"></image>-->
              <!--                                            </g>-->
              <!--                                        </svg>-->
              <!--                                        <div class="review-item__textbox"><h4 class="title title&#45;&#45;h5">Daniel Lewis</h4>-->
              <!--                                            <p class="review-item__caption">Felecia was hired to create a corporate-->
              <!--                                                identity. We were very pleased with the work done.</p></div>-->
              <!--                                    </div>&lt;!&ndash; Item review &ndash;&gt;-->
              <!--                                    <div class="swiper-slide review-item">-->
              <!--                                        <svg class="avatar avatar&#45;&#45;80" viewbox="0 0 84 84">-->
              <!--                                            <g class="avatar__hexagon">-->
              <!--                                                <image xlink:href="assets/img/avatar-3.jpg" height="100%"-->
              <!--                                                       width="100%"></image>-->
              <!--                                            </g>-->
              <!--                                        </svg>-->
              <!--                                        <div class="review-item__textbox"><h4 class="title title&#45;&#45;h5">Jessica-->
              <!--                                            Miller</h4>-->
              <!--                                            <p class="review-item__caption">thanks to the skill of Felecia,we have a-->
              <!--                                                design that we can be proud of.</p></div>-->
              <!--                                    </div>&lt;!&ndash; Item review &ndash;&gt;-->
              <!--                                    <div class="swiper-slide review-item">-->
              <!--                                        <svg class="avatar avatar&#45;&#45;80" viewbox="0 0 84 84">-->
              <!--                                            <g class="avatar__hexagon">-->
              <!--                                                <image xlink:href="assets/img/avatar-4.jpg" height="100%"-->
              <!--                                                       width="100%"></image>-->
              <!--                                            </g>-->
              <!--                                        </svg>-->
              <!--                                        <div class="review-item__textbox"><h4 class="title title&#45;&#45;h5">Tanya Ruiz</h4>-->
              <!--                                            <p class="review-item__caption">Felecia was hired to create a corporate-->
              <!--                                                identity. We were very pleased with the work done.</p></div>-->
              <!--                                    </div>&lt;!&ndash; Item review &ndash;&gt;-->
              <!--                                    <div class="swiper-slide review-item">-->
              <!--                                        <svg class="avatar avatar&#45;&#45;80" viewbox="0 0 84 84">-->
              <!--                                            <g class="avatar__hexagon">-->
              <!--                                                <image xlink:href="assets/img/avatar-5.jpg" height="100%"-->
              <!--                                                       width="100%"></image>-->
              <!--                                            </g>-->
              <!--                                        </svg>-->
              <!--                                        <div class="review-item__textbox"><h4 class="title title&#45;&#45;h5">Thomas Castro</h4>-->
              <!--                                            <p class="review-item__caption">thanks to the skill of Felecia,we have a-->
              <!--                                                design that we can be proud of.</p></div>-->
              <!--                                    </div>-->
              <!--                                </div>-->
              <!--                                <div class="swiper-pagination"></div>-->
              <!--                            </div>-->
              <!--                        </div>&lt;!&ndash; Clients &ndash;&gt;-->
              <!--                        <div class="mt-4"><h2 class="title title&#45;&#45;h3">Clients</h2>-->
              <!--                            <div class="swiper-container js-carousel-clients">-->
              <!--                                <div class="swiper-wrapper">&lt;!&ndash; Item client &ndash;&gt;-->
              <!--                                    <div class="swiper-slide"><a href="#"><img src="static/picture/logo-1.svg"-->
              <!--                                                                               alt="Logo"></a></div>&lt;!&ndash; Item client &ndash;&gt;-->
              <!--                                    <div class="swiper-slide"><a href="#"><img src="static/picture/logo-2.svg"-->
              <!--                                                                               alt="Logo"></a></div>&lt;!&ndash; Item client &ndash;&gt;-->
              <!--                                    <div class="swiper-slide"><a href="#"><img src="static/picture/logo-3.svg"-->
              <!--                                                                               alt="Logo"></a></div>&lt;!&ndash; Item client &ndash;&gt;-->
              <!--                                    <div class="swiper-slide"><a href="#"><img src="static/picture/logo-4.svg"-->
              <!--                                                                               alt="Logo"></a></div>&lt;!&ndash; Item client &ndash;&gt;-->
              <!--                                    <div class="swiper-slide"><a href="#"><img src="static/picture/logo-1.svg"-->
              <!--                                                                               alt="Logo"></a></div>&lt;!&ndash; Item client &ndash;&gt;-->
              <!--                                    <div class="swiper-slide"><a href="#"><img src="static/picture/logo-2.svg"-->
              <!--                                                                               alt="Logo"></a></div>-->
              <!--                                </div>-->
              <!--                                <div class="swiper-pagination"></div>-->
              <!--                            </div>-->
              <!--                        </div>-->
            </div><!-- Footer -->
            <footer class="footer">© 2021 AmakiSora &nbsp<a href="https://beian.miit.gov.cn/" target="_blank">桂ICP备2021001942号
            </a>
            </footer>
          </div>
        </div>
      </div>
    </main><!-- SVG masks -->
    <svg class="svg-defs">
      <clippath id="avatar-box">
        <path d="M1.85379 38.4859C2.9221 18.6653 18.6653 2.92275 38.4858 1.85453 56.0986.905299 77.2792 0 94 0c16.721 0 37.901.905299 55.514 1.85453 19.821 1.06822 35.564 16.81077 36.632 36.63137C187.095 56.0922 188 77.267 188 94c0 16.733-.905 37.908-1.854 55.514-1.068 19.821-16.811 35.563-36.632 36.631C131.901 187.095 110.721 188 94 188c-16.7208 0-37.9014-.905-55.5142-1.855-19.8205-1.068-35.5637-16.81-36.63201-36.631C.904831 131.908 0 110.733 0 94c0-16.733.904831-37.9078 1.85379-55.5141z"></path>
      </clippath>
      <clippath id="avatar-hexagon">
        <path d="M0 27.2891c0-4.6662 2.4889-8.976 6.52491-11.2986L31.308 1.72845c3.98-2.290382 8.8697-2.305446 12.8637-.03963l25.234 14.31558C73.4807 18.3162 76 22.6478 76 27.3426V56.684c0 4.6805-2.5041 9.0013-6.5597 11.3186L44.4317 82.2915c-3.9869 2.278-8.8765 2.278-12.8634 0L6.55974 68.0026C2.50414 65.6853 0 61.3645 0 56.684V27.2891z"></path>
      </clippath>
    </svg>
    <div class="back-to-top"></div><!-- JavaScripts -->
  </div>
</template>

<script>
export default {
  name: "Home"
}
</script>

<style scoped>

</style>
