<template>
  <div>
    <div class="container-tecnologia">
      <p class="titulo-tecnologia">{{ title }}</p>
      <div class="container-nivel">
        <div :style="nivelStyle">{{ porcentagem }}%</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      required: true,
    },
    porcentagem: {
      type: Number,
      required: true,
      default: 0,
    },
    color: {
      type: String,
      required: true,
    },
  },
  computed: {
    nivelStyle() {
      return {
        width: `${this.porcentagem}%`,
        background: this.color,
        'text-align': 'center',
        'border-radius': `${20}px`,
        color: 'white',
      }
    },
  },
}
</script>

 <style scoped>
.container-tecnologia {
  display: flex;
  padding: 20px 0;
  align-items: center;
}
.container-nivel {
  width: 200px;
  margin-left: 10px;
  background: gray;
  border-radius: 20px;
  text-align: center;
}

.titulo-tecnologia {
  font-size: 25px;
  font-weight: 400;
  width: 120px;
  margin: 10px;
}
</style>
