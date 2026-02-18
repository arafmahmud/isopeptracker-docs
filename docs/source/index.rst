IsoPepTracker Documentation
============================

Welcome to IsoPepTracker, an interactive peptide visualizer for alternative splicing analysis. It provides a comprehensive platform for analyzing peptides across transcript isoforms, identifying novel peptides from alternative splicing events, and visualizing splicing impacts on the proteome.


Quick Start
-----------

IsoPepTracker provides four main modules for comprehensive peptide and alternative splicing analysis:

* **Canonical Isoform Analysis**: Analyze canonical peptides across isoforms 
* **Novel Isoform Analysis**: Identify and characterize novel isoforms using peptides
* **Peptide Search**: Search for specific peptides across all genes and isoforms in the database  
* **Alternative Splicing**: Visualize and analyze peptide impact of alternative splicing events

.. note::

   **Performance Note for Large Genes**

   Most genes (e.g. TP53) load within seconds. Exceptionally large genes
   such as TTN, which contains over 300 exons, may require approximately
   10 minutes to fully load due to the volume of transcript and peptide data.


.. toctree::
   :maxdepth: 2
   :caption: Getting Started

   getting-started/introduction

.. toctree::
   :maxdepth: 2
   :caption: Modules

   modules/canonical-isoform-analysis
   modules/novel
   modules/peptide-search
   modules/alternative-splicing



.. toctree::
   :maxdepth: 2
   :caption: Resources

   resources/contact

External Links
--------------

* `Web Application <https://isopeptracker.org>`_
* `Source Code <https://github.com/HuangLabAtUAB/IsoPepTracker>`_

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`