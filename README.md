# hugo-rawhtml

Shortcode to embed raw HTML in Hugo

Thanks to @anaulin for the [original code snippet (link to the blog post)][original-blog-post]. This just wraps that up into a Hugo theme so it can be added/removed from projects as needed.

[original-blog-post]: https://anaulin.org/blog/hugo-raw-html-shortcode/

# Installation

## Hugo Module

1. Add the repository as a Hugo module

```
hugo mod get github.com/ericswpark/hugo-rawhtml
```

2. Add to your `config.toml`:

```toml
# Modules
[module]
  # Other module imports here...
  [[module.imports]]
    path = "github.com/ericswpark/hugo-rawhtml"
    disable = false
```

## Git Submodule (deprecated)

1. Add the repository as a submodule

```
git submodule add https://github.com/ericswpark/hugo-rawhtml.git themes/hugo-rawhtml
```

2. Add `hugo-rawhtml` as a theme in your `config.toml`:

```
theme = ["hugo-rawhtml", "default-theme-name"]
```

# Usage

Add the following snippet when you want to use raw HTML:

```markdown
{{< rawhtml >}}

<!-- Insert your HTML code here -->

{{< /rawhtml >}}
```
