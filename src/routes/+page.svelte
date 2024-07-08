<script>
	import Percent from './../lib/icons/Percent.svelte';
	import Equals from './../lib/icons/Equals.svelte';
	import DividedBy from './../lib/icons/DividedBy.svelte';
	import MultipliedBy from './../lib/icons/MultipliedBy.svelte';
	import Minus from './../lib/icons/Minus.svelte';
	import SquareRoot from "$lib/icons/SquareRoot.svelte";
  import Plus from "$lib/icons/Plus.svelte";
  import Point from "$lib/icons/Point.svelte";
</script>
 <svelte:head>
  <title>
آلة حاسبه
  </title>
 </svelte:head>
 <div class="bg-white h-fit w-fit rounded-3xl grid grid-cols-4 gap-2 p-4 text-lg font-semibold  text-gray-600 shadow-xl ">

  <div class="bg-blue-500 rounded-full col-span-4 h-14 flex items-center text-white text-lg font-semibold px-5 mb-2">
    
    123456
  
  </div>
  <button class="bg-slate-100 "> <Percent/> </button>
  <button class="bg-slate-100 "> <SquareRoot/> </button>
  <button class="bg-slate-100">CE</button>
  <button class="bg-gray-800 text-white">C</button>
  <button>7</button>
  <button>8</button>
  <button>9</button>
  <button class="bg-red-400 text-white " > <Minus/> </button>
  <button>4</button>
  <button>5</button>
  <button>6</button>
  <button class="bg-blue-400 text-white">  <DividedBy/> </button>
  <button>1</button>
  <button>2</button>
  <button>3</button>
  <button class="bg-yellow-400 text-white">  <MultipliedBy/> </button>
  <button>   <Point/>  </button>
  <button>0</button>
  <button>  <Equals/>  </button>
  <button class="bg-green-400 text-white"> <Plus/> </button>

 </div>