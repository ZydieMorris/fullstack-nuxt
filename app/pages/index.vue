<template>
  <div>
    <ul v-for="fruit in data?.database">
      <li>{{ fruit }}</li>
    </ul>
  </div>
</template>

<script setup lang="ts">

const { data } = await useFetch('/api/hello', {
  method: 'GET'
})
const person = {
  name: 'dsadsa',
  age: 2,
  // .....
  password: 'xdasdsdas',
  dateOfBirth: 'dasdas',
  someSecrets: "dasdasdsa"
}


const {name : fullName} = person;




</script>
