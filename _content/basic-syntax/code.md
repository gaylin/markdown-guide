<h1 class="page-header">Code</h1>

To denote a word or phrase as code, enclose it in tick marks (`` ` ``).

<table class="table table-bordered">
  <thead>
    <tr>
      <th>Markdown</th>
      <th>HTML</th>
      <th>Rendered Output</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code class="highlighter-rouge">At the command prompt, type `nano`.</code></td>
      <td><code class="highlighter-rouge">At the command prompt, type &lt;code&gt;nano&lt;/code&gt; </code></td>
      <td>At the command prompt, type <code class="highlighter-rouge">nano</code>.</td>
    </tr>
  </tbody>
</table>

If the word or phrase you want to denote as code includes a tick mark, enclose it in double tick marks (<code>``</code>).

<table class="table table-bordered">
  <thead>
    <tr>
      <th>Markdown</th>
      <th>HTML</th>
      <th>Rendered Output</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>``Use `code` in your Markdown file.``</code></td>
      <td><code class="highlighter-rouge">&lt;code&gt;Use `code` in your Markdown file.&lt;/code&gt;</code></td>
      <td><code>Use `code` in your Markdown file.</code></td>
    </tr>
  </tbody>
</table>

## Code Blocks

To create code blocks, indent every line of the block by at least four spaces or one tab.

```
    <html>
      <head>
      </head>
    </html>
```

The rendered output looks like this:

    <html>
      <head>
      </head>
    </html>

<div class="alert alert-info">
  <i class="fa fa-info-circle" aria-hidden="true"></i> <strong>Note:</strong> For a different way of creating code blocks, see <a href="/extended-syntax/#fenced-code-blocks">fenced code blocks</a>.
</div>
