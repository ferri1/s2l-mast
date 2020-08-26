<template >
  <div  role = "tablist" >
      <div >
       <b-button  v-b-toggle.collapse-1  class = "m-1" >Qu’est-ce que Ange de gain en France ? </b-button >
       <b-collapse  id = "collapse-1" >
         <b-card > Je devrais commencez ouvert! </b-card >
       </b-collapse >
     </div >

     <div >
        <b-button  v-b-toggle.collapse-2  class = "m-1" >Comment rejoindre l'Ange de gain ? </b-button >
        <b-collapse    id = "collapse-2" >
          <b-card > Je devrais commencez ouvert! </b-card >
        </b-collapse >
    </div >


     <div >
        <b-button  v-b-toggle.collapse-3  class = "m-1" >Est ce qu'on garantit le succès des projets présentés ?</b-button >
        <b-collapse  id = "collapse-3" >
          <b-card > Je devrais commencez ouvert! </b-card >
        </b-collapse >
    </div >

    <div >
        <b-button  v-b-toggle.collapse-4  class = "m-1" >c'est quoi La rénumeration des apporteurs d'affaire? </b-button >
        <b-collapse   id = "collapse-4" >
         <b-card > Je devrais commencez ouvert! </b-card >
        </b-collapse >
    </div >

    <div >
        <b-button  v-b-toggle.collapse-5  class = "m-1" >Quelle est la règlementation applicable ? </b-button >
        <b-collapse    id = "collapse-5" >
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

<style media="screen">
.m-1{
  width: 50em!important;
}
</style>
