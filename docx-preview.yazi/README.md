# docx-preview.yazi

Use [docx2txt](https://docx2txt.sourceforge.net/) to preview DOCX files in [yazi](https://github.com/sxyazi/yazi).

## Requirements

- [docx2txt](https://docx2txt.sourceforge.net/) - It's probably available in your package manager.

## Installation

Install with:

```sh
ya pack -a lpanebr/yazi-plugins:docx-preview.yazi
```

and enable by adding it to your `yazi.toml` config file:

```toml
[plugin]
prepend_previewers = [
    { name = "*.doc", run = "doc-preview" },
]
```