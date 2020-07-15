<template>
  <div>
    <h1>Hello there</h1>
    <form>
      <h2>1.</h2>
      <label>How do you feel today</label>
      <div class="rating">
        <span><input type="radio" name="rating" id="str5" value="5"><label for="str5"></label></span>
        <span><input type="radio" name="rating" id="str4" value="4"><label for="str4"></label></span>
        <span><input type="radio" name="rating" id="str3" value="3"><label for="str3"></label></span>
        <span><input type="radio" name="rating" id="str2" value="2"><label for="str2"></label></span>
        <span><input type="radio" name="rating" id="str1" value="1"><label for="str1"></label></span>
      </div>
      <h2>3.</h2>
      <label>Your Password</label>
      <div>
        <input type="password"/>
      </div>
      <h2>4.</h2>
      <label>Your Email Address</label>
      <div>
        <input type="email"/>
      </div>
    </form>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

@Component
export default class CustomerForm extends Vue {

}
</script>
