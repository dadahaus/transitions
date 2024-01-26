<script>
</script>


  <h1>I make artsy stuff with emphasis on animation</h1>
  <section>
    <article>
      <h2>Nice features</h2>
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Rem, ipsum
        omnis earum quod accusantium rerum, aspernatur error beatae dolores ab,
        molestias quia fuga? Maiores animi natus itaque! Perferendis, suscipit
        odit?
      </p>
    </article>
  </section>

  <section>
    <ul>
      <li>
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Veritatis ab
        recusandae inventore odit aspernatur. Pariatur repellat odit rerum!
        Molestiae ipsa eius officiis! Quo, sint libero sapiente repudiandae
        aliquid at reiciendis?
      </li>
      <li>
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Veritatis ab
        recusandae inventore odit aspernatur. Pariatur repellat odit rerum!
        Molestiae ipsa eius officiis! Quo, sint libero sapiente repudiandae
        aliquid at reiciendis?
      </li>
    </ul>
  </section>


  <section>
    <div>
      <p>
        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Earum, quos ab
        libero reprehenderit velit eum nam inventore tenetur? Accusantium esse a
        dolorum ducimus deserunt nihil doloribus consectetur, sint reiciendis
        debitis.
      </p>
    </div>
  </section>
 
<section>

  <div>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Deleniti
      exercitationem sit dolores aliquid in ea. Sed in aliquam, quibusdam quas
      dolorum est amet sit iure, quisquam, ducimus quaerat assumenda
      repudiandae. Lorem ipsum dolor sit amet consectetur adipisicing elit.
      Nulla et a suscipit voluptate, omnis esse vitae eos ex repellat ad
      reprehenderit ut, vel, facilis quod consequuntur. Nemo accusamus suscipit
      vitae?
    </p>
  </div>
</section>
  
<section>
  <div>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla et a
      suscipit voluptate, omnis esse vitae eos ex repellat ad reprehenderit ut,
      vel, facilis quod consequuntur. Nemo accusamus suscipit vitae?
    </p>
  </div>
  <div>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla et a
      suscipit voluptate, omnis esse vitae eos ex repellat ad reprehenderit ut,
      vel, facilis quod consequuntur. Nemo accusamus suscipit vitae?
    </p>
  </div>
</section>
  

  <figure>
    <img src="src/assets/1.png" alt="pic" />
    <figcaption>Some artsy stuff</figcaption>
  </figure>


<style lang="scss">
  :root {
    font-family: Inter, system-ui, Avenir, Helvetica, Arial, sans-serif;
    line-height: 1.5;
    font-weight: 400;
    font-size: clamp(1.125rem, 2vw, 4.5rem);

    color-scheme: light dark;
    color: hsla(165, 60%, 17%, 0.87);
    background-color: hsl(158, 89%, 89%);

    font-synthesis: none;
    text-rendering: optimizeLegibility;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    -webkit-text-size-adjust: 100%;
  
  }

  h1 {
    margin: 2rem 0rem;
    color: hsl(180, 79%, 15%);
    max-width: 15ch;
    text-align: center;
  }

// this is where the typography details are
  p, ul{
    max-width: 25ch;
  }

  section, figure {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    width: 100vw;
    article {
      max-width: 50ch;
    }
  }

  p,
  li {
    animation: fade linear both;
    animation-timeline: view();
  }
  @keyframes fade {
    from {
    }
    to {
    }
    0% {
      opacity: 0;
    }
    60% {
      opacity: 1;
    }
    80% {
      opacity: 0;
    }
    100% {
      opacity: 0;
    }
  }
</style>
