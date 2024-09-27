# Quarto PowerPoint template for GESIS (unofficial)

This is a repository for Quarto PowerPoint template. And this is not an **official** product. Please use the official Powerpoint template available at [GESIS Intranet](https://intranet.gesis.intra/Vorstand/Kommunikation_Transfer/SitePages/Poster_Logos_Vorlagen_Styleguide.aspx).

## Installation

### As Fork 

Fork this repository.

### By Download the Reference Document

Download the reference document [`gesis.pptx`](gesis.pptx).

### Template

Not available yet.

## Usage

Include the following snippet in the YAML header of your document.

```yaml
format:
  pptx:
    reference-doc: gesis.pptx
```

And render the document as usual, for example,

```bash
quarto render
```

## Features

- [X] Background of slides

## Limitations

### "Thanks" Slide

Pandoc does not support use of classes to select the master slide to use.

## Frequenty Asked Questions

1. Where can I find more information on create PowerPoint presentations with Quarto?

   Check [Guide > Presentations > PowerPoint](https://quarto.org/docs/presentations/powerpoint.html) from Quarto official documentation.