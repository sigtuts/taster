<div class="container">
  <h1 class="header">Welcome</h1>
  <div class="main" />
  <h2 class="footer">Good Bye</h2>
</div>

<style>
  .container {
    display: grid;
    grid-template-columns: 1fr 2fr 1fr;
    grid-template-rows: 1fr 6fr;
    grid-template-areas:
      "header header header"
      "main main main"
      "footer footer footer";
    grid-gap: 1rem;
    width: 100vw;
    height: 100vh;
    background-image: linear-gradient(45deg, black, transparent);
  }
  .header {
    grid-area: header;
    background-color: #00fafa11;
    padding: 1rem;
    text-align: center;
  }
  .main {
    grid-area: main;
    background-color: #fafa0022;
    padding: 1rem;
  }
  .footer {
    grid-area: footer;
    background-color: #fa55fa11;
    padding: 1rem;
    text-align: center;
  }
</style>
