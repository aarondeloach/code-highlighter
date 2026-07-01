# Code Highlighter

A component that renders code with [Shiki](https://github.com/shikijs/shiki) in Svelte apps.

It works on the client side (+page.svelte).

## Installation

```bash
npm install @aarondeloach/code-highlighter
```

## Usage

```javascript
// +page.svelte
<script>
    import {CodeHighlighter} from '@aarondeloach/code-highlighter'
</script>

<CodeHighlighter code={`<h1>Hello World</h1>`}/>
```
