<template>
  <v-app id="home">
    <!-- <v-container>
       <div class="container-one">
        <div class="prog">
          <p class="prog-one">Программа для каждого</p>
        </div>
        <div class="menu-one">
          <p class="prog-two">Для школьников</p>
          <div class="qator">
            <ul>
              <li class="mini">Мини-группы</li>
              <li class="mini-one">Индивидуальные занятия</li>
              <li class="mini-two">Разговорные практики с носителями языка</li>
              <li class="mini-three">Подготовка кэкзаменам</li>
            </ul>
          </div>
          <div class="button-mini">
            <button class="button-one">Записаться на урок</button>
          </div>
        </div>  -->

    <!-- <div class="menu-two">
          <p class="prog-three">Для школьников</p>
          <div class="qator-one">
            <ul>
              <li class="minis">Мини-группы</li>
              <li class="mini-ones">Индивидуальные занятия</li>
              <li class="mini-twos">Разговорные практики с носителями языка</li>
              <li class="mini-threes">Подготовка кэкзаменам</li>
            </ul>
          </div>
          <div class="button-mini">
            <button class="button-one">Записаться на урок</button>
          </div>
        </div> -->

    <!-- </div>  -->
    <v-container class="main-table">
    <!-- <div class="main-table"> -->
        <img class="img-one" src="../assets/Vector 17.png" alt="">
      <p class="prog">Программа для каждого</p>
      <ul class="main-ul">
        <li class="table-li">
          <p class="prog-one">Для школьников</p>
          <ul class="content-table">
            <li class="mini">Мини-группы</li>
            <li class="mini-two">Индивидуальные занятия</li>
            <li class="mini-three">Разговорные практики с носителями языка</li>
            <li class="mini-for">Подготовка кэкзаменам</li>
          </ul>
          <ul class="content-tables">
            <!-- <button class="button-one">Записаться на урок</button> -->
            <v-btn class="button-one">Записаться на урок</v-btn>
          </ul>
        </li>
        <li class="table-li">
          <p class="prog-one">Для взрослых</p>
          <ul class="content-table">
            <li class="mini">Мини-группы</li>
            <li class="mini-two">Индивидуальные занятия</li>
            <li class="mini-three">Разговорные практики с носителями языка</li>
            <li class="mini-for">Подготовка кэкзаменам</li>
          </ul>
          <ul class="content-tables">
            <!-- <button class="button-one">Записаться на урок</button> -->
            <v-btn class="button-one">Записаться на урок</v-btn>
          </ul>
        </li>
        <li class="table-li">
          <p class="prog-one">Для студентов</p>
          <ul class="content-table">
            <li class="mini">Мини-группы</li>
            <li class="mini-two">Индивидуальные занятия</li>
            <li class="mini-three">Разговорные практики с носителями языка</li>
            <li class="mini-for">Подготовка кэкзаменам</li>
          </ul>
          <ul class="content-tables">
            <!-- <button class="button-one">Записаться на урок</button> -->
            <v-btn class="button-one">Записаться на урок</v-btn>
          </ul>
        </li>
      </ul>
      <img class="img-two" src="../assets/Vector 22.png" alt="">
    <!-- </div> -->
  </v-container>
    <!-- </v-container> -->
  </v-app>
</template>

<script>
export default {
  name: 'Pagevue'
}
</script>

