<template>
  <div class="container-profile">
    <div class="container-biografia">
      <div class="container-image">
        <img
          class="image-profile"
          src="../assets/caio.jpg"
          width="150"
          alt="foto-autor"
        />
      </div>
      <div class="container-titulo-biografia">
        <h2 class="titulo-biografia">Caio Gomes</h2>
        <p>
          Formado em Análise e Desenvolvimento de Sistemas pela FATEC-Itu,
          trabalho como Desenvolvedor Fullstack na Deal Technologies. Atualmente
          curso Pós-graduação em Arquitetura de software na PUC-Minas
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.container-profile {
  width: 100%;
  display: flex;
  flex-direction: row;
  justify-content: center;
  padding: 20px;
}

.container-biografia {
  max-width: 80%;
  display: inherit;
}

.container-image {
  margin-left: 20px;
}

.container-titulo-biografia {
  padding-top: 20px;
  padding-left: 20px;
}

.image-profile {
  border-radius: 100px;
}

.titulo-biografia {
  font-size: 25px;
  font-weight: 400;
  color: darkgreen;
}
</style>
