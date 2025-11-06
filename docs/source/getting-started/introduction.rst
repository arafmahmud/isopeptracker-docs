Introduction
============

A Shiny Application for Alternative Splicing Analysis and Peptide Mapping
--------------------------------------------------------------------------

IsoPepTracker is a powerful bioinformatics tool designed to visualize alternative splicing events, map peptides to genomic coordinates, and compare protein isoforms at the peptide level. It provides interactive visualizations to explore how alternative splicing influences protein diversity and peptide generation under various proteolytic digestion conditions.

**Web Portal**: https://www.isopeptracker.org

.. figure:: ../_static/isopeptracker.png
   :alt: IsoPepTracker Workflow
   :align: center
   :width: 100%
   
   IsoPepTracker workflow for alternative splicing analysis and peptide mapping

Purpose
-------

IsoPepTracker enables researchers to:

* Analyze canonical and its associated peptides across different transcript isoforms
* Identify novel peptides arising from novel isoforms discovered through RNASeq or long read RNA sequencing
* Search for peptides across transcripts
* Visualize alternative splicing events and their impact on peptide generation

Key Features
------------

* **Multi-Isoform Peptide Comparison**: Interactive comparison of peptides across multiple transcript isoforms
* **Alternative Splicing Visualization**: Visualize 5 AS event types (SE, A3SS, A5SS, MXE, RI) in canonical isoforms
* **Enzyme Digestion Simulation**: Analyze peptides from 6 proteases:

  * Trypsin
  * Chymotrypsin
  * AspN
  * LysC
  * LysN
  * GluC

* **Novel Isoform Analysis**: Identify and characterize novel peptides from alternative splicing
* **BLASTP Integration**: Search peptides against protein databases for functional annotation
* **AS Tool Support**: Process and visualize outputs from rMATS and SplAdder

Getting Started
---------------

To begin using IsoPepTracker:

1. Visit the `web application <https://www.isopeptracker.org>`_
2. Choose the appropriate module for your analysis
3. Follow the module-specific workflows described in this documentation

For detailed information about each module, see the :doc:`../modules/canonical` section.