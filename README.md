# W210S

A modification of [W210](https://github.com/paulHasselkuss/W210) to be used for single page sites. WIP.

The homepage consists of multiple sections (using `details` elements) created from the markdown files in `content/home`. You can control their order by assigning a `weight` in the file's frontmatter. By default, sections are closed, but you can overwrite this by setting `open` to `true`.

See [W210](https://github.com/paulHasselkuss/W210) for other features.

## Usage

Add the following to your `config.yml`:

```YAML
module:
  imports:
  - path: github.com/paulHasselkuss/W210S
```

## License

W210S is copyright © 2021-2022 Paul Hasselkuß. It is free software, and may be redistributed under the terms specified in the [license](LICENSE.md).