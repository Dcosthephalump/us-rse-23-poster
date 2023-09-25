# us-rse-23-poster

This repository accompanies the poster "JupyterIDE: Promoting JupyterLab features and extensions that facilitate collaboration among researchers and RSEs" presented at [US-RSE'23](https://us-rse.org/usrse23/). Similar to the poster, this repository details some of the [JupyterIDE](https://github.com/Accessible-Data-and-Code/jupyterlab-ide) project goals and showcasing useful tools for making JupyterLab a more powerful development environment.

# Abstract
Jupyter Notebooks are open-source tools researchers commonly use to develop workflows and other software. Researchers and RSEs alike are most likely familiar with the Classic Notebook interface, the original web application for creating and sharing notebooks, but there are several other coding environments to choose from. An Integrated Development Environment (IDE) is a software application that provides helpful features beyond traditional source code editors, such as debuggers, for developing software. However, IDEs such as VSCode can present a barrier to entry for researchers familiar with other tools. JupyterLab, an alternative developed by Project Jupyter, is an extensible development environment for notebooks that comes with many IDE-like features, including a debugger and tab expansion. Additionally, the community maintains many other helpful extensions that do not ship with the default environment. Our JupyterIDE project collects and curates useful extensions and provides notebook-based tutorials for how to use them. Tutorial-style notebooks include notebooks on Vim keybindings, which make cell manipulation faster and easier, and language server processing, which provides code auto-completion and linting features. Tools like these can make JupyterLab an ideal environment for developing research workflows that can be used by seasoned RSEs who are accustomed to IDE features in collaboration with researchers who may not have interest in investing time into learning a new tool. JupyterIDE makes these tools more accessible for users and promotes software engineering best practices in a research environment.

# Background

I have said all of this badly. Please forgive the roughness of this draft.

It is [not uncommon](https://jupyter4edu.github.io/jupyter-edu-book/case-studies.html#jupyter-notebooks-in-support-of-scaling-for-large-enrollments) for researchers to have been introduced to Python and other programming languages for scientific computing through Jupyter Notebooks. Introductions like these often do not involve a systematic approach to learning coding practices or a theoretical background in computer science that most career professionals in software engineering have. As researchers continue to use computational tools like the ever popular Jupyter Notebook, moving from this functional but limited background in coding is a difficult and time consuming task that may not be feasible for researchers to do while working against deadlines and handling administrative and logistical tasks (trying to communicate that things like grants need to be applied to, research deadlines are real, even if they are somewhat soft sometimes, etc...) that remain constant in a research career. For this reason, researchers often continue to use the same tools in the same ways as they learned near the beginning of their careers.

Software engineers who work with researchers often have a background working with a large assortment of software creation tools each geared towards different development workflows. When software engineers work with researchers, it is often to assist researchers with a wide variety of relatively limited workflows and backgrounds in scientific computing. Turning an existing and developing research workflow into a software product (I don't like the term product, but I'm coming up blank here for better words) may involve technologies that researchers are unfamiliar with, such as version control systems (see Git), or software development products, like traditional IDEs, that researchers do not use. For this reason, software engineers and researchers can struggle with a disconnect in technical backgrounds that hampers the development of research software.

# Solution

Outline:
Talk about bringing researchs and software engineers together.

For researchers, JupyterIDE:
- introduces JupyterLab as a friendly alternative to Jupyter Notebook
  - JupyterLab has the ability to view multiple files at the same time, search the file tree, use a console for a kernel, and many other things useful for researchers not available in the Jupyter Notebook interface
- gently introduces better coding practices for a research environment

For software engineers, JupyterIDE:
- introduces JupyterLab as an extensible development environment with several quality of life features for software development highlighted and community extensions given tutorials
  - Git extension and LSP are especially good examples of what is available.
- introduces the literate programming approach as uniquely suited for creating documentation and working with researchers

Draft:
Bringing researchers and software engineers closer together in terms of their toolsets, coding practices, and paradigms will help facilitate communication and development. JupyterIDE can help with this in a number of ways. For researchers, it introduces JupyterLab as an alternative to Jupyter Notebook. While the two programs share a similar layout and JupyterLab maintains an interface optimized for notebook development, JupyterLab also has several features that help with productivity such as the ability to view a notebook and a dataframe simultaneously in one window. To take advantage of this, JupyterIDE includes a short, accessible tutorial on literate programming for researchers using JupyterLab that helps researchers build documentation for exploratory data analysis and avoid common problems associated with results reproducibilitiy in notebooks. In addition, there is a tutorial for the Git extension that helps researchers learn about the value of version control, especially in collaborative research environments, and how to use it easily with JupyterLab.

There are several development tools commonly associated with IDEs that software engineers may be familiar with or would benefit from using. JupyterIDE can help software engineers by introducing useful JupyterLab extensions (in a pre-made Conda environment) for software engineering and making them easy to learn or review with tutorials for compatible versions of the extensions. The language server processing extension includes code linting and code autocompletion, among many other features, which are introduced in a tutorial from JupyterIDE. The Vim extension brings Vim keybindings to JupyterLab and extends them to interacting with code cells. These new features are also introduced with a tutorial from JupyterIDE. Other, less transformative extensions are also included with tutorials. This allows for software engineers to quickly learn the JupyterLab development environment with useful extensions.

# Acknowledgments

<img width="200" align="left" alt="BSSw-logo" src="https://github.com/nicole-brewer/rmacc-hpc-symposium-2023/assets/20686935/e834056f-7169-4ce8-90ed-24bb878ab993">

This work was supported by the Better Scientific Software Fellowship Program, funded by the Exascale Computing Project (17-SC-20-SC), a collaborative effort of the U.S. Department of Energy (DOE) Office of Science and the National Nuclear Security Administration; and by the National Science Foundation (NSF) under Grant No. 2154495. Any opinions, findings, and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the DOE or NSF.
