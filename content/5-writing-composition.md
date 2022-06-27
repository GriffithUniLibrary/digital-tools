## Markdown

{% capture aboutmarkdown %}
`Markdown` is a simple and popular text formatting syntax. It has many advantages for writing for the web, including the fact that it produces plain text files, which are easily shared. It's worth becoming familiar with it. This site is written in Markdown.
{% endcapture %}
{% include alert.html text=aboutmarkdown color="info" %}

{% capture markdowntools %}

All of the programming text editors above support Markdown. Below are some dedicated Markdown editors. 

- **[Dillinger](https://dillinger.io)**:  popular and free online Markdown editor.

- **[Stackedit](https://stackedit.io)**: popular and free online Markdown editor.

- **[Ulysses](https://ulysses.app)**: a general-purpose writing app with good Markdown support.

- **[Marked 2 (Mac)](https://marked2app.com)**

{% endcapture %}
{% include card.html header="<i class='fab fa-markdown'></i> Markdown editors" text=markdowntools %}

## LaTeX

`LaTeX` is a text formatting language (like `Markdown`) which is very flexible and robust. It is very well suited to scientific and mathematical notation. It is format agnostic your document structure, headings and figures can use any style you like. 

{% capture latextools %}

- **[Overleaf](https://www.overleaf.com)**: is a web-based LaTeX editor with many built-in templates and automatic preview. It can automatically format your paper for certain journals and even submit them for you.

{% endcapture %}
{% include card.html header="LaTeX composition tools" text=telatextoolsxt %}

## Pandoc

`Pandoc` is an open-source tool that can convert just about any document format into just about any other document format! You can use it to convert your `Markdown` or `LaTeX` documents into Word — even automatically if you want!

## Composition tools

{% capture compostition %}

- **[Scrivener](https://www.literatureandlatte.com/scrivener/)**: designed for long-form writing

- **[Hemingway Editor](http://hemingwayapp.com/)**: This website checks your text for readability. It warns you if you are being too verbose or your sentences are too long. Use it as a good guideline, without relying on it too heavily.

- **[Microsoft Word](https://www.office.com)**: popular—ubiquitous, almost—but not always the best tool.

- **[Manuscripts](https://www.manuscriptsapp.com)**

- **[Authorea](https://www.authorea.com)**: Billed as 'Google Docs for scientists', automatic journal submission.

{% endcapture %}
{% include card.html header="<i class='fas fa-pencil-alt'></i> Composition tools" text=compostition %}