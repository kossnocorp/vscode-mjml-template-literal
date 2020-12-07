# vscode-mjml-template-literal

Syntax highlighting for MJML string literals (recommended to use with [tag-mjml](https://github.com/tinovyatkin/tag-mjml)):

```js
import tagMJML from "tag-mjml";

const mjml = tagMJML({
  /* MJML options */
});

const template = mjml`
<mjml>
  <mj-body>
    <mj-container>
      <mj-section>
        <mj-column>
          <mj-text>Hello World!</mj-text>
        </mj-column>
      </mj-section>
    </mj-container>
  </mj-body>
</mjml>`;
```

Based on [vscode-sql-template-literal](https://github.com/ForbesLindesay/vscode-sql-template-literal).
