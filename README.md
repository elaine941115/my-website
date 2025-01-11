<!DOCTYPE html>
<html lang="en">
<head>
  <!-- Import Materialize CSS 和 JavaScript -->
  <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css">
  <script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script>
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>

  <title>CAFE!N</title>

  <style>
    .brand-logo img {
      height: 50px; /* 調整 Logo 高度 */
    }
  </style>
</head>
<body>
  <!-- 導航列 -->
  <nav class="white">
    <div class="nav-wrapper container">
      <!-- Logo -->
      <a href="#" class="brand-logo">
        <img src="https://i.ibb.co/BVjrJxp/2025-01-11-10-26-55.png" alt="CAFE!N">
      </a>
      <!-- 漢堡選單 (Mobile) -->
      <a href="#" data-target="mobile-demo" class="sidenav-trigger">
        <i class="material-icons black-text">menu</i>
      </a>
      <!-- Desktop 選單 -->
      <ul class="right hide-on-med-and-down">
        <li><a href="//jsfiddle.net/yungchihsu/ez56aqnx/embed/result/" class="black-text">飲品</a></li>
        <li><a href="snacks.html" class="black-text">輕食</a></li>
        <li><a href="join.html" class="black-text">加入會員</a></li>
      </ul>
    </div>
  </nav>

  <!-- 漢堡選單內容 (Mobile) -->
  <ul class="sidenav" id="mobile-demo">
    <li><a href="https://jsfiddle.net/yungchihsu/ez56aqnx/1/show/" class="black-text">飲品</a></li>
    <li><a href="snacks.html">輕食</a></li>
    <li><a href="join.html">加入會員</a></li>
  </ul>

  <!-- 主內容區域 -->
  <div class="container">
    <h1></h1>
    <p>探索我們的飲品與輕食，或者加入會員享受更多優惠！</p>
  </div>

  <!-- 頁腳 -->
  <footer class="page-footer grey lighten-3">
    <div class="container">
      <p class="black-text">© 2025 CAFE!N</p>
    </div>
  </footer>

  <script>
    // 初始化漢堡選單 (Mobile)
    document.addEventListener('DOMContentLoaded', function() {
      var elems = document.querySelectorAll('.sidenav');
      var instances = M.Sidenav.init(elems);
    });
  </script>
</body>
</html>
</html>
