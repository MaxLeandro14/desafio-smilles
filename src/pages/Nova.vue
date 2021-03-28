<template>
  <div>
    <q-toolbar style="background: rgb(251, 251, 251); border-bottom: 1px solid #e8e4e4;">
      <q-btn  @click="back" flat round dense icon="keyboard_backspace"/>
    <q-toolbar-title class="primary-font" style="font-size: 16px;">
    Nova meta
    </q-toolbar-title>
    </q-toolbar>
   </div>
</template>

<script >

export default {
  name: 'CriarSala',
  components: {
  },
  data () {
    return {
      step: 1,
      dataNova: '',
      nomeLivro: null,
      totalPagina: null,
      totalParticip: null,
      debates: '',
      range: {
        start: '',
        end: ''
      },
      loadingCR: false,
      msgIcon: '',
      msgDR: '',
      persDR: false,
      dataHoje: new Date(),
      idSala: ''
    }
  },
  methods: {
    back: function () {
    }
  }
}
</script>
<style>
.title-data{
  color: rgb(86, 86, 86);
  font-size: 16px;
  background: #fbfbfb;
  padding: 8px 3px 20px 7px;
  border-radius: 7px;
}
.date-blue {
  color: #1976d2;
}
.date-red{
  color: #e53e3e;
}
.date-blue{
  color: #9c27b0;
}
.text-h {
  font-size: 16px;
  padding: 17px 0px;
  text-align: center;
}
</style>
