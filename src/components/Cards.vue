<template>
    <article class="col-md-6 col-lg-4 col-sm-12" v-for="item in AboutArray" :key="item.id">
        
        <div class="card-content">
            <div id="icon-border">
                <img id="card-icons" class="card-image" :src="item.icon" alt="mmm">
                </div>
            <h4 class="spectrum-h2 text-black text-center">{{ item.title }}</h4>
            <p> {{ item.text }} </p>
        </div>
    </article>
</template>

<script>
export default {
    data() {
        return {
            AboutArray: [
                {
                "id": 1,
                "icon": "https://i.postimg.cc/xjyvnLdR/portfoliotask.png",
                "title": "Portfolio",
                "text": ""
            },
            {
                "id": 2,
                "icon": "https://i.postimg.cc/nzxXPwqt/calculator.png",
                "title": "Calculator",
                "text": ""
            },
            {
                "id": 3,
                "icon": "https://i.postimg.cc/43g4fHy6/Bmi.png",
                "title": "BMI Calculator",
                "text": ""
            },
            {
                "id": 4,
                "icon": "https://i.postimg.cc/TwNt9mWg/properties-task.png",
                "title": "  Properties Market",
                "text": ""
            },
            {
                "id": 5,
                "icon": "https://i.postimg.cc/SRWDpPv7/to-do-list.png",
                "title": "To-do list",
                "text": ""
            },
            {
                "id": 6,
                "icon": "https://i.postimg.cc/mD6GHPL6/blogs.png",
                "title": "Food Blog",
                "text": ""
            },  {
                "id": 7,
                "icon": "https://i.postimg.cc/7h0wrx4s/tempcal.png",
                "title": "Temperature Clcualtor",
                "text": ""
            },
            {
                "id": 8,
                "icon": "https://i.postimg.cc/yNGHJJYp/simple-compoundcal.png",
                "title": "Simple&Compound Interest Calculator",
                "text": ""
            },
            {
                "id": 9,
                "icon": "https://i.postimg.cc/8C78V1BR/areaoftrianglecal.png",
                "title": "Area of triangle Calculator",
                "text": ""
            }]
        };
    }
}
</script>

<style scoped>
.card-content {
    background: #f5f5f5;
    height: 400px;
    width:;
    padding: 10px;
    margin-top: 1em;
    margin-bottom: 1em;
    box-shadow: 3px 3px 8px white;
    border-radius: 10px;
    background: linear-gradient(145deg, #825b85, #FFFFFF);
    box-shadow: 10px 10px 10px #dcabdf,
        -10px -10px 10px white;
}

card-content h3 {
    margin-bottom: 0.5em;
    font-weight: normal;
    text-align: center;
}

card-content p {
    font-size: 95%;
    padding: 1rem;
}

/* #icon-border {
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: 100%;
    aspect-ratio: 1;
    padding: 2rem;
     border: 5px solid black; 
    border-radius: 100px;
    margin-bottom: 10px;
    opacity: 0.8;
    transition: all 0.5s ease;
} */
.card-content:hover{
text-decoration: none;
    background-color: #dcabdf;
    border: #feffff;
     opacity: 1.5;
    filter: contrast(100%);
}
/* #icon-border:hover {
    text-decoration: none;
    background-color: #dcabdf;
    border: #feffff;
}

#icon-border:hover {
    opacity: 1.5;
    filter: contrast(100%);
} */

</style>







