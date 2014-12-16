BibTeX Repository
=================

This is my BibTeX repository. It contains the bib files to included via `\bibliography{/path/to/bibfile}`

Conventions
-----------

* filenames are `surnameFirstname.bib` of the first author on the paper
* labels are `surname%YYYY[-%MM[-%DD]]` with the year of publication. If more publications were made by this author in one year, use the month and eventually day of the publication. 
* include DOI whenever possible.

Examples
--------

.. code:: latex

    \bibliography{einsteinAlbert}
    \cite{einstein1935}

refers to the paper "Can Quantum-Mechanical Description of Physical Reality Be Considered Complete?" by Albert Einstein, Boris Podolsky and Nathan Rosen, published in 1935.
