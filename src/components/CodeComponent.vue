<template>
  <pre>
<code class="language-javascript line-numbers">
function Person(name, age){
    this.name = name || 'pelli';
	this.age = age || 18;
}

Person.prototype.sayHi = function(){
	console.log('Hi, I am ' + this.name + ', I am ' + this.age + ' years old');
};
			</code>
		</pre>
</template>

<script setup>
import { reactive } from "vue";
const msg = reactive({
  age: 185
});
</script>

<style>
</style>