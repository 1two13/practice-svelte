<script>
  import PanelComponent from './panelComponent.svelte'
  
  let count = 10
  
  function incrementCount(event) {
    console.log(event.detail.message)
    count += 10
  }
  </script>
  
  <PanelComponent {count} on:increment={incrementCount}/>