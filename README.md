# Some App

## What is it?

It's a demonstration of the present inaccuracy of the TailWind SvelteKit Docs

As soon as you attempt to reference in the Svelte docs a color by the lil dot notation show in the docs it breaks.

```html
<style lang="postcss">
  :global(html) {
    background-color: theme(colors.gray.100);
  }
</style>
```

Before this it seems to work though - it is the referencing of the color.at.key notation that makes it 💥

For now can the docs be as they were?
