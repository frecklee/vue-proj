<template>
  <div class="Ex">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.2/css/bootstrap.min.css">
    <p>주로 자주 들어가는 링크입니다.</p>
    <ul>
      <li><a href="https://vuejs.org/">vue.js 공식 홈페이지</a></li>
      <li><a href="https://kr.vuejs.org/">vue.js 한국어 홈페이지</a></li>
      <li><a href="https://gitter.im/vuejs/vue?utm_source=share-link&amp;utm_medium=link&amp;utm_campaign=share-link">vue.js 공식 채팅</a></li>
      <li><a href="https://vuejs-korea.signup.team/">vue.js 한국어 사용자 채팅</a></li>
      <li><a href="https://github.com/vuejs">vue.js 공식 조직</a></li>
      <li><a href="https://github.com/vuejs-kr">vue.js 한국어 조직</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue">awesome vue</a></li>
      <li><a href="http://forum.vuejs.org/">vue.js 포럼</a></li>
    </ul>
    <p>{{ greeting }} World!</p>
    <p>{{ greeting2 }} World!</p>
    <button style="text-align:center" type="submit" class="btn btn-success">제출</button>
  </div>
</template>

<style>
  @import url('https://fonts.googleapis.com/css?family=Arimo|Noto+Sans+KR');
  
  .Ex {
    font-family: 'Noto Sans KR', sans-serif;
    align-content: center;
    text-align: center;
  }
  input, button {
    border-radius: 30% !important;
  }
</style>
<script>
  module.exports = {
    data: function() {
      return {
        greeting: 'Hello',
        greeting2: 'bye'
      }
    },
  }
</script>