<template>
  <v-app>
    <v-container fluid>
      <div class="table">
        <v-col class="col">
          <v-row>
            <div>
              <v-card  max-width="120px" height="">
                <v-card-text class="card-one"> Как проходят уроки? </v-card-text>
              </v-card>
            </div>
            <!-- <v-card class="mw-auto" max-width="120px" height="" border="2px solid red">
            <v-card-text class="card"> Как проходят уроки? </v-card-text>
            </v-card> -->
          </v-row>
        </v-col>
        <v-col cols="6">
          <v-card class="card-two">
            <div class="birinchi">
              <v-btn class="btn">Разминка</v-btn>
              <h4 class="text-one">Начинаем занятие с проверки устной части домашнего задания</h4>
            </div>
          </v-card>
        </v-col>
      </div>
    </v-container>
  </v-app>
</template>

<script>
export default {}
</script>

<style scoped>
.v-container {
  display: inline-block;
  width: 1100px;
  height: 600px;
  top: 2187px;
  left: 130px;
  border: 2px solid black;
  margin-left: 40px;
  margin-right: 20px;
}
.table {
  max-width: 1200px;
  height: 600px;
  margin-left: 20px;
}
.col {
  width: 50px;
  height: 200px;
  margin-top: 100px;
}

.card-one {
  width: 600px;
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
.card-two {
  width: 180px;
  height: 70px;
  top: 2405px;
  left: 120px;
  border-radius: 35px;
  border: 2px solid black;
}
.btn {
width: 200px;
height: 70px;
top: 2482.645751953125px;
left: 120px;
border-radius: 35px;
border: 2px solid black;
margin-top: 5px;
transform: skew(0deg, -6deg);
}

</style>