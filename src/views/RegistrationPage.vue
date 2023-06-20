<template>
  <div class="registerNewUser">
    <h1>Registration page for new users</h1>

    <input type="text" placeholder="Enter Name"/>
    <input type="text" placeholder="Enter Email ID"/>
    <input type="password" placeholder="Enter New Password"/>
    <input type="password" placeholder="Confirm Password"/>
    <button> Register</button>

  </div>
</template>

<style>
@media (min-width: 1024px) {
  .registerNewUser input{
   
    width: 300px;
    height: 40px;
    padding-left: 20px;
    display: block;
    margin-bottom: 30px;
    margin-right: auto;
    margin-left: auto;
    border: 1px solid skyblue;
  }
}

</style>
