<template>
  <div>
    <div class="container">
      <ProfileComponent />
    </div>
    <div class="container">
      <div class="container-tecnologias">
        <div class="sub-container-tecnologias">
          <h2 class="titulo-tecnologia">Tecnologias</h2>
          <hr />
          <div class="painel-tecnologia">
            <TecnologiasComponent
              title="Flutter"
              porcentagem="50"
              color="darkgreen"
            />
            <TecnologiasComponent
              title="C#"
              porcentagem="75"
              color="darkgreen"
            />

            <TecnologiasComponent
              title="HTML"
              porcentagem="80"
              color="darkgreen"
            />
            <TecnologiasComponent
              title="CSS"
              porcentagem="60"
              color="darkgreen"
            />
            <TecnologiasComponent
              title="JavaScript"
              porcentagem="70"
              color="darkgreen"
            />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.container-tecnologias {
  width: 100%;
  display: flex;
  justify-content: center;
}

.sub-container-tecnologias {
  width: 80%;
  display: inherit;
  padding: 20px 40px;
  flex-direction: column;
}
.titulo-tecnologia {
  font-size: 40px;
  font-weight: 400;
  color: darkgreen;
  margin-bottom: 10px;
}

.painel-tecnologia {
  display: flex;
  flex-wrap: wrap;
}
</style>
<script>
</script>
