<template>
        <div class="center">
        <bold>
        <p>WELCOME TO POST IT<br></p>
        </bold>
        <p id="Sign Up">Create an account<br></p>
        <bold2>
        <p>or<br>Sign up here:</p>
        </bold2>
    <form action="index.html">
        <input type="email" name="email" placeholder="Email" required>

        <input type="password" name="password" placeholder="Password" required>

        <a href="index.html">
            <button type="submit">Sign Up</button><br>
        </a>

    </form>

        <p>Forgot password<br></p>

    </div>
<template>

<script>
// @ is an alias to /src
import WebFooter from '@/components/footer.vue'
import WebHeader from '@/components/header.vue'

export default {
  name: 'SignUpView',
  components: {
    WebFooter,
    WebHeader
  }
}
</script>