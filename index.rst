Document/Project Title
##########################################

Each Sphinx project has an index page, as well as index pages for parts of the document, which align to subfolders.

Start each index page with a summary of the document or part, followed by the
toctree command and links to the index file for each part, or topics within that
part.

Example for index:

.. toctree::
      :maxdepth: 1

      file
      file
      file
      file
.. list-table::
   :widths: 25 25 50
   :header-rows: 1

   * - Heading row 1, column 1
     - Heading row 1, column 2
     - Heading row 1, column 3
   * - Row 2, column 1
     - Row 2, column 2
     - Row 2, column 3
   * - Row 3, column 1
     - Row 3, column 2
     - Row 3, column 3
