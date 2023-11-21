<script>
export default {
    data() {
        return {
            
        }
    },
    props: {
        
    },
    components: {
        
    },
    watch: {
        
    },
    mount: {
        
    },
    methods: {
        
    }
}
</script>

<template>
    <div class="pacman">
      <div class="pacman-eye"></div>
      <div class="pacman-mouth"></div>
    </div>
</template>

<style scoped>
    .pacman{
      width: 100px;
      height: 100px;
      border-radius: 50%;
      background-color: yellow;
      position: absolute;
    }

    .pacman-eye{
      
    }

    .pacman-eye{
      position: relative;
      width: 8px;
      height: 8px;
      border-radius: 50%;
      background-color: #f1f1f1;
      right: 20px;
      top: 20px;
    }
</style>