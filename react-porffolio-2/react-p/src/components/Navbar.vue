<template>
    <nav class="custom-nav">
        <ul>
            <li class="name">Burness Scott III</li>
            <li><router-link class="hov" to="/">Home</router-link></li>
            <li><router-link class="hov" to="/about">About</router-link></li>
            <li><router-link class="hov" to="/contact">Contact</router-link></li>
            <li><router-link class="hov" to="/portfolio">Portfolio</router-link></li>
            <li><router-link class="hov" to="/resume">Resume</router-link></li>
        </ul>
    </nav>
</template>
  
<style scoped>
.name {
    margin-left: 300px;
    font-weight: bold;
    margin-right: 20px;
}

.hov:hover {
    background-color: rgb(159, 148, 148);
    border-radius: 20%;


}

.custom-nav {
    background-color: gray;
    padding: 10px;
    height: 40px;
}

ul {
    list-style: none;
    display: flex;
    justify-content: right;
    align-items: center;
    margin: 0;
    padding: 0;
}

li {
    margin: 0 15px;
}

router-link {
    color: #fff;
    text-decoration: none;
    transition: color 0.3s, background-color 0.3s;
    cursor: pointer;
}
</style>
  