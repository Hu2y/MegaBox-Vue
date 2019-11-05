<template>
  <header id="header">
    <div class="container">
      <div class="row">
        <div class="header clearfix">
          <h1>
            <a href>
              <em>
                <img src="../assets/img/logo.png" alt="MEGABOX" />
              </em>
              <strong>
                <img src="../assets/img/logo-sub.png" alt="LIFE THEATER" />
              </strong>
            </a>
          </h1>
          <nav id="mNav">
            <h2 class="ir_so">전체메뉴</h2>
            <a href class="ham">
              <span></span>
            </a>
          </nav>
          <nav class="nav">
            <ul class="clearfix">
              <li v-for="navItem in navMenu" :key="navItem.index">
                <a href="#">{{ navItem }}</a>
              </li>
            </ul>
          </nav>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  data() {
    return {
      navMenu: ['영화','큐레이션','영화관','특별관','스토어','이벤트','로그인']
    }
  }
};
</script>

