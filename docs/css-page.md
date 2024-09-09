---
layout: home
title: css page
---

<div class="wrap">
  <h2>Css page (SSR'ng correctly), open devtools -> network tab -> check doc (refresh page)</h2>
  <a href="/css-page" class="btn btn-green">Green Button</a>
  <a href="/css-page" class="btn btn-blue">Blue Button</a>
  <a href="/css-page" class="btn btn-yellow">Yellow Button</a>
  <a href="/css-page" class="btn btn-red">Red Button</a>
</div>

<style >
.btn {
  color: white;
  text-decoration: none;
  padding: 5px 10px;
  margin: 5px 10px;
  border-radius: 3px;
  font-size: 1em;
}
.btn-green {
  background: #2ecc71;
}
.btn-green:hover {
  background: #26ab5f;
  transition: all 0.3s ease;
}
.btn-green:active {
  background: #176437;
}
.btn-blue {
  background: #3498db;
}
.btn-blue:hover {
  background: #2383c4;
  transition: all 0.3s ease;
}
.btn-blue:active {
  background: #16527a;
}
.btn-yellow {
  background: #f1c40f;
}
.btn-yellow:hover {
  background: #cba50c;
  transition: all 0.3s ease;
}
.btn-yellow:active {
  background: #796307;
}
.btn-red {
  background: #e74c3c;
}
.btn-red:hover {
  background: #df2e1b;
  transition: all 0.3s ease;
}
.btn-red:active {
  background: #921e12;
}

/*Other Stylez*/
.wrap {
  margin: 0 auto;
  width: 800px;
  text-align: center;
}
</style>
