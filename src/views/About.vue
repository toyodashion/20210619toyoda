<template>
<main>
  <div class="about">
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
</main>
</template>
<style>
main{
  display: flex;
  flex-direction: column;
  align-items: center;
  width:100%;
  padding:0;
  font-family: 'Noto Serif JP', serif;
}

.about{
  width: 80%;
  margin: 200px 0 0 ;
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
  margin:0;
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