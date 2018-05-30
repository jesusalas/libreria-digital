<template>
<v-container>
  <v-form @submit.prevent="submit">
    <v-text-field
      v-model="email"
      label="E-mail"
      required
    ></v-text-field>
    <v-text-field
      label="Contraseña"
      v-model="password"
      type="password"
      required
    ></v-text-field>
    <v-btn color="green" type="submit">Aceptar</v-btn>
  </v-form>
</v-container>
</template>
<script>
export default {
  data () {
    return {
      email: '',
      password: ''
    }
  },
  methods: {
    submit () {
      console.log(`Email es ${this.email} y la contraseña ${this.password}`)
    }
  }
}
</script>
