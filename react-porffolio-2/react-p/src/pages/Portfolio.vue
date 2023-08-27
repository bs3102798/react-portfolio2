<template>
    <div class="portfolio-page">
        <h1>Portfolio Page</h1>
        <div class="project-list">
            <div class="project">
                <h2>Note-taker-express</h2>
                <p>Description of Project 1</p>
                <p>Use of express</p>
                <a href="https://github.com/bs3102798/note-taker-express" target="_blank">View Project</a>
            </div>
            <div class="project">
                <h2>Tech-blog</h2>
                <p>Description of Project 2</p>
                <p>Use ofbcryptjs,connect-session-sequelize,dotenv,express,express-handlebars,
                    express-session,handlebars,mysql2,sequelize </p>
                <a href="https://github.com/bs3102798/Tech-blog" target="_blank">View Project</a>
            </div>

            <div class="project">
                <h2>Gababara</h2>
                <p>Description of Project 3</p>
                <p>Use of Materialize CSS,JSON,Sequelize,Handlebars
                </p>
                <a href="https://github.com/guapjorge/gababara" target="_blank">View Project</a>
            </div>

            <div class="project">
                <h2>SQL-Employee-Tracker</h2>
                <p>Description of Project 4</p>
                <p>Use of cfonts,chalk,console.table,inquirer,mysql2</p>
                <a href="https://github.com/bs3102798/SQL-Employee-Tracker" target="_blank">View Project</a>
            </div>

            <div class="project">
                <h2>E-commerce-back-end</h2>
                <p>Description of Project 5</p>
                <p>Use of express,mysql2,sequelize</p>
                <a href="https://github.com/bs3102798/E-commerce-back-end" target="_blank">View Project</a>
            </div>

        </div>
    </div>
</template>
  
<script setup>
</script>
  
<style scoped>
.portfolio-page {
    padding: 20px;
    background-color: #fff;

}

.project-list {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
}

.project {
    padding: 20px;
    background-color: #f0f0f0;
    border-radius: 5px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    text-align: center;
}

.project img {
    max-width: 100%;
    height: auto;
    border-radius: 5px;
    margin-bottom: 10px;
}

.project h2 {
    font-size: 1.5rem;
    margin-bottom: 10px;
}

.project p {
    margin-bottom: 10px;
}

.project a {
    display: inline-block;
    padding: 8px 20px;
    background-color: #007bff;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
}

div a:hover {
    background-color: #92bdea;
}
</style>
  