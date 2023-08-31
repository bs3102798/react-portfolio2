<template>
    <div class="contact-page">
        <h1>Contact Page</h1>
        <form @submit.prevent="submitForm">
            <div class="form-group">
                <label for="name">Name</label>
                <input v-model="name" type="text" id="name" name="name" required />
            </div>
            <div class="form-group">
                <label for="email">Email</label>
                <input v-model="email" type="email" id="email" name="email" required />
            </div>
            <div class="form-group">
                <label for="message">Message</label>
                <textarea v-model="message" id="message" name="message" rows="4" required></textarea>
            </div>
            <button type="submit">Submit</button>
        </form>
    </div>
</template>
  
<script setup>
import { ref } from 'vue';

const name = ref('');
const email = ref('');
const message = ref('');

</script>
  
<style scoped>
.contact-page {
    padding: 20px;
    background-color: #fff;
    border-radius: 5px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.form-group {
    margin-bottom: 20px;
}

label {
    display: block;
    font-weight: bold;
    margin-bottom: 5px;
}

input,
textarea {
    width: 100%;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

button {
    padding: 10px 20px;
    background-color: #007bff;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #84a8ce;

}
</style>
  