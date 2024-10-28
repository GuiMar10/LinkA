<script>
  import svelteLogo from './assets/svelte.svg'
  import viteLogo from '/vite.svg'
  import Counter from './lib/Counter.svelte'
</script>

<h2>Oie, papai!</h2>
<input type="text" placeholder="Pesquisar">
<div class="card">Card ;)</div>
<div class="card">Card ;)</div>

<style>
  @font-face {
    font-family: More Sugar;
    src: url('./assets/MoreSugar-Regular.otf')
  }
  input {
    border-radius: 100px;
    font-size: 17px;
    padding: 10px;
    border-top: 2px solid;
    border-bottom: 7px solid;
    border-left: 4px solid;
    border-right: 4px solid;
    transition: 0.2s ease;
    border-color: #882fda;
    outline: #521887 solid 2px;
    outline-offset: -1px;
  }
  input:active {
    scale: 0.95 0.9;
  }
  .card {
    border-radius: 10px;
    background: rgb(227, 211, 255);
    margin-top: 12px;
    transition: 0.2s;
    cursor: pointer;
    border-bottom: 3px solid;
    border-right: 3px solid;
  }
  .card:hover{
    scale: 1.02;
  }
  .card:active {
    scale: 1;
  }
  h2 {
    font-family: More Sugar;
  }
</style>
