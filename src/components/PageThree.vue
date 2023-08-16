<template>
  <v-app>
    <v-container fluid="boolean">
      <div class="container">
      <div class="table">
        <v-col class="col-2">
          <v-row>
            <div>
              <img class="image-one" src="../assets/Vector 19.png" alt="">
              <v-card max-width="120px" height="">
                <p class="card-one"> Как проходят уроки? </p>
              </v-card>
            </div>
            <div class="panel">
             <v-col class="mt-12 oyna-one">
             <v-btn variant="text">Разминка</v-btn>
             <p>Начинаем занятие с проверки устной части домашнего задания</p>
            </v-col>

             <v-col class="mt-12 ikki">
             <v-btn class="mt-2" color="#FBDF7E">Погружение</v-btn>
             <p>Начинаем занятие с проверки устной части домашнего задания</p>
            </v-col>
          </div>

          <div class="panel-one">
            <img class="image-two" src="../assets/Vector 22.png" alt="">
             <v-col class="mt-12 oyna-two">
             <v-btn variant="text">Практика</v-btn>
             <p>Начинаем занятие с проверки устной части домашнего задания</p>
            </v-col>
            </div>

            <div class="panel-two">
             <v-col class="mt-12 oyna-one">
             <v-btn variant="text">
              Закрепление
            </v-btn>
             <p>Начинаем занятие с проверки устной части домашнего задания</p>
            </v-col>
             <v-col class="mt-12 uch">
             <v-btn class="mt-2 rass" color="#FBDF7E">Рассрабление</v-btn>
             <p>Начинаем занятие с проверки устной части домашнего задания</p>
            </v-col>
          </div>
          <img class="image-uch" src="../assets/Vector 20.png " alt="">

            <!-- <v-card class="mw-auto" max-width="120px" height="" border="2px solid red">
            <v-card-text class="card"> Как проходят уроки? </v-card-text>
            </v-card> -->
          </v-row>
        </v-col>
        <!-- <div class="hire" style="d-flex">
          <v-col class="" cols="12" sm="8">
            <v-btn class="mt-15 button" style="border: 1px solid orange; margin-top: 5px; width: 100px height: 15px;">
              Разминка
            </v-btn>
            <p>Начинаем занятие с проверки устной части домашнего задания</p>
          </v-col>
        </div> -->

        <!-- <div class="hire-one">
          <v-col class="" cols="12" sm="8">
            <v-btn class="mt-15 button" style="border: 1px solid orange; width: 100px height: 15px;">
              Разминка
            </v-btn>
            <p>Начинаем занятие с проверки устной части домашнего задания</p>
          </v-col>
        </div>

        <div class="hire">
          <v-col class="" cols="12" sm="8">
            <v-btn class="mt-15 button" style="border: 1px solid orange; width: 100px height: 15px;">
              Разминка
            </v-btn>
            <p>Начинаем занятие с проверки устной части домашнего задания</p>
          </v-col> -->
        <!-- </div> -->
      </div>
    </div>
    </v-container>
  </v-app>
</template>

<script>
export default {}
</script>

<style scoped>
.container {
  width: 1100px;
  height: 600px;
  top: 2187px;
  left: 130px;
  margin-left: auto;
  margin-right: auto;
  margin-top: 50px;
  margin-bottom: 40px;
  align-items: center;
}
.table {
  /* display: flex;
  justify-content: space-between;
  text-align: start; */
  max-width: 1200px;
  height: 600px;
  margin-left: 20px;
}
.col {
  width: 50px;
  height: 200px;
}
.image-one{
  width: 25px;
  height: 25px;
  margin-left: 700px;
  margin-top: 0px;
}

.card-one {
  width: 500px;
  height: 82px;
  top: 2222px;
  left: 120px;
  font-family: Raleway;
  font-size: 50px;
  font-weight: 500;
  line-height: 82px;
  letter-spacing: 0em;
  text-align: left;
}

/* .hire {
  display: inline-block;
  display: flex;
  border: 1px solid rgb(211, 41, 41);
  width: 300px;
  height: 100px;
  top: 2405px;
  border: 2px 5px 5px 2px;
}
.hire p{
  margin-left: 30px;
  font-size: 15px;
  margin-top: 25px;
}
/* .hire {
  margin-top: 10px;
  border: 1px solid black;
} 
.hire-one{
  margin-top: 10px;
  border: 1px solid black;
  width: 350px;
  height: 90px;
  margin-left: 500px;
} */
.oyna-one{
  width: 300px;
  height: 70px;
  margin-left: 5px;
}
.oyna-one p{
  margin-left: 60px;
  width: 270px;
  height: 30px;
  margin-top: 15px;
}
.panel{
  display: flex;
}
.ikki{
  margin-left: 300px;
}
.ikki p{
  margin-left: 60px;
  width: 270px;
  height: 30px;
  margin-top: 15px;
}
.panel-one{
  width: 400px;
  height: 40px;
  display: flex;
  margin-top: 20px;
  margin-left: 4px;
}
.oyna-two{
  margin-left: 100px;
  width: 270px;
  height: 30px;
  margin-top: 15px;
}
.oyna-two p{
  margin-left: 60px;
  width: 270px;
  height: 30px;
  margin-top: 10px;
}
.panel-two{
  display: flex;
  margin-top: 60px;
}
.uch{
  margin-top: 10px;
  margin-left: 300px;
}
.uch p{
  margin-left: 60px;
  width: 270px;
  height: 30px;
  margin-top: 15px;
}
.image-two{
  margin-left: 200px;
  margin-top: 15px;
}
.image-uch{
  margin-left: 1100px;
  margin-top: 30px;
}
.rass{
  width: 300.0000107759783px;
height: 70.00000251439494px;
top: 2894.519287109375px;
left: 1071.6807861328125px;
border-radius: 5px;
border: 2px 5px 5px 2px solid black;
}

</style>