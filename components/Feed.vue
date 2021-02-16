<template>
    <scroll-view class="view-container">
            
      <FeedItem />
      <button title="see more"/>
      <FeedItem />
      <button title="see more"/>
      <FeedItem />
      <button title="see more"/>
    </scroll-view>
</template>

<script>

import FeedItem from './FeedItem'
export default {
    components: {FeedItem},
    data(){
        return {

        };
    }
}
</script>

<style>
    .view-container{
        background-color:white;
        padding-top: 100px;
        width:75%;
    }

    
</style>