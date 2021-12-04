<script>
  export let title;
  export let desc;
</script>

<div class="card">
  <div class="container">
    <h4><b>{title}</b></h4>
    <p>{desc}</p>
  </div>
</div>

<style>
  .card:hover {
    box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2);
  }

  .container {
    padding: 2px 16px;
  }

  .card {
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
    transition: 0.3s;
    border-radius: 5px; /* 5px rounded corners */
    margin: 20px auto;
    width: 30%;
    align-items: center;
    justify-content: center;
    text-align: center;
    text-align: center;
    color: rgb(169, 169, 179);
    font-family: "Inter UI", -apple-system, BlinkMacSystemFont, "Roboto",
      "Segoe UI", Helvetica, Arial, sans-serif;
    line-height: 1.54;
    text-rendering: optimizelegibility;
    font-feature-settings: "liga", "tnum", "case", "calt", "zero", "ss01",
      "locl";
    font-size: 1rem;
    letter-spacing: 0.03em;
  }

  h4,
  p {
    color: aliceblue;
    font-family: "Inter UI", -apple-system, BlinkMacSystemFont, "Roboto",
      "Segoe UI", Helvetica, Arial, sans-serif;
  }
</style>
