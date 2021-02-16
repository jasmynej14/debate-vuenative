<template>
    <view class="post">
        <text id="title">{{ postTitle }}</text>
        <text>{{ postAuthor }}</text>
        <image :source="require('/Users/jasmynejeanremy/Desktop/Debate-Front/debate-native/assets/createherstock-2019-Agency-Neosha-Gardner-15-640x427.jpg')" />
    </view>
</template>

<script>
export default {
    data: function(){
        return{
            postTitle: "Debate Title",
            postAuthor: "Debate Author",
            thumbnail: "https://createherstock.com/wp-content/uploads/2019/08/createherstock-2019-Agency-Neosha-Gardner-15-640x427.jpg",
            tags: ["healthcare","democrat","election"]

        }
    }
}
</script>

<style>
    .post{
        background-color:palegoldenrod;
    }
</style>