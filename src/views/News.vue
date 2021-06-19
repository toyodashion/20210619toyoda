<template>
  <main>
    <div class="news">
      <h2>NEWS</h2>
      <div class="news__content">
        <dl><a href="">
          <dt>2021.06.18</dt>
          <dd>【重要なおしらせ】テキストが入ります。</dd>
        </a></dl>
        <dl><a href="">
          <dt>2021.06.18</dt>
          <dd>【重要なおしらせ】テキストが入ります。</dd>
        </a></dl>
        <dl><a href="">
          <dt>2021.06.18</dt>
          <dd>【重要なおしらせ】テキストが入ります。</dd>
        </a></dl>
        <dl><a href="">
          <dt>2021.06.18</dt>
          <dd>【重要なおしらせ】テキストが入ります。</dd>
        </a></dl>
      </div>
    </div>
  </main>
</template>

<style>
main{
  display: flex;
  flex-direction: column;
  align-items: center;
  width:100%;
  padding:0;
  margin:0;
  font-family: 'Noto Serif JP', serif;
}

.news{
  width: 80%;
  margin-top:150px!important;
}

.news h2{
  padding: 0 0 10px 0;
  text-align:center;
}

.news dl{
  border-bottom: black solid 1px;
  padding: 10px;
}

.news dt{
  padding: 10px;
}

.news dd{
  margin:0;
}
</style>
