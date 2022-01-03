<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h4>Thank you for your interest in our project.</h4>
    <h4>We are designing the next generation backpack for every day carry.</h4>
    <h4>
      Our website is currently under construction, but we will be back as soon as possible.
    </h4>
    <div class="push"></div>
  </div>

  <footer>
    &copy; Copyright {{ copyrightDate }}. <a href="http://castle-vast.com">Castle Vast Limited</a>, Hong Kong SAR.
  </footer>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
  data() {
		return {
			copyrightDate: new Date().getFullYear(),
		};
	},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h4 {
  margin: 20px 0 20px;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #4276b9;
  text-decoration: none
}
p {
  width: 40%;
  margin-left: auto;
  margin-right: auto;
}
footer {
  margin-top: 10%;
}
</style>
