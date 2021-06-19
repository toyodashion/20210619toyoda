<template>
<main>
  <div class="service">
    <h2>SERVICE</h2>
    <div class="service__card">
      <div class="service__card--content">
        <img src="../assets/moii_thumb.jpg" alt="SERVICE">
        <div class="service__card--content--text">
          <h3>題名が入ります</h3>
          <p>テキストが入ります。テキストが入ります。</p>
        </div>
      </div>
      <div class="service__card--content">
        <img src="../assets/moii_thumb.jpg" alt="SERVICE">
        <div class="service__card--content--text">
          <h3>題名が入ります</h3>
          <p>テキストが入ります。テキストが入ります。</p>
        </div>
      </div>
      <div class="service__card--content">
        <img src="../assets/moii_thumb.jpg" alt="SERVICE">
        <div class="service__card--content--text">
          <h3>題名が入ります</h3>
          <p>テキストが入ります。テキストが入ります。</p>
        </div>
      </div>
      <div class="service__card--content">
        <img src="../assets/moii_thumb.jpg" alt="SERVICE">
        <div class="service__card--content--text">
          <h3>題名が入ります</h3>
          <p>テキストが入ります。テキストが入ります。</p>
        </div>
      </div>
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

.service{
  width: 80%;
  display:flex;
  flex-direction:column;
  align-items:center;
}

.service h2{
  padding: 20px;
}

.service__card{
  width: 100%;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}

.service__card img{
  border-radius: 10px;
}

.service__card--content{
  width: 24%;
  margin: 0 0 25px 0;
}

.service__card--content--text h3{
  padding: 5px 0;
  font-size: 15px;
  font-weight: bold;
}

.service__card--content--text p{
  font-size: 15px;
  padding: 5px 0;
}
</style>
