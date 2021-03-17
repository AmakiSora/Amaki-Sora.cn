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
              <ul class="nav"  v-on:click.prevent>
                <li class="nav__item">
                  <a :class="isActive==='About'?'active':''" href="#" v-on:click="makeActive('About')"><i class="icon-user"></i>About</a></li>
                <li class="nav__item">
                  <a :class="isActive==='Resume'?'active':''" href="#" v-on:click="makeActive('Resume')"><i class="icon-file-text"></i>Resume</a></li>
                <li class="nav__item">
                  <a :class="isActive==='Works'?'active':''" href="#" v-on:click="makeActive('Works')"><i class="icon-codesandbox"></i>Works</a></li>
                <li class="nav__item">
                  <a :class="isActive==='Blog'?'active':''" href="#" v-on:click="makeActive('Blog')"><i class="icon-book-open"></i>Blog</a></li>
                <li class="nav__item">
                  <a :class="isActive==='Contact'?'active':''" href="#" v-on:click="makeActive('Contact')"><i class="icon-book"></i>Contact</a></li>
              </ul>
            </div>
          </aside><!-- Content -->
          <About v-show="isActive==='About'"></About>
          <Resume v-show="isActive==='Resume'"></Resume>
          <Works v-show="isActive==='Works'"></Works>
          <Blog v-show="isActive==='Blog'"></Blog>
          <Contact v-show="isActive==='Contact'"></Contact>
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
import About from "../components/About";
import Resume from "../components/Resume";
import Works from "../components/Works";
import Contact from "../components/Contact";
import Blog from "../components/Blog";

export default {
  name: "Home",
  data() {
    return {
      isActive: 'About',
    }
  },
  components: {Blog, Contact, Works, Resume, About },
  methods: {
    makeActive(a){
      this.isActive = a
    }
  }
}
</script>

<style scoped>

</style>
