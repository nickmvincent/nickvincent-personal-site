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
          <div class="column is-4 name">
            <p>
              <span class="title is-bold">Nick Vincent</span>
            </p>
            <p class="tagline">First year Ph.D. student with Dr. Brent Hecht in the <a> People, Space, and Algorithms Research </a> group researching economic implications of AI. </p>
          </div>
          <div class="column is-3 followers">
            <p>Northwestern University</p>
            <p><a> Technology and Social Behavior </a><p>
            <p>Evanston, Illinois</p>
          </div>
          <div class="column is-3 following">
            <p> nickvincent@u.northwestern.edu </p>
            <p><a> LinkedIn </a></p>
            <p><a> Github </a></p>
            <p><a> Twitter </a></p>
          </div>
        </div>
      </div>
      <div class="profile-options">
        <div class="tabs is-fullwidth">
          <ul>
            <li class="link is-active"><a><span class="icon"></span> <span>News</span></a></li>
            <li class="link"><a><span class="icon"></span> <span>Publications</span></a></li>
          </ul>
        </div>
      </div>

      <div class="box">
        <!-- Main container -->
        <nav class="level">
          <!-- Left side -->
          <div class="level-left">
            <div class="level-item">
              <p class="subtitle is-5">
                <strong>123</strong> posts
              </p>
            </div>
            <div class="level-item">
              <p class="control has-addons">
                <input class="input" type="text" placeholder="Find a post">
                <button class="button">
                  Search
                </button>
              </p>
            </div>
          </div>

          <!-- Right side -->
          <div class="level-right">
            <p class="level-item"><strong>All</strong></p>
            <p class="level-item"><a>Published</a></p>
            <p class="level-item"><a>Drafts</a></p>
            <p class="level-item"><a>Deleted</a></p>
            <p class="level-item"><a class="button is-success">New</a></p>
          </div>
        </nav>
      </div>

      <div class="spacer"></div>

      <div class="columns">

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
.profile-heading .name {
  border-right: 1px solid #f1f1f1;
  margin:-30px 0;
  padding: 40px 30px 0 30px;
}
.profile-heading .followers, .profile-heading .following {
  border-right: 1px solid #f1f1f1;
}
.profile-heading .likes {
  margin:-30px 0;
  padding: 70px 30px;
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
.tagline {
  padding:20px 0;
}
.avatar {
  float: right;
}
.follow {
  float: right;
}
.avatar img {
  border-radius: 200px;
}
p.title.is-bold {
  font-weight: bold;
}
.card .timestamp {
  float:right;
  color:#bbb;
}
</style>
