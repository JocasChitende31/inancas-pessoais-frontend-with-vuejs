

<template>
  <div class="header">
    <nav class="navigation">
      <li class="nav-list">
        <ul class="nav-list-item">
          <RouterLink to="/" style="font-weight: bolder;" >GESTACIONAR.SE</RouterLink>

        </ul>
      </li>
      <li class="nav-list">
        <ul class="nav-list-item">
          <RouterLink to="/meus-ganhos"  >Meus ganhos</RouterLink>
        </ul>
      </li>
      <li class="nav-list">
        <ul class="nav-list-item">
          <RouterLink to="/minhas-despesas">Minhas despesas</RouterLink>
        </ul>
      </li>
      <li class="nav-list">
        <ul class="nav-list-item">
          <RouterLink to="/minhas-poupancas">Minhas poupanças</RouterLink>
        </ul>
      </li>
      <li class="nav-list">
        <ul class="nav-list-item">
          <RouterLink to="/user/name"><i class="large material-icons" >person</i></RouterLink>
        </ul>
      </li>
      <li class="nav-list">
        <ul class="nav-list-item">
          <RouterLink to="/about">Sobre</RouterLink>
        </ul>
      </li>
    </nav>
    <!-- <div class="corrency-amount">
      <div class="corrency">
        <div class="title">
          <h3>AOA-KWZ</h3>
        </div>
      </div>
      <div class="line-devisor">
        <h3></h3>
      </div>
      <div>
        <div class="amount">
          <div class="title">
            <h3>300.000,00</h3>
          </div>
        </div>
      </div>
    </div> -->
    <!-- <div class="title-AOA">
      <h3>AOA-KWZ</h3>
    </div> -->
  </div>
</template>
<script setup></script>
<style>
.header {
  background-color: #f5eee2;
  width: 100%;
  height: 45vh;

  
}

.navigation {
  display: flex;
  justify-content: center;
  padding: .5rem 0;
  list-style: none;
  border-bottom: 1px solid #BF6A0242;
  width: 100%;
  /* margin: 0 auto; */
  letter-spacing: .6px;
  background-color: white;
  z-index: 9;

  position: fixed;
  .nav-list {
    padding: 1rem 1rem;
    z-index: 2;
      .nav-list-item {
        a{
          font-size: 1.1rem;
          font-weight: 500;
        }
      }
  }

}
.border-indigo-500{
  color: hsl(33, 98%, 38%);
}
.border-indigo-700{
/* background-color: hsl(33, 98%, 38%); */
border-bottom: 2px solid hsl(33, 98%, 38%);
position:relative;
border-radius:0;
transition:all .4s ease-in-out;
  
}
.corrency-amount {

  display: flex;
  align-items: center;
  /* justify-content: space-between; */
  padding: .5rem 2rem;
  height: 30vh;
  width: 70%;

  position: absolute;
  z-index: 1;
  top: 73px;
  
  .corrency {
    display: none;
    padding: 100px 75px;
    border-radius: 25px;
    background-color: hsl(33, 98%, 38%, 1);
    transform: rotate(45deg);
    margin: 0 0 0 -150px;

    .title {
      position: relative;
      transform: rotate(-45deg);
      bottom: 100px;
      top: 10px;
      /* margin: 0 0px 0 20px;   */
      color: hsl(33, 98%, 38%, 1);
    }
  }

  .line-devisor {
    width: 830px;
    margin-right: -25px;
    border: .05px solid hsla(33, 98%, 38%, 0.33);
    border-style: dotted;
  }

  .amount {
    /* padding: 20px 5px;
    border-radius: 30px;
    background-color: hsl(33, 98%, 38%, 1);
    transform: rotate(45deg); */

    .title {
     
      /* transform: rotate(-45deg); */
      color: white;
      padding: 10px 20px;

      img{
        width: 200px;
        height: fit-content;
        opacity: .6;
      }

      h3 {
        display: flex;
        position: absolute;
        right: 0px;
        left: 0px;
        top: 0px;
        bottom: 0px;
        font-size: 1.5rem;
        font-weight: 600;
        margin: 0 0px 0 -16px;
        text-align: center;
      }
    }
  }

}
</style>
