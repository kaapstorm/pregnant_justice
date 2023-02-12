The First Pregnant Justice
==========================

by Norman Hooper


.. figure:: src/img/dore_solomon.jpg
   :alt: The Judgement of Solomon by Gustave Doré

   The Judgement of Solomon by Gustave Doré


© Norman Hooper, 2023. Some rights reserved. This work is licensed under a
`Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License`_.


How to make a document
----------------------

You can turn these files into an ePub document, a single-page HTML
document, or HTML files with one page per chapter.

The following instructions are for Linux, and assume that you have Git
and Python installed.

1. Clone this repository locally.

2. Create and activate a Python virtual environment.
   ::
       $ python3 -m venv venv
       $ source venv/bin/activate

3. Install requirements.
   ::
       $ pip install -r requirements.txt

4. You are now ready to build your document.

   a. For ePub:
      ::
          $ sphinx-build -b epub src _build/epub

      Your ePub will be saved as
      ``_build/epub/TheFirstPregnantJustice.epub``.

   b. For single-page HTML:
      ::
          $ sphinx-build -b singlehtml src _build/singlehtml

      To read, open ``_build/singlehtml/index.html`` in your browser.

   c. For page-per-chapter HTML:
      ::
          $ sphinx-build -b html src _build/html

      To read, open ``_build/html/index.html`` in your browser.


.. _Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License: http://creativecommons.org/licenses/by-nc-sa/4.0/
