<template>
    
    

    <div>
        <slot></slot> 
                <p class="text-center"> {{ nombre }} </p>
                <p class="text-center"> {{ descripsion }} </p>
                <p class="text-center"> {{ precio }} </p>
                <a href="https://bilbao.edu.mx/wp-content/uploads/2021/10/comida_rapida_1.jpg" target="_blank">Comprar</a>
    </div>
    
  
</template>   

<style scoped>
   
    
    div{
    
       
        display: inline-block; 
        text-align: center;
        border: 0.5px solid #f2f2f2;
        border-radius: 50px;
        margin:  1%;
        padding: 1%;

    }
    header {
        display: flex;
        width: 10%;
        size: 100%;
        height: 10%;
        font-size: 12px;
        
    }
    
   
</style>

<script>

    export default {
        props: {
        
            nombre: {
                String,
            },
            descripsion: {
                String,
            },
            precio: {
                String,
            },
        },


    };
</script>

