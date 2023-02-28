<template>    
<div>
    <div id="head"></div>
    <div id="torso"></div>
    <div id="butt"></div>
</div>
</template>


<script>
export default 
{
   name:"JurajH",
   props:
   {
      sprava: String
   }

}
</script>

<style>

#head {
  border-width: 3.571px;
  border-color: rgb(0, 0, 0);
  border-style: solid;
  border-radius: 50%;
  background-color: rgb(255, 255, 255);
  position: absolute;
  left: 81px;
  top: 67px;
  width: 74.858px;
  height: 76.858px;
  z-index: 3;
}

#torso {
  border-width: 3.571px;
  border-color: rgb(0, 0, 0);
  border-style: solid;
  border-radius: 50%;
  background-color: rgb(255, 255, 255);
  position: absolute;
  left: 63px;
  top: 142px;
  width: 113.858px;
  height: 106.858px;
  z-index: 2;
}

#butt {
  border-width: 3.571px;
  border-color: rgb(0, 0, 0);
  border-style: solid;
  border-radius: 50%;
  background-color: rgb(255, 255, 255);
  position: absolute;
  left: 44px;
  top: 223px;
  width: 155.858px;
  height: 140.858px;
  z-index: 1;
}

</style>