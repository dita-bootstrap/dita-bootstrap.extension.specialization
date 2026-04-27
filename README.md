# DITA Bootstrap Extension Specialization

DITA Bootstrap Extension Specialization is a [DITA Open Toolkit plug-in](https://www.dita-ot.org/plugins) that provides the DTD specializations for the [DITA Bootstrap Extension plug-in](https://dita-bootstrap.github.io/dita-bootstrap.extension).

## Installing

Use the `dita` command to add this plug-in and its requirements to your DITA Open Toolkit installation:

```console
dita install dita-bootstrap.extension.specialization
dita install dita-bootstrap.extension
```

## Featured Bootstrap Extension components

The plug-in includes DTD handling for the following Bootstrap Extension components:

- [Counter](https://bootstrapextensions.com/counter.html) (`<counter>`)
- [Parallax](https://bootstrapextensions.com/parallax.html) (`<parallax>`)
- [Slider](https://bootstrapextensions.com/slider.html) (`<slider>`)
- [Whitebox](https://bootstrapextensions.com/whitebox.html) (`<whitebox>`)

## Using Bootstrap Extension Specializations

The extension specializations provide native DITA elements for Bootstrap Extension features:

```xml
<parallax href="background.jpg" speed="0.5">
  <title>Parallax Title</title>
  <p>Content goes here.</p>
</parallax>
```

### Attributes

The extension specializations support common Bootstrap decoration attributes:

- **Color Themes**: `color` and `bordercolor`.
- **Borders**: `border` and `rounded`.
- **Spacing**: `margin` and `padding`.
- **Layout**: `width` and `shadow`.

## License

[Apache 2.0](LICENSE) © 2024-2026 Jason Fox

Within the documentation, where necessary, the texts describing the Bootstrap Extension usage of each component have been copied directly from the [Bootstrap Extension documentation](https://bootstrapextensions.com/) however DITA markup is used throughout the examples describing how to implement these components correctly using DITA specializations or `outputclass`. The text is therefore a derivative of "Bootstrap Extension docs" by AKK IT, Inc, and used under MIT.
