{% capture editors %}

{% capture text %}
Plain text editors are much more important than you might think. Get yourself a good one.
{% endcapture %}
    
{% include alert.html text=text color=info %}

These text editors are all oriented towards programming and editing code. They have features that are helpful when working in code, like syntax coloring and code folding. Even if you don't consider yourself a programmer, you'll find a good text editor invaluable.

- **[Sublime Text](https://www.sublimetext.com)**: one of the most popular programming text editors for Windows

- **[Notepad++](https://notepad-plus-plus.org/)**: a popular free option

- **[BBEdit (Mac)](https://www.barebones.com/products/bbedit/)**: a venerable (30y+) program with many fans.

- **[Atom](https://atom.io)**: Free, extensible with lots of plugins

- **[Brackets](http://brackets.io)**: Adobe's free text editor.

- **[Visual Studio Code](code.visualstudio.com)**: Microsoft's programming-oriented text editor. Free and highly extensible.

{% capture besttext %}
**Our recommendation: Visual Studio Code**

Microsoft's editor is free, highly extensible (meaning it has lots of plugins to improve its features) and integrates directly with GitHub. I'm writing these words in VS Code right now!
{% endcapture %}
{% include alert.html text=besttext color="primary" %}

{% endcapture %}
{% include card.html header="<i class='fas fa-superscript'></i> Programming text editors" text=editors img="code-editor.png" %}

{% capture environments %}

{% capture text %}
**What's a development environment?**: It's a set of tools that allow you to write, debug, build and run code. Some development environments support a single language  or platform (like R), and some (like Visual Studio) support multiple languages and platforms.
{% endcapture %}

{% include alert.html text=text color="info" %}

- **[R](https://www.r-project.org)**:  extensible, support through Hacky Hour and Carpentries

- **[Python](https://www.python.org)**: support through Hacky Hour and Carpentries

- **[GitLab](https://gitlab.rcs.griffith.edu.au)**: Griffith University shared code repository

- **[Visual Studio](https://visualstudio.microsoft.com)**: mulitiplatform IDE published by Microsoft

- **[GitHub](https://github.com)**: a popular code repository site. This site is hosted on GitHub.

- **[Anaconda](https://www.anaconda.com/distribution/)**: Python development environment

{% endcapture %}

{% include card.html header="<i class='fas fa-bug'></i> Development languages and environments" text=environments %}