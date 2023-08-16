<template>
  <v-app id="home">
    <div class="container">
    <v-container class="main-table">
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

            <v-btn class="button-one">Записаться на урок</v-btn>
          </ul>
        </li>
      </ul>
      <img class="img-two" src="../assets/Vector 22.png" alt="">
  </v-container>
  </div>
  </v-app>
</template>

<script>
export default {
  name: 'Pagevue'
}
</script>

<style scoped>
.container{
  max-width: 1200px;
  width: 100%;
  height: 600px;
  margin-left: auto;
  margin-right: auto;
  margin-top: 20px;
}
.main-table {
  max-width: 1200px;
  width: 100%;
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
  border-radius: 30px;
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
  background-color: orange;
  text-align: center;
}
.img-two{
    width: 30px;
height: 30px;
top: 2011px;
left: 128px;
border: 1px;
margin-top: 5px;
}
</style>