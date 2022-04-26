<script>
  import Observable from './components/Observable.svelte'
</script>

<main>


  <Observable mode="btm" inOut>
      <h1>Hello world!</h1>
      </Observable>
     <Observable mode="btm" inOut>
        <p>animated: Start editing to see some magic happen :)</p>
      </Observable>
      <Observable mode="btm" inOut>
        <p>animated: Start editing to see some magic happen :)</p>
      </Observable>
      <Observable mode="btm" inOut>
        <p>animated: Start editing to see some magic happen :)</p>
      </Observable>
      <Observable mode="btm" inOut>
        <p>animated: Start editing to see some magic happen :)</p>
      </Observable>
      <Observable mode="btm" inOut>
        <p>animated: Start editing to see some magic happen :)</p>
      </Observable>
      <Observable mode="btm" inOut>
        <p>animated: Start editing to see some magic happen :)</p>
      </Observable>
      <Observable mode="btm" inOut>
        <p>animated: Start editing to see some magic happen :)</p>
      </Observable>
      <Observable mode="btm" inOut>
        <p>animated: Start editing to see some magic happen :)</p>
      </Observable>
      <Observable mode="btm" inOut>
        <p>animated: Start editing to see some magic happen :)</p>
      </Observable>
      <Observable mode="btm" inOut>
        <p>animated: Start editing to see some magic happen :)</p>
      </Observable>
      <Observable mode="btm" inOut>
        <p>animated: Start editing to see some magic happen :)</p>
      </Observable>
      <Observable mode="btm" inOut>
        <p>animated: Start editing to see some magic happen :)</p>
      </Observable>
      <Observable mode="btm" inOut>
        <p>animated: Start editing to see some magic happen :)</p>
      </Observable>
      <Observable mode="btm" inOut>
        <p>animated: Start editing to see some magic happen :)</p>
      </Observable>
      <Observable mode="custom" inOut>
        <p class="custom-animation">
          animated: Start editing to see some magic happen :)
        </p>
      </Observable>
      <p>Start editing to see some magic happen :)</p>
      <p>Start editing to see some magic happen :)</p>
      <Observable mode="custom" inOut treshold={0.05}>
        <p>custom: Start editing to see some magic happen :)</p>
      </Observable>
      <p>Start editing to see some magic happen :)</p>
      <Observable mode="left" inOut treshold={0.05}>
        <p style={{ height: '150vh', boxShadow: '0 0 0 1px red' }}>
          animated: Start editing to see some magic happen :)
        </p>
      </Observable>
      <p>Start editing to see some magic happen :)</p>
      <Observable mode="top" inOut>
        <p>top: Start editing to see some magic happen :)</p>
      </Observable>
      <Observable mode="left" inOut trDelay="0.5s" trOffset="100px">
        <p>left: Start editing to see some magic happen :)</p>
      </Observable>
      <Observable mode="right" inOut>
        <p>right: Start editing to see some magic happen :)</p>
      </Observable>
</main>

<style global>
  :root {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen,
      Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  }

  main {
    text-align: center;
    padding: 1em;
    margin: 0 auto;
  }

  img {
    height: 16rem;
    width: 16rem;
  }

  h1 {
    color: #ff3e00;
    text-transform: uppercase;
    font-size: 4rem;
    font-weight: 100;
    line-height: 1.1;
    margin: 2rem auto;
    max-width: 14rem;
  }

  p {
    max-width: 14rem;
    margin: 1rem auto;
    line-height: 1.35;
  }

  @media (min-width: 480px) {
    h1 {
      max-width: none;
    }

    p {
      max-width: none;
    }
  }

</style>
