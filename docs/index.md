---
layout: home
title: sass page
---

<div class="wrap">
  <h2>Sass page (not SSR'ng), open devtools -> network tab -> check doc (refresh page)</h2>
  <a href="/css-page" class="btn btn-green">Green Button</a>
  <a href="/css-page" class="btn btn-blue">Blue Button</a>
  <a href="/css-page" class="btn btn-yellow">Yellow Button</a>
  <a href="/css-page" class="btn btn-red">Red Button</a>
</div>

<style lang="scss"> 

@use 'vuetify' with (
  // $utilities: false,
  // $reset: false,
  $color-pack: false
);

/* @mixin button-bg($bg) {
  background: $bg;
  &:hover {
    background:darken($bg,8%);
    transition: all 0.3s ease;
  }
  &:active {
    background:darken($bg,25%);
  } 
}

.btn {
 color:white;
 text-decoration:none;
 padding:5px 10px;
 margin:5px 10px;
 border-radius:3px;
 font-size:1em;
}

.btn-green {
   @include button-bg(#2ecc71);
}

.btn-blue {
   @include button-bg(#3498db);
}

.btn-yellow{
   @include button-bg(#f1c40f);
}

.btn-red {
   @include button-bg(#e74c3c);
} */

/*Other Stylez*/
/* .wrap {
  margin:0 auto;
  width:800px;
  text-align:center;
} */


</style>