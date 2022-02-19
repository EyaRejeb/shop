<template>
  <div>
    <div class="flex">
            <div>
                <img src = "{{productImage}}" />
            </div>
            <div>
                <h1>{{productName}}</h1>
                <h1>product Size: {{productSize}}</h1>
                <h1>Color: {{productColor}}</h1>
                <h1>{{productPrice}}</h1>
                <h1>{{productDescription}}</h1>
    
                
            </div>
     </div>>
   
  </div>
</template>

<script>
export default {
  props: {
    productName: String,
    productPrice: String,
    productImage: String,
    productColor: String,
    productSize: String,
    productDescription: String
  }
};
</script>
