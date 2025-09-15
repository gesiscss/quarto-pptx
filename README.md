# Quarto PowerPoint template for GESIS (unofficial)

This is not an **official** product. Please use the official Powerpoint template available at [GESIS Intranet](https://intranet.gesis.intra/Vorstand/Kommunikation_Transfer/SitePages/Poster_Logos_Vorlagen_Styleguide.aspx)!

This is based on GESIS PowerPoint template presentation from 12.06.2024.

## Usage

### Recommended Way

Run

```bash
quarto use template gesiscss/quarto-pptx
```

to install this Quarto extension and a template file to start.

You can render your document as usual.

### Creating a repository from a template

**This only works for GitHub!**

Follow the steps in "[Creating a repository from a template](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template#creating-a-repository-from-a-template)" and choose `gesiscss/quarto-pptx` in the dropdown menu of "Start with a template".

You can render your document as usual.

## `_quarto.yml`

Make sure that `_quarto.yml` has

```
project:
  type: gesis
```

## Features

- [X] Background of slides

## Limitations

### "Thanks" Slide

Pandoc does not support use of classes to select the master slide to use.

## Frequenty Asked Questions

1. Where can I find more information on create PowerPoint presentations with Quarto?

   Check [Guide > Presentations > PowerPoint](https://quarto.org/docs/presentations/powerpoint.html) from Quarto official documentation.