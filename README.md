# LSU-Undergrad-Honors-Thesis

LaTeX template for Undergraduate Honors Thesis in the Department of Psychology

## Some important information

- This template uses APA format.
- There is an example figure.
- There is an example equation.
- There is an example in-text citation.
- There is an example .bib file.

## Structure

The actual body of your work, including abstract, acknowledgements, individual chapters, etc. are housed in their own documents. The `main.tex` file combines all of the elements together to compile the entire document. This is extremely helpful in keeping your work organized and clean.

## Printing your document

You have just completed a large body of work which is hopefully a reflection of your dedication and work ethic. It might be of interest to print your document and bind it similar to that of a novel. In the `main.tex` there are two components that must be changed, the `\documentclass` and the `\geometry`. Below are the necessary changes to have your document formatted for printing in book style.

```
\documentclass[twoside]{report}

\usepackage{geometry}
    \geometry{
        a4paper,
        outer=0.75in,
        inner=1.5in
    }
```

## Using this template

This template can be intergrated seamlessly into Overleaf. If you have premium features, you can fork this repository from GitHub and synchronize with Overleaf.

## Making changes

If you wish to make changes to the document, suggest improvements, or point out errors, please submit an issue on GitHub.

## Regular updates

This template will be monitored and receive regular improvements until **May 2024**.
