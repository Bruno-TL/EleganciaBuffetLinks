<template>
  <div class="container">
    <div class="imgPerfil">
      <div class="imgPerfil__modura">

      </div>  
    </div>
    
    <a href="https://www.instagram.com/buffetelegancia/" target="_blank" class="inst__link">@BuffetElegancia</a>
    
    <div class="linha">

    </div>

    <div class="links">

      <a class="links__unico" href="https://elegancia-buffet.vercel.app/" target="_blank">site</a>
      <a class="links__unico" href="https://api.whatsapp.com/send?phone=558599344210&text=Ol%C3%A1,%20Obrigado%20por%20entrar%20em%20contanto%20com%20a%20gente%20do%20Eleg%C3%A2ncia%20Buffet,%20em%20instantes%20a%20nossa%20Gerente%20de%20Eventos%20ir%C3%A1%20falar%20com%20voc%C3%AA">whatsApp</a>


    </div>

    <div class="creator">
      <a href="https://www.instagram.com/t.bruno__/" target="_blank" class="creator__link">Created by @t.bruno__</a>
    </div>
  </div>
  
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .container{
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 70%;
    height: 100vh;
  }
  .imgPerfil {
    margin-top: 50px;
    margin-bottom: 40px;
  }

  .imgPerfil__modura {
    height: 110px;
    width: 130px;

    background-image: url(../assets/Eb4.png);
    background-size: cover;
    background-repeat: no-repeat;

    border-radius: 50%;
  }

  /* Menção instagram */
  
  .inst__link {
    font-size: 1rem;
    text-decoration: none;
    color: rgb(34, 34, 34);
    font-weight: 600;
    font-family: 'Courier New', Courier, monospace;
    margin-bottom: 20px;
  }

  .inst__link:visited {
    color: rgb(34, 34, 34);
    font-weight: 600;
  }

  .linha {
    margin-top: 10px;
    border: 1px solid rgb(39, 39, 39);
    width: 100%;
  }
  /* Dimnuir o tamanho da letra para o mobile */
  /* Links  */

  .links{
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 80%;
    height: 35vh;
  }

  .links__unico {
    box-sizing: content-box;
    border: 1.5px solid rgb(39, 39, 39);
    width: 70%;
    font-size: 1.4em;
    text-decoration: none;
    text-align: center;
    text-transform: uppercase;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    margin-top: 15px;
    border-radius: 5px;
    color: rgb(34, 34, 34);
    transition-duration: 0.5s;
  }

  .links__unico:hover{
    background-color: #000;
    color: #fff;
    border: 1.5px solid #fff;
  }

  .creator{
    height: 10vh;
    display: flex;
    align-items: end;
    justify-content: center;
    width:200px;
  }

  .creator__link {
    font-size: 1em;
    text-decoration: none;
    color: rgb(109, 109, 109);
  }

  @media screen and (max-width:500px){
    .container{
    width: 100%;
  }

  .inst__link {
    font-size: 1.5rem;
  }

    .linha {
    margin: 20px 0;
    border: 1px solid #000;
    width: 100%;
  }

  .links{
    width: 100%;
    height: 35vh;
  }

  .links__unico {
    box-sizing: content-box;
    border: 2px solid rgb(39, 39, 39);
    width: 90%;
    font-size: 1.6em;
    margin-top: 20px;
  }



  }
</style>
