<template>
  <div>
      <div class="nav-container">
          <img src="@/assets/images/logosmk.png" class="logosmk"/>
          <div class="headerText">
              <h1>PERPUS DIGIAL
                  SMKN 4 TASIKMALAYA</h1>
          </div>
          <h4>KAMBING TUA</h4>
          <img src="@/assets/images/logoclub.png" class="logoclub"/>

          
      </div>
  </div>
</template>

<script setup>

</script>
<style scoped>
*{
margin: 0;
z-index: 1;
}
.nav-container {
  background-color:#FF9900;
  width: 100%;
  height: 150px;
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
}

.logoclub {
  width: 100px;
  height: 90px;
}

.logosmk{
  width: 111px;
  height: 126px;

}
h1 {
  color: #ffffff;
  text-align: right;
  font-family: '';
  font-size: 20px;
  letter-spacing: 9px;
  font-weight: 50;
  line-height: normal;

}

h4{
  color: #ffffff;
  text-align: right;
  font-size: 50px;
  letter-spacing: 4px;
  font-weight: 60;
}

@media (max-width: 520px) {
.nav-container {
    background-color:#FF9900;
    width: 100%;
    height: 80px;
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
}

.logoclub {
    width: 150px;
    height:100px;
}
  
}
.logosmk{
    width: 46.077px;
    height: 50px;

}
h1 {
  color: #ffffff;
    text-align: right;
    font-family: '';
    font-size: 26px;
    letter-spacing: 4px;
    font-style: 'bold';
  
}
  
  h4{
    color: #ffffff;
    text-align: center;
    font-family: 'Charm', cursive;
    font-size: 35px;
    letter-spacing: 2px;
    font-style: 'bold';
    font-weight: 60;
}

@media (max-width: 820px) {
.nav-container {
    background-color:#FF9900;
    width: 100%;
    height: 130px;
    display: flex;
      justify-content: space-evenly;
    align-items: center;
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
  }
  
  .logoclub {
      width: 100px;
      height:118px;
  }
  
  
  .logosmk{
      width: 80.077px;
      height: 80px;
  
  }
  h1 {
      color: #EFDE79;
      text-align: center;
      font-family: '';
      font-size: 15px;
      letter-spacing: 2px;
      font-style: 'bold';
  
  }
  
  h4{
      color: #fff9c2;
      text-align: left;
      font-family: 'Charm', cursive;
      font-size: 12px;
      font-weight: 60;
  }
  #name {
    width: 335px;
    height: 50px;
    font-size: 20px;
    padding-left: 15px;
    background-color: #fff9c2;
    filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.25));
    border-radius: 50px;
    border-style: hidden;
}
#kategori {
    width: 335px;
    height: 50px;
    font-size: 20px;
    padding-left: 15px;
    background-color: #fff9c2;
    filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.25));
    border-radius: 50px;
    border-style: hidden;

}
#keperluan {
    width: 335px;
    height: 50px;
    font-size: 20px;
    padding-left: 15px;
    background-color: #fff9c2;
    filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.25));
    border-radius: 50px;
    border-style: hidden;
}
/* End Visitor Style */
/* History Style */
.showData {
    background-color: #483800ec;
    display: flex;
    flex-direction: column;
    padding: 60px 5px 5px 0px;
}

.table-responsive{
    border: 2px solid #A59663;
    font-family: 'Chau Philomene One', sans-serif;
    color: wheat;
    margin: 15px;
    letter-spacing: 3px;

}
}
</style>