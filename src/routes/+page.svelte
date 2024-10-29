<script>
</script>

<h2>Oie, papai!</h2>
<div id="search">
  <input type="text" placeholder="Pesquisar" />
  <button>b</button>
</div>
<div class="card">Card ;)</div>
<div class="card">Card ;)</div>

<style lang="scss">
  :global(body) {
    font-family: More Sugar;
    --borderColor: #521887;
  }
  @font-face {
    font-family: More Sugar;
    src: url("/MoreSugar-Regular.otf");
  }
  #search {
    width: max-content;
    border-radius: 20px;
    transition: 0.2s ease;
    &:active {
      scale: 0.95 0.9;
    }
    & button {
      position: relative;
      border-radius: 50px;
      background: #9e6df7;
      color: white;
      border: 1px solid var(--borderColor);
      cursor: pointer;
      height: 39px;
      width: 39px;
      transform: translateX(-52px) translateY(-2px);
    }
  }
  input {
    border-radius: 100px;
    font-size: 17px;
    padding: 10px;
    border-top: 2px solid;
    border-bottom: 7px solid;
    border-left: 4px solid;
    border-right: 4px solid;
    border-color: #882fda;
    outline: var(--borderColor) solid 2px;
    outline-offset: -1px;
    width: 180px;
    font-family: More Sugar;
  }
  .card {
    border-radius: 10px;
    background: rgb(227, 211, 255);
    margin-top: 12px;
    transition: 0.2s;
    cursor: pointer;
    box-shadow: 2px 2px 2px 2px rgb(175, 143, 230);
    user-select: none;
    width: 100%;
    height: 50px;
    text-align: center;
    place-content: center;
    &:hover {
      scale: 1.02;
    }
    &:active {
      scale: 1;
      box-shadow: none;
    }
  }
  h2 {
    font-family: More Sugar;
  }
</style>
