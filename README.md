# hugo-iframe

Shortcode to embed iframes and Hugo shortcode

Works for iframe URLs and files such as PDFs.

# Usage

1. Add the repository as a submodule

```
git submodule add https://github.com/ericswpark/hugo-iframe.git themes/hugo-iframe
```

2. Add `hugo-iframe` as a theme in your `config.toml`:

```
theme = ["hugo-iframe", "default-theme-name"]
```

3. Add the following snippet where you want to embed iframes:

```
{{< iframe url="https://example.com/iframe/src/url/" >}}
{{< iframe url="/path/to/file.pdf" >}}
```

