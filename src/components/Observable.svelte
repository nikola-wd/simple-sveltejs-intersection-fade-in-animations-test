<script>
  // import logo from './assets/svelte.png'
  // console.log('slots: ', $$slots)
  import { onMount } from 'svelte';
  import {IntersectionTransitions} from '../classes/IntersectionTransitions'

  // props
    export let mode = false
    export let inOut = false
    export let rootMargin = '80px 0px 0px 0px'
    export let treshold = 0.35
    export let trOffset = '30px'
    export let trDelay = '0s'
    export let trDuration = '0.4s'
  // end props

  let helperRef

  onMount(() => {
    const el = helperRef.nextElementSibling
    el.style.setProperty('--ivtr-offset', trOffset);
    el.style.setProperty('--ivtr-delay', trDelay);
    el.style.setProperty('--ivtr-duration', trDuration);

    el.classList.add('ivtr');
    if (mode) el.classList.add(`ivtr--${mode}`);
    if (inOut) el.classList.add('ivtr--in-out');
    new IntersectionTransitions({ el, rootMargin, treshold });
  });
</script>

<span bind:this={helperRef} style="display: none; position: absolute;" />
<slot />

 