<style scoped>
.main-table {
  max-width: 1200px;
  width: 100%;
  /* border: 1px solid black; */
  margin-left: auto;
  margin-right: auto;
}
.img-one{
    margin-left: 600px;
    width: 30px;
height: 30px;
top: 1248px;
left: 1203px;
border: 1px;
margin-top: 15px;
}
.main-ul {
  display: flex;
  justify-content: space-between;
  text-align: start;
}
.table-li {
  width: 300px;
  height: 350px;
  margin: 50px;
  display: block;
  margin: 30px;
  list-style: none;
  border: 3px solid black;
}
.content-table li{
  display: inline-block;
  width: 250px;
  list-style: none;
  margin-left: 30px;
}
.prog {
  width: 700px;
  height: 82px;
  top: 1282px;
  left: 120px;
  font-family: Raleway;
  font-size: 50px;
  font-weight: 500;
  line-height: 82px;
  letter-spacing: 0em;
  text-align: left;
}
.prog-one {
  text-align: center;
}
.mini {
  width: 191px;
  height: 28px;
  top: 1602px;
  left: 243px;
  font-family: Raleway;
  font-size: 20px;
  font-weight: 400;
  line-height: 28px;
  letter-spacing: 0em;
  text-align: left;
  margin-top: 15px;
}
.mini-two {
  margin-top: 15px;
  width: 328px;
  height: 28px;
  top: 1650px;
  left: 243px;
  font-family: Raleway;
  font-size: 20px;
  font-weight: 400;
  line-height: 28px;
  letter-spacing: 0em;
  text-align: left;
}
.mini-three {
  margin-top: 15px;
  width: 328px;
  height: 56px;
  top: 1698px;
  left: 243px;
  font-family: Raleway;
  font-size: 20px;
  font-weight: 400;
  line-height: 28px;
  letter-spacing: 0em;
  text-align: left;
}
.mini-for {
  margin-top: 15px;
  width: 313px;
  height: 28px;
  top: 1774px;
  left: 243px;
  font-family: Raleway;
  font-size: 20px;
  font-weight: 400;
  line-height: 28px;
  letter-spacing: 0em;
  text-align: left;
}
.button-one {
  width: 188px;
  height: 23px;
  top: 1887px;
  left: 318px;
  font-family: Raleway;
  font-size: 20px;
  font-weight: 500;
  line-height: 23px;
  letter-spacing: 0em;
  text-align: center;
}
.content-tables {
  width: 200px;
  height: 40px;
  margin-left: auto;
  margin-right: auto;
  margin-top: 30px;
  top: 1864px;
  left: 263px;
  border-radius: 15px;
  border: 3px solid black;
}
.img-two{
    width: 30px;
height: 30px;
top: 2011px;
left: 128px;
border: 1px;
margin-top: 5px;

}
/* .container-one {
  display: flex;
  justify-content: space-between;
  border: 1px solid black;
  width: 1200px;
  height: 450px;
  top: 50px;
  left: 120px;
  margin-left: auto;
  margin-right: auto;
  margin-top: 20px;
}
.prog {
  width: 825px;
  height: 82px;
  top: 1282px;
  left: 120px;
}
.prog-one {
  width: 825px;
  height: 82px;
  top: 1282px;
  left: 120px;
  font-family: Raleway;
  font-size: 50px;
  font-weight: 500;
  line-height: 82px;
  letter-spacing: 0em;
  text-align: left;
}
.menu-one {
  width: 220px;
  height: 270px;
  top: 1464px;
  left: 213px;
  border: 3px solid black;
  margin-left: 25px;
}
.prog-two {
  color: #000;
  font-family: Raleway;
  font-size: 20px;
  font-style: normal;
  font-weight: 500;
  line-height: normal;
  text-align: center;
  margin-top: 15px;
  margin-left: 15px;
}
.qator {
    display: flex;
  width: 170px;
  height: 150px;
  flex-shrink: 0;
  border: 1px solid black;
  margin-top: 15px;
  margin-left: 15px;
  margin-right: 15px;
  text-align: start;
  display: inline-block;
}
.mini {
  margin-top: 15px;
  width: 170px;
  color: #000;
  text-align: center;
  font-family: Raleway;
  font-size: 15px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
}
.mini-one {
  margin-top: 10px;
  width: 170px;
  color: #000;
  text-align: center;
  font-family: Raleway;
  font-size: 15px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
}
.mini-two {
  margin-top: 10px;
  width: 170px;
  color: #000;
  font-family: Raleway;
  font-size: 15px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
}
.mini-three {
  margin-top: 10px;
  color: #000;
  text-align: center;
  font-family: Raleway;
  font-size: 15px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
}
.button-mini {
  width: 160px;
  height: 40px;
  flex-shrink: 0;
  border-radius: 15px;
  border-top: 3px solid #000;
  border-right: 7px solid #000;
  border-bottom: 7px solid #000;
  border-left: 3px solid #000;
  background: var(--yellow, #ffcf58);
  margin-top: 10px;
  margin-left: auto;
  margin-right: auto;
}
.button-one {
  color: #000;
  font-family: Raleway;
  font-size: 15px;
  font-style: normal;
  font-weight: 500;
  line-height: normal;
  text-align: center;
  margin-left: 10px;
}
.menu-two{

} */
</style>