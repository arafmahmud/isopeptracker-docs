Peptide Search Module
=====================

The Peptide Search module provides a powerful interface to search for specific peptides across the entire IsoPepTracker database.

Module Overview
---------------

This module enables comprehensive searching across all peptides in the IsoPepTracker database, allowing researchers to quickly find peptides of interest and their associated metadata.

Search Capabilities
-------------------

The search functionality supports multiple query types:

* **Peptide sequence search**: Find exact or partial sequence matches
* **Gene name search**: Search by associated gene symbols
* **Transcript ID search**: Query specific transcript identifiers
* **Property-based filtering**: Filter by peptide characteristics

Search Interface
----------------

The search interface provides:

* **Auto-complete functionality**: Suggestions as you type
* **Advanced filters**: Refine results by multiple criteria
* **Batch search**: Upload multiple queries simultaneously
* **Export options**: Download results in various formats

How to Use
----------

Follow these steps to perform a search:

.. note::
   **Search Workflow**

   1. **Enter your search query**
      
      Input peptide sequence, gene name, or transcript ID

   2. **Apply filters if needed**
      
      Use advanced filters to narrow results

   3. **View search results**
      
      Browse through matching peptides and metadata

   4. **Export results for further analysis**
      
      Download data in preferred format

Query Types
-----------

Exact Sequence Search
~~~~~~~~~~~~~~~~~~~~~

Search for peptides with exact sequence matches::

   PEPTIDER
   SEQUENCE
   MATCHING

Partial Sequence Search
~~~~~~~~~~~~~~~~~~~~~~~

Use wildcards for partial matches::

   PEP*ER
   *QUENCE
   MATCH*

Gene-based Search
~~~~~~~~~~~~~~~~~

Search by gene symbols::

   BRCA1
   TP53
   EGFR

Advanced Filters
----------------

Available filters include:

* **Peptide length**: Filter by amino acid count
* **Molecular weight**: Mass range filtering
* **Isoelectric point**: pI range selection
* **Modification status**: Modified vs. unmodified peptides
* **Protease specificity**: Filter by cleavage enzyme

Search Results
--------------

.. info::
   **Results Include**

   * Matching peptide sequences
   * Associated genes and transcripts
   * Isoform information
   * Peptide locations and properties
   * Cross-links to related modules

Performance Tips
----------------

For optimal search performance:

* Use specific queries when possible
* Combine multiple filters for focused results
* Use batch search for large query sets
* Export large result sets for offline analysis

Integration with Other Modules
------------------------------

Search results can be directly used with:

* **Canonical module**: Analyze found peptides across isoforms
* **Novel module**: Check if peptides are novel variants
* **Alternative Splicing module**: View splicing context

For alternative splicing analysis, see :doc:`alternative-splicing`.