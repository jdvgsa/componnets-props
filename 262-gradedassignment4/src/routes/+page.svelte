<script>
// import CardComponent from "../lib/components/Card.svelte"; 
import Card from "../lib/components/Card.svelte";
import {cardData} from "../lib/data.js"
let visible = true;
</script>

<header>
   <nav>
    <ul>
      <li> <a href="/">Home</a></li>
      <li> <a href="/about">About</a></li>
      <li> <a href="/contact">Contact</a></li>
    </ul>
  </nav>
  </header> 

<h1 class="text-5xl font-bold underline">Components and Props Assignment Test223</h1>

<!-- <CardComponent {...CardComponent} /> -->
<Card {...cardData}/>


<footer><p>&copy; 2023 John Dagsa Svelte Assignment</p></footer>

