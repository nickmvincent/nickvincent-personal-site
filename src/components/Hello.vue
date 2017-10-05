<template>
  <div class="hello">
    <div class="container">
      <div class="section profile-heading">
        <div class="columns">
          <div class="column is-2">
            <div class="image is-128x128 avatar">
              <img src="/static/nick_vincents_face.jpg">
            </div>
          </div>
          <div class="column is-4 bordered">
            <p>
              <span class="subtitle is-bold">Nick Vincent</span>
            </p>
            <p>Graduate student with <a href="http://www.brenthecht.com/">Dr. Brent Hecht </a> in the <a href="http://www.psacomputing.org/"> People, Space, and Algorithms Research </a> group researching economic implications of AI. </p>
          </div>
          <div class="column is-3 bordered">
            <p>First Year Graduate Student</p>
            <p><a href="http://tsb.northwestern.edu/"> Technology and Social Behavior Ph.D. program </a><p>
            <p>Northwestern University</p>
            <p>Evanston, Illinois</p>
          </div>
          <div class="column is-3 bordered">
            <p><a> CV </a></p>
            <p> nickvincent@u.northwestern.edu </p>
            <p><a> LinkedIn </a></p>
            <p><a> Github </a></p>
            <p><a> Twitter </a></p>
          </div>
        </div>
      </div>
      <!--div class="profile-options">
        <div class="tabs is-fullwidth">
          <ul>
            <li class="link is-active"><a><span class="icon"></span> <span>News</span></a></li>
            <li class="link"><a><span class="icon"></span> <span>Publications</span></a></li>
          </ul>
        </div>
      </div-->


      <div class="columns section">
        <div class="column is-6">
          <p class="subtitle"> News </p>
          <p>Sep. 2017 - Started Ph.D. program at Northwestern</p>
          <p>Sep. 2016 - Started work at Cloudbakers</p>
          <p>Sep. 2016 - Moved to Chicago</p>
        </div>
        <div class="column is-6">
          <p class="subtitle"> Publications </p>
          <p>Deep learning...</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>

body {
  font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Helvetica,Arial,sans-serif,"Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol";
}

.profile-heading {
  margin: 20px 0;
  padding-bottom: 30px;
  font-size: 14px;
}
.bordered {
  border-right: 1px solid #f1f1f1;
  border-bottom: 1px solid #f1f1f1;
}


.profile-options {
  background-color: #f1f1f1;
  margin:-20px 0 20px 0;
}
.profile-options .link a {
  padding:18px;
  font-size: 18px;
}
.profile-options .link .icon {
  font-size: 16px;
  padding-top:2px;
}
.avatar {
  float: right;
}
.avatar img {
  border-radius: 200px;
}
p.title.is-bold {
  font-weight: bold;
}
</style>
