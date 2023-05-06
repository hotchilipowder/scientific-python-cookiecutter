================================
What I have done for my workflow
================================


一些值得注意的点: 

+ 使用相对路径例如 \ :code:`from . import utils`\, see \ `multiple modules <https://nsls-ii.github.io/scientific-python-cookiecutter/the-code-itself.html#multiple-modules>`_
+ `sphinx autodoc documentation <http://www.sphinx-doc.org/en/stable/ext/autodoc.html>`_.
+ `IPython sphinx directive documentation <https://ipython.org/ipython-doc/rel-0.13.2/development/ipython_directive.html>`_.
+ `matplotlib plot directive documentation <https://matplotlib.org/devel/plot_directive.html>`_ .
+ `the Sphinx documentation <http://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html>`_
+ Include data file see \ `including-data-files <https://nsls-ii.github.io/scientific-python-cookiecutter/including-data-files.html>`_




Docs Changes
==============

Add some sphinx-extensions
--------------------------

.. code-block:: bash

    ...
    "sphinx_design",
    "sphinx_copybutton",
    "sphinxcontrib-bibtex",
    "sphinx_comments",
    "sphinxemoji.sphinxemoji",
    ]

    html_css_files = [
     "https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css"
    ]
    
    bibtex_bibfiles = ['refs.bib']







