.header {
  padding: 0 50px;
  background-color: rgb(255, 255, 255);
  max-width: 1500px;
  gap: 100px;
}
.head__wrap {
  display: flex;
  align-items: center;  
  justify-content: space-between;  
  gap: 50px;
    &__nav-bar{
      width: 100%;
      height: 50px;
      display: flex;
      justify-content: center;  
      align-items: center;
      gap: 50px;
      max-width:600px ; 
    }

    &__head__logo{
      max-width: 150px;
      width: 100%;
      height: 100%;
      img{
        width: 100%;
        height: 100%;
      }
    }
}
.head__button {
  width: 200px;
  height: 70px;
  text-align: center;
  color: #fff;
  background: #FF8541;
  border-radius: 15px;
  border: none;
}

.kelajak{
  padding: 0 50px;
  }


  .sect__wrap{
    padding: 0 50px;
    &__button{
      display: flex;
      justify-content: flex-end;
        button{
          max-width: 100px;
          width :100%;
          height: 40px;
          border-radius: 5px;
        }
    }

    &__title{
      max-width: 400px;
      width: 100%;
      height: 100%;
    }
  }
  

.news__wrap{
  padding:0 50px;
  &__images{
   display: flex; 
   gap: 25px;
  }

  &__title{
    max-width: 200px;
    width: 100%;
    height: 30px;
  }
}


/*# sourceMappingURL=main.css.map */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  html,
  body,
  .wrapper {
    width: 100%;
    height: 100%;
  }
  

  .continer {
    max-width: 1700px;
    width: 100%;
    padding: 0 20px;
    margin: 0 auto;
  }
  
  a {
    text-decoration: none;
    color: inherit;
  }
  
  .button {
    cursor: pointer;
    border: none;
    background-color: transparent;
  }