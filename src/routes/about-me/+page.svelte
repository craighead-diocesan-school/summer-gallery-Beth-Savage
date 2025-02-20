<script>
    import Header from '$lib/Header.svelte'
    import Footer from '$lib/Footer.svelte'
    import Nav from '$lib/Nav.svelte' 
    import Card from '$lib/Card.svelte'
    import Image from '$lib/Image.svelte'
</script>
  
  <Header title="Summer Gallery" subtitle="Images from summer" />
  <Nav />
  <main>
    <h2> 
        About Me 
    </h2>
    <div class="columns is-8 is-multiline">
      <div class="column is-full">My name is Beth Savage. I am a 16 year old, year 12 student at Craighead Diocian school.I do ballet and Musical theatre at Timaru Dance Studio. I play the piano and violin, I play the violin with the South Canterbury Youth Orchestra, Craighead String group and a String Trio with my friends. I sing in the Craighead Chorale and Choir.</div>
      <div class="column is-half has-text-centered"> <Image src= "Summer-camp.jpg"  alt= "The view of the lobby day one of RAD summer camp" caption = "RAD summer camp"/></div>
      <div class="column is-half"> In the summer holidays I went to a six day summer camp for ballet in Wellington. We did 6 hours of dancing a day for 6 days straight with a mix of ballet, jazz and contemporary. I was there with my brother and one other girl from my studio. While I was there I made two new friends; Bianca and Amy-Lee. We were in the Intermediate/Advanced Foundation class together. At the end of the week we did a showcase for the parents. </div>
      <div class="column is-half">On Christmas we spent the day with family. We had lunch at our Grandparents house. It was our Dogs first Christmas and we gave her a new toy wrapped in plain brown paper. Like many children she had more fun with the wrapping than the present. We took her with us when we went to have lunch and she was very unhappy about being left out. I got a ukulele so I spent most of the afternoon playing it for her.</div>
      <div class="column is-half has-text-centered"> <Image src= "Clara-Christmas.jpg"  alt= "Our Dog Clara playing with the wrapping paper on Christmas day"/></div>
    </div>
   
    
  </main>
  <Card />
  <Footer />

  <style>
    .is-full{
      margin: 2%;
    }
    main{
      margin: 0.5%;
    }
  </style>