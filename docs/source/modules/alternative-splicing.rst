Alternative Splicing Analysis Module
====================================

The Alternative Splicing Analysis module provides comprehensive visualization and analysis of alternative splicing events and their impact on peptide generation.

Module Overview
---------------

Alternative splicing is a crucial mechanism that increases protein diversity. This module helps researchers understand how splicing variations affect the resulting peptide landscape.

Supported Splicing Event Types
-------------------------------

The module supports analysis of five major alternative splicing event types:

=================== ========================================
Event Type          Description
=================== ========================================
**SE**              Skipped Exon
**A3SS**            Alternative 3' Splice Site
**A5SS**            Alternative 5' Splice Site  
**MXE**             Mutually Exclusive Exons
**RI**              Retained Intron
=================== ========================================

Input Support
-------------

The module is compatible with output from major splicing analysis tools:

rMATS Integration
~~~~~~~~~~~~~~~~~

* Process and visualize rMATS output files
* Support for all rMATS event types
* Direct import of statistical results
* Integration with rMATS confidence scores

SplAdder Compatibility
~~~~~~~~~~~~~~~~~~~~~~

* Compatible with SplAdder results
* Support for SplAdder event annotations
* Integration with SplAdder quantification

Key Features
------------

The module provides comprehensive splicing analysis capabilities:

* **Interactive visualization** of splicing events
* **Peptide consequence mapping** for each event
* **Event statistics and quantification** 
* **Comparison across conditions** (e.g., control vs. treatment)
* **Export visualizations and data** in multiple formats

Workflow
--------

.. tip::
   **Analysis Workflow**

   1. **Upload rMATS or SplAdder output files**
      
      Import your alternative splicing results

   2. **Select splicing event type to visualize**
      
      Choose from SE, A3SS, A5SS, MXE, or RI events

   3. **Choose specific events or genes of interest**
      
      Filter by statistical significance or gene lists

   4. **View splicing visualization and peptide impacts**
      
      Examine interactive plots and peptide consequences

   5. **Export results and figures**
      
      Download visualizations and processed data

Visualization Features
----------------------

The module generates various visualization types:

Event Diagrams
~~~~~~~~~~~~~~

* Schematic representation of splicing events
* Exon-intron structure visualization
* Splice site annotations

Peptide Impact Plots
~~~~~~~~~~~~~~~~~~~~

* Before/after peptide comparisons
* Sequence alignment visualizations
* Functional domain mapping

Statistical Summaries
~~~~~~~~~~~~~~~~~~~~~

* Event frequency distributions
* Significance score plotting
* Cross-condition comparisons

Input File Formats
------------------

Accepted file formats include:

rMATS Files
~~~~~~~~~~~

* ``SE.MATS.JC.txt`` - Skipped exon events
* ``A3SS.MATS.JC.txt`` - Alternative 3' splice sites
* ``A5SS.MATS.JC.txt`` - Alternative 5' splice sites
* ``MXE.MATS.JC.txt`` - Mutually exclusive exons
* ``RI.MATS.JC.txt`` - Retained intron events

SplAdder Files
~~~~~~~~~~~~~~

* SplAdder graph-based event files
* Quantification matrices
* Event annotation files

Parameters
----------

Configurable analysis parameters:

* **Significance threshold**: P-value or FDR cutoffs
* **Effect size filters**: Minimum delta PSI values
* **Coverage requirements**: Minimum read support
* **Gene filtering**: Focus on specific gene sets

Output
------

.. info::
   **Generated Output**

   The module generates:

   * Splicing event diagrams
   * Affected peptide lists
   * Statistical summaries
   * Exportable visualizations

Applications
------------

This module is valuable for:

* **Disease research**: Identifying pathological splicing changes
* **Drug discovery**: Understanding compound effects on splicing
* **Basic research**: Studying tissue-specific splicing patterns
* **Comparative genomics**: Cross-species splicing analysis

For contact information and additional resources, see :doc:`../resources/contact`.