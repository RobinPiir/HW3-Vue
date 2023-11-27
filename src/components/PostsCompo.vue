<template>
    <div class="contentfield">
        <div class="container" v-for = "post in postList" :key="post.id">
            <header class="box-header">
                <img class="profile" src="post.authorAvatar" width="50" height="50" alt="Post author">
                <p class="post-author">{{ post.author }}</p>
                <time class="post-date">{{ post.createTime }}</time>'
            </header>
        </div>
    </div>
</template>

<script>
export default {
    name: "PostsCompo",
    props: ["postList"],
    data: function() {
return {

}},
computed: {
}
}
</script>

<style scoped>
.contentfield{
        display:flex;
        width:60%;
        height: auto;
        background-color: #B1CDA4;
        border: 1px solid black;
        height: auto;
        margin-top: 15px;
        margin-left: auto;
        margin-right: auto;
        display:flex;
        align-items: center;
        flex-direction: column;
        margin-bottom: 7em;
    }

.container{
    background-color: white;
    margin-top:7%;
    width: inherit;
    min-width: 300px;
    border:1px solid gray;
    box-shadow: 5px 5px 20px #888888;
    border-radius: 5px;
}

.profile{
    border: 1px solid gray;
    margin-left: 10px;
    margin-top: 10px;
}

.post-author{
    display: inline-block;
    vertical-align: middle;
    margin-left: 10px;
    margin-bottom: 50px;
}

.post-date{
    vertical-align: middle;
    margin-top: 20px;
    float: right;
}
</style>