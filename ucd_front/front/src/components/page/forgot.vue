<template>
<div class=" flex items-center justify-center bg-gray-50 py-12 px-4 sm:px-6 lg:px-8">
  <div class="max-w-md w-full space-y-8">

  <form lass="mt-8 space-y-6" @submit.prevent="click"> 
      
       <h2 class="mt-6 text-center text-3xl font-extrabold text-gray-900">
        Mot de passe oublié
      </h2>
      <div class="mt-8 space-y-6">
          <label>Saisir votre Email :</label>
          <input type="email" v-model="email" class="appearance-none rounded-none relative block w-full px-3 py-2 border border-gray-300 placeholder-gray-500 text-gray-900 rounded-t-md focus:outline-none focus:ring-indigo-500 focus:border-indigo-500 focus:z-10 sm:text-sm" placeholder="Email address"/>
      </div>
      <br>
      <div>
        <button type="submit" class="group relative w-full flex justify-center py-2 px-4 border border-transparent text-sm font-medium rounded-md text-white bg-indigo-600 hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500">
          <span class="absolute left-0 inset-y-0 flex items-center pl-3">
            <!-- Heroicon name: lock-closed -->
            <svg class="h-5 w-5 text-indigo-500 group-hover:text-indigo-400" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
              <path fill-rule="evenodd" d="M5 9V7a5 5 0 0110 0v2a2 2 0 012 2v5a2 2 0 01-2 2H5a2 2 0 01-2-2v-5a2 2 0 012-2zm8-2v2H7V7a3 3 0 016 0z" clip-rule="evenodd" />
            </svg>
          </span>
          Sign in
        </button>
      </div>
  </form>
  </div>
</div>
</template>
  
<script>
// import axios from 'axios'
export default {
name:'forgot',
// data(){
//  return {
//    email:''
//  }

// },
// methods: {
//   async click(){
//     const response = await axios.post('forget',{
//       email : this.email
//     });
//      console.log(response); 
//   }

// }
}
</script>
