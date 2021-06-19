<template>
  <main>
    <div class="first-view">
      <div class="first-view__img"></div>
      <div class="first-view__text">
        <h2>テキストが入ります</h2>
        <p>
          テキストが入ります。テキストが入ります。テキストが入ります。<br>テキストが入ります。テキストが入ります。テキストが入ります。<br>テキストが入ります。テキストが入ります。テキストが入ります。<br>テキストが入ります。
        </p>
      </div>
    </div>
    <div class="about">
      <h2>ABOUT</h2>
      <div class="about__content">
        <div class="about__img">
          <img src="../assets/IMG_20200717_085928.jpg" alt="ABOUT">
        </div>
        <div class="about__text">
          <p class="about__text--p1">ShionToyoda</p>
          <table>
            <tr>
              <th>生年月日</th>
              <td>1998.09.16</td>
            </tr>
            <tr>
              <th>出身地</th>
              <td>東京都</td>
            </tr>
            <tr>
              <th>趣味</th>
              <td>
                Instagram<br>
                美容<br>
                勉強
              </td>
            </tr>
          </table>
          <p class="about__text--p2">
            テキストが入ります。
            テキストが入ります。
            テキストが入ります。
            テキストが入ります。
            テキストが入ります。
            テキストが入ります。
            テキストが入ります。
            テキストが入ります。
            テキストが入ります。
            テキストが入ります。
            テキストが入ります。
            テキストが入ります。
            テキストが入ります。
            テキストが入ります。
          </p>
        </div>
      </div>
    </div>

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

    <div class="link">
      <div class="link__content">
        <img src="../assets/IMG_20200713_193132.jpg" alt="LINK">
        <div class="link__content--text">
          <h3>SERVICE</h3>
        </div>
      </div>
      <div class="link__content">
        <img src="../assets/IMG_20200713_193102.jpg" alt="LINK">
        <div class="link__content--text">
          <h3>NEWS</h3>
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

.first-view{
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;
  width: 100%;
}

.first-view__img{
  background: url(../assets/IMG_20200719_220848.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  width: 100%;
  height: 600px;
  position: relative;
  top: 120px;
  z-index: -1;
}

.first-view__text{
  width: 80%;
  margin-top:150px;
}

.first-view__text h2{
  padding: 20px 0;
  text-align: center;
  font-size: 20px;
}

.first-view__text p{
  line-height: 30px;
  text-align: center;
  font-size: 15px;
}

.about{
  width: 80%;
  display:flex;
  flex-direction:column;
  align-items:center;
  margin-top:10px!important;
}

.about h2{
  padding: 20px;
}

.about__content{
  display: flex;
  justify-content: center;
}

.about__img{
  width:300px;
}

.about__img img{
  width: 100%;
  border-radius: 10px;
}

.about__text{
  padding: 20px;
  width: 30%;
}

.about__text--p1{
  font-size: 30px;
  margin:10px 0;
}

tr th,td{
  font-size: 15px;
}

th{
  padding: 8px 20px 8px 0;
}

td{
  line-height: 20px;
}

.about__text--p2{
  font-size: 15px;
  padding: 30px 0;
  line-height: 20px;
}

.service{
  width: 80%;
  display:flex;
  flex-direction:column;
  align-items:center;
  margin-top:10px!important;
}

.service h2{
  padding: 0 20px 20px;
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

.news{
  width: 80%;
  margin-top:10px!important;
  margin-bottom:80px!important;
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

.link{
  display: flex;
}

.link__content img{
  width:100%;
  height:100%
}

.link__content{
  position: relative;
}

.link__content::before{
  content: "";
  background-color: rgba(0,0,0,0.5);
  width: 100%;
  height: 100%;
  position: absolute;
}

.link__content--text{
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%);
  color: white;
  font-weight: bold;
  text-align: center;
}

.link__content--text p{
  padding: 10px 0 ;
}

.link__content:hover{
  opacity: 0.7;
}

img{
  width:100%;
}

@media screen and (max-width:768px){
  .service__card--content{
    width:49%;
  }
}

@media screen and (max-width:768px){
  .about__content{
    flex-direction:column;
    align-items:center;
  }
  .about__text{
    width:100%;
    text-align:center;
    display:flex;
    flex-direction:column;
    align-items:center;
  }
}

</style>