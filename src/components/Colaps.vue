< template >
  <div  role = "tablist" >
    <b-card  no-body  class = "mb-1" >
      <b-card-header  header-tag = "header"  class = "p-1"  role = "onglet " >
        <bloc b-button  v-b-toggle.accordion-1 variant = " info " >   Accordéon 1 </b-button >
      </b-card-header >
      <b-collapse  id = "accordéon-1" visible  accordion = "my-  accordéion " role = "tabpanel" >
        <b-card-body >
          <b-card-text > Je commence à ouvrir car <code > visible </code > est <code > true </code > </b-card-text >
          <b-card-text > {{text}} </b-card-text >
        </b-card-body >
      </b-collapse >
    </b-card>

    <b-card  no-body  class = "mb-1" >
      <b-card-header  header-tag = "header"  class = "p-1"  role = "tab" >
        <b-button  block  vb-toggle. accordion-2  variant = "info" > Accordion 2 </b-button >
      </b-card-header >
      <b-collapse  id = "accordion-2"  accordion = "my-accordéion" role = "tabpanel" >
        <b-card-body >
          <b-card-text > {{text}} </b-card-text >
        </b-card-body >
      </b-collapse >
    </b-card >

    <b-card  no-body  class = "mb-1" >
      <b-card-header  header-tag = "header"  class = "p-1"  role = "tab" >
        <b-button  block  vb-toggle. accordion-3  variant = "info" > Accordion 3 </b-button >
      </b-card-header>
      <b-collapse  id = "accordion-3"  accordion = "my-accordéion" role = "tabpanel" >
        <b-card-body >
          <b-card-text > {{text}} </b-card-text >
        </b-card-body >
      </b-collapse >
    </b-card >
  </div >
</template >

<script >
export default {
  name: "Colaps",

    les donnees() {
      return {
         text : `
          Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry
          richardson ad squid. 3 Wolf Moon Officia Aute, non Cupidatat Skateboard Dolor
          brunch. Camion alimentaire quinoa nesciunt laborum eiusmod. Brunch 3 Lune de loup
          tempor, sunt aliqua mettre un oiseau dessus calmar café d'origine unique nulla
          assumenda shoreditch et. Nihil Anim Keffiyeh Helvetica, bière artisanale labore
          wes anderson cred nesciunt sapiente ea proident. Pub vegan saufeur boucher
          vice lomo. Legging Occaecat Craft Beer Farm-to-Table, esthétique denim brut
          synth nesciunt vous n'avez probablement pas entendu parler d'eux accusamus labore VHS.

      },
    };

};
</script >
