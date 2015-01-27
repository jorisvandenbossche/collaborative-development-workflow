Presentation on workflows for collaborative code development.

The slides can be seen here: https://github.ugent.be/pages/jorvdnbo/collaborative-development-workflow/collaborative-development-workflow.slides.html?theme=sky#/

To convert the notebook to html reveal slides:

    ipython nbconvert collaborative-development-workflow.ipynb --to=slides --post=serve --reveal-prefix=reveal.js-2.6.2 --config slides_config.py

Without automatically serving the slides:

    ipython nbconvert collaborative-development-workflow.ipynb --to=slides --reveal-prefix=reveal.js-2.6.2 