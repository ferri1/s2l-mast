<template lang="html">

  <section id="lessteps">

          <h3 id="h3">On Finance quatre types de  projets </h3>
        <ul>
          <li id="step-1">
            <img src="@/assets/images/techenologie.svg"  alt="techno"  class="img"/>
            <h4>Techenologie</h4>
            <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.
            </p>
          </li>
          <li id="step-1">
            <img src="@/assets/images/social.svg"  alt="social"  class="img"/>
            <h4>Social</h4>
            <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.
            </p>
          </li>
          <li id="step-2">
            <img src="@/assets/images/echologie.svg" alt="Echologie" class="img" />
            <h4>Echologie</h4>
            <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.
            </p>
          </li>
          <li id="step-3">
            <img src="@/assets/images/education.svg" alt="Educatif"  class="img"/>
            <h4>Educatif</h4>
            <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.
            </p>
          </li>
        </ul>

    </section>


</template>

<script>
export default {
  name: "Type"
}
</script>

<style media="screen">
#h3{
  font-family: 'Arvo' serif;
  font-size: 3em;
}
#lessteps ul{
margin: 80px 0;
}
#lessteps ul li{
width: 200px;
float: left;
padding-top : 140px;
text-align: center;
margin-right: 10px;


}
ul{
list-style: none;
}
.img{
width: 100px;
height: 150px;
}
#lessteps h4{
text-transform: uppercase;
margin-bottom: 20px;

}
#lessteps p{
margin-bottom: 20px;
}

</style>
