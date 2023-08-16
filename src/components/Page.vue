<template>
  <v-app id="home">
    <div class="container">
      <div class="head">
        <div class="navbar">
          <img src="../assets/Logo.png" alt="" />
          <ul class="navbar-nav">
            <li class="link"><a href="">О школе</a></li>
            <li class="linkt"><a href="">Преимущества</a></li>
            <li class="linkr"><a href="">Адрес</a></li>
          </ul>
          <p class="nomer">8 800 780 90 90</p>
        </div>
      </div>
      <div class="row1">
        <div>
          <p class="p1">Курсы Qorakul School в Сырдарье</p>
          <p class="p2">Курсы, которые тебе точно понравятся</p>
          <p class="p3">
            Пройди бесплатный экспресс-тест на знание языка и мы подберем подходящую программу
          </p>

          <button class="btn">Перейти на Kundalik</button>
        </div>
        <img class="image-one" src="../assets/vector15.png" />
        <div class="menu-two">
          <img src="../assets/Illustration.png" class="img-one" />
        </div>
        <img class="image-two" src="../assets/vector 16.png" />
      </div>
    </div>

    <div class="info">
      <div class="icon">
        <img class="vector-one" src="../assets/Vector 14.png" />
      </div>
      <div class="infoo">
        <div class="info-one">
          <h1 class="besh">> 5 000</h1>
          <p class="page1">Успешных студентов прошедших наши курсы</p>
        </div>
        <div class="info-one">
          <h1 class="besh">> 95%</h1>
          <p class="page1">Освоили наши курсы без проблем</p>
        </div>

        <div class="info-one">
          <h1 class="besh">> 9 из 10</h1>
          <p class="page1">Студентов активно используют знания полученные на курсах</p>
        </div>
      </div>
    </div>
  </v-app>
</template>

<script>
export default {}
</script>

<style scoped>
.container {
  width: 1200px;
  height: 600px;
  top: 50px;
  left: 120px;
  margin-left: auto;
  margin-right: auto;
  margin-top: 20px;
  margin-bottom: 20px;
}

.head {
  float: right;
  width: 1150px;
  height: 60px;
  top: 50px;
  left: 147px;
  margin-left: 15px;
  margin-right: 15px;
  margin-bottom: 100px;
}
.link {
  width: 100px;
  height: 58px;
  top: 50px;
  left: 577px;
  font-family: Raleway;
  font-size: 24px;
  font-weight: 600;
  line-height: 28px;
  letter-spacing: 0em;
  text-align: left;
  margin-top: 10px;
}
.linkt {
  width: 177px;
  height: 28px;
  top: 65px;
  left: 827px;
  opacity: 0.75px;
  font-family: Raleway;
  font-size: 24px;
  font-weight: 500;
  line-height: 28px;
  letter-spacing: 0em;
  text-align: left;
}
.linkr {
  width: 73px;
  height: 28px;
  top: 65px;
  left: 1154px;
  opacity: 0.75px;
  font-family: Raleway;
  font-size: 24px;
  font-weight: 500;
  line-height: 28px;
  letter-spacing: 0em;
  text-align: left;
}
.logo {
  margin-left: 300px;
}
.nomer {
  width: 200px;
  height: 28px;
  font-size: 24px;
  /* font-weight: 500;
  line-height: 28px; */
  letter-spacing: 0em;
  float: right;
}
.school {
  width: 70px;
  height: auto;
  top: 54px;
  left: 147px;
  padding: 5px;
}
.row1 {
  display: flex;
  width: 500px;
  height: 400px;
  margin-top: 40px;
}
.image-one {
  margin-top: 0px;
  margin-left: 90px;
  widows: 50px;
  height: 50px;
}
.p1 {
  width: 350px;
  height: 22px;
  top: 250px;
  left: 90px;
  font-family: Raleway;
  font-size: 18px;
  font-weight: 400;
  line-height: 28px;
  letter-spacing: 0em;
  text-align: left;
}
.p2 {
  width: 450px;
  height: 100px;
  margin-top: 15px;
  font-family: Raleway;
  font-size: 50px;
  font-weight: 300;
  line-height: 10px;
  letter-spacing: 0em;
  text-align: left;
  line-height: 50px;
}
.p3 {
  width: 500px;
  height: 85px;
  font-family: Raleway;
  font-size: 25px;
  font-weight: 200;
  letter-spacing: 0em;
  text-align: left;
  margin-top: 20px;
}
.btn {
  width: 200px;
  height: 50px;
  background: rgb(228, 188, 26);
  margin-top: 15px;
}
.menu-two {
  width: 400px;
  height: 380px;
  margin-left: 2px;
  /* border: 2px solid black; */
}
.img-one {
  width: 400px;
  height: 400px;
  margin-left: 0px;
  margin-top: 0px;
  height: 365px;
  /* border: 1px solid green; */
  margin-bottom: 0px;
}
.image-two {
  width: 50px;
  height: 50px;
  margin-top: 250px;
  margin-left: 15px;
}
.info {
  /* background: rgb(199, 186, 36); */
  width: 1100px;
  height: 200px;
  flex-shrink: 0;
  margin: auto;
  align-items: center;
}
.vector-one {
  margin-left: 230px;
}
.info-one {
  width: 250px;
  height: 130px;
  /* border: 1px solid black; */
  display: inline-block;
  margin-top: 5px;
  margin-left: 15px;
  margin-bottom: 1px;
}
.icon {
  width: 1100px;
  height: 60px;
  margin-top: 5px;
  /* left: 695px;*/
}
.besh {
  width: 176px;
  height: 56px;
  top: 1000px;
  left: 343px;
}
.page1 {
  width: 386;
  height: 76px;
  top: 1106px;
  left: 238px;
}
.infoo {
  display: flex;
  justify-content: space-between;
  text-align: start;
  width: 1100px;
  height: 150px;
  top: 1000px;
  left: 238px;
}

/* .icon-one {
  width: 49.99999932694132px;
  height: 49.99999932694132px;
  top: 200px;
  left: 1080px;
  border: 1px; }*/

/* icon style */

.info {
  /* display: flex;
  justify-content: space-between; */
  margin-top: 2px;
}
/* icon style */

/* navbar style */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.navbar-nav {
  display: flex;
  align-items: center;
}
.navbar-nav li {
  margin: 0px 50px;
}
/* navbae-end */
</style>
