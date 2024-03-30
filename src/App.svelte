<script>
 
  import  Router  from 'svelte-spa-router'
  import Header from "./components/Header.svelte";
  import Home from "./components/Home.svelte";
  import Footer from "./components/Footer.svelte";
  import Nouveautees from './components/Nouveautees.svelte';
  import APropos from "./components/APropos.svelte";
  import MeContacter from "./components/MeContacter.svelte";
  import MaSelection from "./components/MaSelection.svelte";
  import TousLesProduits from "./components/TousLesProduits.svelte";
 
 
  
  let routes = {
    // define your routes here
    
    '/': Home,
    '/Nouveautees': Nouveautees,
    '/APropos': APropos,
    '/MeContacter': MeContacter,
    '/MaSelection': MaSelection,
    '/TousLesProduits': TousLesProduits,
    // '/other': OtherComponent,
  };
</script>




<Header />


  <main>
    <Router {routes}/>
  </main>


<Footer />
