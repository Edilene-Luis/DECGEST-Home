<template>
  <footer
    class="bg-black w-100 d-flex text-white flex-column align-items-center justify-content-center p-3 text-center"
  >
    <div class="d-flex flex-wrap w-100 justify-content-around">
      <div class="img-container">
        <img
          src="../static/images/logo-footer.jpg"
          class="h-100 w-100"
          alt="logo da DECgest"
        />
      </div>
      <div class="d-sm-block">
        <h3>Navegação</h3>
        <div>
          <a href="#" class="text-decoration-none text-white d-block">ativos</a>
          <a href="#" class="text-decoration-none text-white d-block"
            >Aprendizado</a
          >
          <a href="#" class="text-decoration-none text-white d-block"
            >Simulação</a
          >
        </div>
      </div>
      <div class="text-center d-sm-block">
        <h3>Contatos</h3>
        <div class="d-flex">
          <div class="img-container-icone">
            <img src="../static/ícones/telefone.png" alt="icone de contactos" />
          </div>
          <p class="ml-3">
            +244 928840907 <br />
            +244 934868272
          </p>
        </div>
        <div class="mt-1 d-flex align-content-center">
          <div class="img-container-icone">
            <img src="../static/ícones/o-email.png" alt="icone de e-mail" />
          </div>
          <p class="ml-3">Decgest@gmail.com.ao</p>
        </div>
        <div class="mt-1 d-flex align-items-center">
          <div class="img-container-icone">
            <img src="../static/ícones/endereco.png" alt="icone de endereço" />
          </div>
          <address class="ml-3">Angola, Luanda</address>
        </div>
      </div>
    </div>

    <div class="mx-auto">
      <a href=""
        ><img src="../static/ícones/linkedin.png" width="27" alt=""
      /></a>
      <a href=""
        ><img src="../static/ícones/instagram.png" width="27" alt=""
      /></a>
      <a href=""
        ><img src="../static/ícones/facebook.png" width="27" alt=""
      /></a>
      <a href=""
        ><img src="../static/ícones/whatsapp.png" width="27" alt=""
      /></a>
    </div>
  </footer>
</template>

<script>
export default {}
</script>

<style scoped>
.img-container {
  height: 220px;
  width: 220px;
}
img {
  object-fit: cover;
}

.img-container-icone {
  height: 30px;
  height: 30px;
}
.img-container-icone img {
  height: 100%;
  width: 100%;
}
</style>
