<script setup>
import TopicItem from '../components/TopicItem.vue';
</script>

<template>
<main>
    <div class="homeContent">
        <div class="summary">
            <h1>Titre</h1>
            <p>nuvronvrejvreo</p>
            <p>nuvronvrejvreo</p>
            <p>nuvronvrejvreo</p>
            <p>nuvronvrejvreo</p>
            <p>nuvronvrejvreo</p>
            <p>nuvronvrejvreo</p>
        </div>

        <div class="hotTopic">
            <h1>Découvrez</h1>
            <div id="topics">
                <TopicItem></TopicItem>
            </div>
        </div>
    </div>
</main>
</template>

<style>
body{
    background-color: #A8F7A6;
}

.homeContent{
    display: flex;
    flex-direction: column;
    margin-top: 10%;
    align-items: center;
}

.summary{
    background-color: #E3FED6;
    width: 75%;
    border-radius: 30px;
}
</style>