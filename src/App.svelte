<script>
 
  import  Router  from 'svelte-spa-router'
  import Header from "./components/Header.svelte";
  import Home from "./components/Home.svelte";
  import Footer from "./components/Footer.svelte";
  import Nouveautees from './components/Nouveautees.svelte';
 
 
  
  let routes = {
    // define your routes here
    
    '/': Home,
    '/Nouveautees': Nouveautees,
    // '/other': OtherComponent,
  };
</script>




<Header />

<body>
  <main>
    <Router {routes}/>
  </main>
</body>

<Footer />
