<script> 
import Card from "../lib/components/Card.svelte";
import {cardData} from "../lib/data.js"
import {cardArray} from "../lib/data.js"
// renders card
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

<h1 class="text-5xl font-bold underline">Components and Props Assignment Test322</h1>

<div>
<Card {...cardData}/>
</div>

<h1>Looping cardArray</h1>
<span>

{#each cardArray as card}
<Card {...card}/>
{/each}

</span>

<footer><p>&copy; 2023 John Dagsa Svelte Assignment</p></footer>

