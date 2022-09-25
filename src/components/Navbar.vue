<template>
<nav>
  <div class="nav-container">
    <div class="nav-container--left">
      <img src="../assets/sign.png" alt="" class="nav-logo">
      <span class="nav-logo-text">
        <p class="nav-logo-text--left">Garage</p>
        <p class="nav-logo-text--right">Sale</p>
      </span>

    </div>
    <div class="nav-container--right">
        <div class="redirect-buttons">
          <p class="subpage">Messages</p>
          <p class="subpage">Account</p>
          <p class="button">Create</p>
        </div>
    </div>
  </div>
</nav>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Navbar"
}
</script>

<style scoped>
.nav-container{
  padding: 10px 50px 10px 50px;
  display: flex;
  justify-content: space-between;
}
.nav-logo{
  width:48px;
  height: 48px;
}
.nav-logo-text{
  font-family: 'Helvetica', sans-serif;
  font-weight: bold;
  font-size:20px;
  align-items: center;
}
.nav-logo-text--left{
  color: #3B454E;
}
.nav-logo-text--right{
  color:#4BA8DD;
}

.nav-container--left{
  display: flex;
  flex-direction: row;
  gap: 15px;
}

.nav-logo-text{
  display: flex;
  flex-direction: row;
}

nav{
  font-weight: bold;
  border-bottom: 2px solid #C3CBD2;
  font-family: 'Helvetica', sans-serif;
  font-size: 20px;
}
.subpage{
  display: flex;
  align-items: center;
}
.redirect-buttons{
  display: flex;
  align-items: center;
  gap:15px;
  font-size:18px;
}
.nav-container--right{
  display: flex;
  align-content: flex-end;
}
.button{
  background-color: #4BA8DD;
  color: #fff;
  padding: 15px;
  border-radius: 10px;
}
</style>