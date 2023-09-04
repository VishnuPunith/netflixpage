<template>
  
  <body>
    <link href="https://db.onlinewebfonts.com/c/0d5f8cc3c1312e1f7c94b4ccf48733c0?family=NetflixSans-Icon" rel="stylesheet">
    <div class="container">
      <div class="navbar">
        <nav class="head">
    <img src="../src/assets/12net.png" class="image">
    </nav>
    <div class="button">
      <div class="select">
        <span><svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg" id="globe" class="default-ltr-cache-0 e1mhci4z1" data-name="Globe" aria-hidden="true"><path fill-rule="evenodd" clip-rule="evenodd" d="M8 14.5C8.23033 14.5 8.84266 14.2743 9.48679 12.986C9.76293 12.4337 9.99973 11.7621 10.1748 11H5.8252C6.00027 11.7621 6.23707 12.4337 6.51321 12.986C7.15734 14.2743 7.76967 14.5 8 14.5ZM5.57762 9.5C5.52716 9.02077 5.5 8.51911 5.5 8C5.5 7.48089 5.52716 6.97923 5.57762 6.5H10.4224C10.4728 6.97923 10.5 7.48089 10.5 8C10.5 8.51911 10.4728 9.02077 10.4224 9.5H5.57762ZM11.7092 11C11.4822 12.1217 11.1317 13.117 10.6914 13.9184C12.0137 13.3161 13.0987 12.2837 13.7678 11H11.7092ZM14.3261 9.5H11.9298C11.9759 9.01412 12 8.51269 12 8C12 7.48731 11.9759 6.98588 11.9298 6.5H14.3261C14.4398 6.98152 14.5 7.48373 14.5 8C14.5 8.51627 14.4398 9.01848 14.3261 9.5ZM4.0702 9.5H1.67393C1.56019 9.01848 1.5 8.51627 1.5 8C1.5 7.48373 1.56019 6.98152 1.67393 6.5H4.0702C4.02411 6.98588 4 7.48731 4 8C4 8.51269 4.02411 9.01412 4.0702 9.5ZM2.23221 11H4.29076C4.51779 12.1217 4.86832 13.117 5.30864 13.9184C3.98635 13.3161 2.90128 12.2837 2.23221 11ZM5.8252 5H10.1748C9.99973 4.23793 9.76293 3.56626 9.48679 3.01397C8.84266 1.72571 8.23033 1.5 8 1.5C7.76967 1.5 7.15734 1.72571 6.51321 3.01397C6.23707 3.56626 6.00027 4.23793 5.8252 5ZM11.7092 5H13.7678C13.0987 3.71627 12.0137 2.68389 10.6914 2.08162C11.1317 2.88302 11.4822 3.8783 11.7092 5ZM5.30864 2.08162C4.86832 2.88302 4.51779 3.8783 4.29076 5H2.23221C2.90128 3.71628 3.98635 2.68389 5.30864 2.08162ZM8 0C12.4183 0 16 3.58172 16 8C16 12.4183 12.4183 16 8 16C3.58172 16 0 12.4183 0 8C0 3.58172 3.58172 0 8 0Z" fill="currentColor"></path></svg></span>
      <select id="afe4f46e7a749" name="LanguageSelect" data-uia="language-picker-header">
        <option selected="" lang="en" class="option" label="English" value="en-IN">English</option>
        <option lang="hi" label="हिन्दी"  class="option" value="hi-IN">हिन्दी</option>
      </select>
      </div>
        <a href="#" class="Signin"><span>Sign In</span></a>
      </div>
      </div>
      <div style="padding: 75px 0 20px;">
      <div>
   <header class="heads">
<h1 class="text">
Enjoy big movies, hit series and more from ₹ 149.</h1>
<p class="para">Join today. Cancel anytime.</p>
<p class="para">Ready to watch? Enter your email to create or restart your membership.
</p>
<div class="input">
  <input autocomplete="email" minlength="5" maxlength="50" type="email" class="search" id="82f7235321951" name="email" data-uia="field-email" value="">
   <button type="text" id="start">Get Started</button>
</div>
   </header>
  </div>
</div>
  </div>
  </body>
</template>


<style>
body{
  /* background-image: linear-gradient(to top, rgba(0, 0, 0, 0.8) 0, rgba(0, 0, 0, 0) 60%, rgba(0, 0, 0, 0.8) 100%), url("../src/assets/bg.jpg"); */
  height: 100vh;

  @media (max-width: 480px){
    height: 100vh;

  
   }
  
}
.para{
  color: white;
  display: flex;
  margin: 0;
  letter-spacing: .8px;
}
.container{
  background-image: linear-gradient(to top, rgba(0, 0, 0, 0.8) 0, rgba(0, 0, 0, 0) 60%, rgba(0, 0, 0, 0.8) 100%), url("../src/assets/bg.jpg");
   background-size: cover;
   height: 100%;

   @media (max-width: 480px){
    background-size: cover;
    height: 100%;
   }
}
.heads{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 16px;
}
.input{
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  width: 50%;
  gap: 2px;
  padding: 38px;
}
.search{
  width: 100%;
  height: 56px;
  background-color: rgba(0, 0, 0, 0.8);
  border: 1px solid white;
  color: white;
  border-radius: 3px;
}
.search:active,
.search:focus
{
  outline: none;
}
.text{
color: white;
margin: 0;

}
.Signin{
  text-decoration: none;
  color: white;
  background-color: #E50914;
  padding: 6px 36px;
  font-family: "NetflixSans-Icon";
  font-size: 14px;
  display:flex;
  border-radius: 4px;
  letter-spacing: .5px;
}
#start
{
  height: 60px;
    padding: 13px 20px;
    white-space: nowrap;
    font-weight: 700;
    border-radius: 4px;
    font-size: 23px;
    color: white;
    background-color: #E50914;
}
.navbar {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 71px;
    height: 100px;

    @media (max-width: 480px){
      padding: 0 100px;
      height: 20px;
   }
}

.head{
  height:100px;
  size: 12px;
}
.image{
  height: inherit;

  @media (max-width: 480px){
    height: inherit;

   }
}
.button{
  display: flex;
  align-items: center;
  gap: 20px;
}
#afe4f46e7a749{
  background-color: transparent;
  color: white;
  border: none;
}

#afe4f46e7a749:active,
#afe4f46e7a749:focus
{
  outline: none;
 
}
#82f7235321951:active,
#82f7235321951:focus
{
  outline: none;
  background-color: rgba(0, 0, 0, 0.8);;
}
.select{
  border: 1px solid white;
  padding: 6px 36px;
  border-radius: 4px;
  display: flex;
  gap: 2px;


  
}
.option{
  color: black;
}
#globe{
  color: white;
}
@media (max-width: 599.98px){

  .container{

 background-color: #E50914;
  }
}
</style>
