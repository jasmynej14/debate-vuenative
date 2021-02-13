

<template>
  <view class="container">
    <text class="text-color-primary">Debate app!</text>
    <text> {{ subtitle }} </text>
    
    <button id="btn" title="press" @press ="exclaim" />
    <text> Count: {{ count }}</text>
    <Feed />
  </view>
</template>
<script>
    import Feed from './components/Feed'
    export default{
      components: { Feed },
      data() {
        return {
          subtitle: "This is working out much better",
          count: 0
        };
      },
      methods:{
        exclaim(){
         this.count+=1;
        }
      }
    }
</script>
<style>
.container {
  background-color: rgb(106, 88, 122);
  align-items: center;
  justify-content: center;
  flex: 1;
}
.text-color-primary {
  color: rgb(255, 255, 255);
}

#btn{
  background-color: lavender;
}
</style>
