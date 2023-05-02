<template>
<nav class="navbar fixed-top navbar-expand-lg bg-success"  >
  <div class="container-fluid">
    <a class="navbar-brand text-light" href="#">プログラミング勉強会</a>
    <button type="button" class="navbar-toggler" data-bs-toggle="collapse" data-bs-target="#Navber" aria-controls="Navber" aria-expanded="false" aria-label="ナビゲーションの切替">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="Navber">
      <ul class="navbar-nav me-auto  mb-2 mb-lg-0">

        <li class="nav-item">
          <a class="nav-link active text-light"  href="#">ホーム</a>
        </li>

        <li class="nav-item">
          <a class="nav-link text-light" href="">資料一覧</a>
        </li>
        
        <li class="nav-item dropdown btn-light">
          <a href="#" class="nav-link dropdown-toggle text-light" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            その他資料
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Java (基礎)</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Java (ラムダ式)</a></li>
            <li><a class="dropdown-item" href="#">その他</a></li>
          </ul>
        </li>

        <li class="nav-item">
          <a class="nav-link active text-light">おすすめの書籍</a>
        </li>
      </ul>
    </div><!-- /.navbar-collapse -->
  </div><!-- /.container-fluid -->
</nav>
</template>

<script>

export default {
  name: 'HeadarMenu',
  components: {
  }
}</script>