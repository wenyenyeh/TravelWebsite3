<script setup>
// import axios from 'axios';
// import { ref } from 'vue';

// // 定义一个响应状态的变量以处理请求响应
// const responseStatus = ref(null);

// // 发送POST请求的函数
// const sendLogoutRequest = async () => {
//   try {
//     const response = await axios.post('http://localhost:8080/auth/logout', null, {
//       withCredentials: true,
//     });
//     responseStatus.value = response.data;
//     console.log(response.data); 
//     alert(response.data);
//     window.location.replace("/");
//     window.location.reload();

//   } catch (error) {
//     console.error('Error during the POST request:', error);
//     responseStatus.value = 'Request failed';
//   }
// };

</script>

<template>
  <div>
    <div>
    <!-- <button @click="sendLogoutRequest" class="fa-solid fa-skull"> -->
        <a href="../../memberinfo">
            <i class="fa-regular fa-poo icon-large" @click="sendLogoutRequest" style="vertical-align: bottom;"></i>
        </a>
        
    <!-- </button> -->
  </div>
    
  </div>
</template>

<style scoped >
.icon-large {
    font-size: 21px;
    padding: 5.5px; /* 设置你想要的padding值 */
}

</style>