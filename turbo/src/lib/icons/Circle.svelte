<script>
  export let size = '.8em';
  export let width = size;
  export let height = size;
  export let color = 'currentColor';
  export let viewBox = '0 0 24 24';
  export let ariaLabel = void 0;
  export let ariaHidden = void 0;
  export let title = void 0;
  export let desc = void 0;

  let className = void 0;
  export { className as class };
</script>

<svg {viewBox} {width} {height} class={className} aria-label={ariaLabel} aria-hidden={ariaHidden}
  >{#if desc}<desc>{desc}</desc>{/if}{#if title}<title>{title}</title>{/if}<path
    d="M12,2A10,10 0 0,0 2,12A10,10 0 0,0 12,22A10,10 0 0,0 22,12A10,10 0 0,0 12,2Z"
    fill={color}
  /></svg
>
