<template>
    <div class="header">
        <div class="left">
            <Menu />
        </div>
        <div class="right">
            <Account />
        </div>
    </div>
</template>
  
<script setup>
import Account from 'vue-material-design-icons/Account.vue';
import Menu from 'vue-material-design-icons/Menu.vue';
</script>
  
<style scoped>
.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.left,
.right {
    padding: 10px 10px;
}
</style>
  