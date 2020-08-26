<template >
  <div  role = "tablist" >
    <div >
   <b-button  v-b-toggle.collapse-3  class = "m-1" > Pour quoi nous?  </b-button >
   <b-collapse  visible  id = "collapse-3" >
     <b-card > Je devrais commencez ouvert! </b-card >
   </b-collapse >
 </div >
 <div >
<b-button  v-b-toggle.collapse-3  class = "m-1" > quels sont les avantages? </b-button >
<b-collapse  visible  id = "collapse-3" >
  <b-card > Je devrais commencez ouvert! </b-card >
</b-collapse >
</div >
<div >
<b-button  v-b-toggle.collapse-3  class = "m-1" > Toggle Collapse </b-button >
<b-collapse  visible  id = "collapse-3" >
 <b-card > Je devrais commencez ouvert! </b-card >
</b-collapse >
</div >
<div >
<b-button  v-b-toggle.collapse-3  class = "m-1" > Toggle Collapse </b-button >
<b-collapse  visible  id = "collapse-3" >
 <b-card > Je devrais commencez ouvert! </b-card >
</b-collapse >
</div >
  </div >
</template >

<script >
export default {
  name: "Colaps",



};
</script >
