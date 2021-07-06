
## Quill delta to Markdown converter
Converter from the [Delta](https://quilljs.com/docs/delta/) document format used by the [Quill](https://quilljs.com/) 
text editor to Slack's Markdown

## Usage

```typescript
import { deltaToMarkdown } = from 'quill-delta-to-markdown';
const markdown = deltaToMarkdown(deltaFromElseWhere)
```

## Test

```
npm install
npm test
```

## About

This lib was forked from [frysztak's fork](https://github.com/frysztak/quill-delta-to-markdown) of [rdesmartin's fork](https://github.com/rdesmartin/quill-delta-markdown) of [the Slite Team's fork](https://github.com/sliteteam/quill-delta-markdown) of 
[Bart Visscher (bartv2) 's lib](https://github.com/bartv2/quill-delta-markdown). Open source!
