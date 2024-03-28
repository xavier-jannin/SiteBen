<script>
  import Header from "./components/Header.svelte";
  import Home from "./components/Home.svelte";
  import Footer from "./components/Footer.svelte";
  let routes = {
    // define your routes here
    "/": Header,
    "/home": Home,
    "/footer": Footer,
    // '/other': OtherComponent,
  };
</script>




<Header />

<body>
  <main>
    <Home />
  </main>
</body>

<Footer />
