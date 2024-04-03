
请帮我为typescript的类或方法写文档，文档格式参考下边的Example，

Example:

```markdown

### Clipboard.copy

Copies text or a file to the clipboard.

#### Signature

<CodeGroup>
```ts clipboard.ts 
async function copy(content: string | number | Content): Promise<void>
```
</CodeGroup>

#### Props
<ParamField body="content" type="string|integer|Content" required>
  The content to be added to the Clipboard.
</ParamField>


#### Example

<CodeGroup>
```ts example.ts 
import {  Clipboard } from "@enconvo/api";

export default async function main(req: Request) {

    // copy text to clipboard
    await Clipboard.copy("Hello World")

}
```
</CodeGroup>

```

Attention:
TLDR; just give me the final structure json, don't show me any process and explanation

这个是类/方法，{text}，请开始：
