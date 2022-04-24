<template>
    <ul>
        <li v-for="vehicle in vehicles">
          <h1> {{vehicle.name}} </h1> <br/>
           <h6> {{vehicle.age}}</h6>
        </li>

    </ul>
</template>

<script>
export default {
   name: "SundayList",
   data(){
       return ({
         vehicles :  [
            {name: 'James', age: 42},
             {name: 'John', age: 55},
              {name: 'Kerry', age: 22},
               {name: 'Khanh', age: 4}
           ]
       })
   }
}
</script>

<style scoped>
 p {
       font-size: 3.0rem;
       font-weight: 500;
 }
</style>
