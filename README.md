# hugo-pdf-iframe

Shortcode to embed PDF files using iframes and Hugo shortcode

# Usage

1. Add the repository as a submodule

```
git submodule add https://github.com/ericswpark/hugo-pdf-iframe.git themes/hugo-pdf-iframe
```

2. Add `hugo-pdf-iframe` as a theme in your `config.toml`:

```
theme = ["hugo-pdf-iframe", "default-theme-name"]
```

3. Add the following snippet where you want to embed PDFs:

```
{{< pdf url="/path/to/pdf/file.pdf" >}}
```

