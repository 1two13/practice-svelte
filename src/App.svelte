<script>
  import {setContext} from 'svelte'
  import PanelComponent from './panelComponent.svelte'
  
  let count = 10
  
  function incrementCount(event) {
    count += 10
  }

  setContext('incrementCount', incrementCount)
  setContext('count', count)
  </script>
  
  <PanelComponent {count} />