Canonical Isoform Analysis
==========================

Analyze canonical peptides across isoforms.

.. figure:: ../_static/analysis_parameters.png
   :alt: Analysis Parameters panel
   :align: center
   :width: 100%

   Analysis Parameters -- select a gene, enzyme, missed-cleavage allowance,
   and intron display mode before updating the view.

The Canonical module provides comprehensive analysis of known peptides across
different transcript isoforms. It is divided into three complementary analysis
approaches, accessible via the tabs at the top of the page.

1. Overview Analysis
~~~~~~~~~~~~~~~~~~~~

Gene selection and basic visualization interface.

.. figure:: ../_static/overview.png
   :alt: Overview tab showing gene visualization
   :align: center
   :width: 100%

   The Overview tab shows the full gene structure with all transcript
   isoforms and their peptide maps at a glance.

2. Events-Centric Analysis
~~~~~~~~~~~~~~~~~~~~~~~~~~

Focus your analysis on specific splicing events and their peptide
consequences.

**Features:**

* Splicing event selection
* Visualization of event impacts on peptides


.. figure:: ../_static/event-centric_1.png
   :alt: Alternative Splicing Structure diagram
   :align: center
   :width: 100%

   Alternative Splicing Structure showing AS event types (A3SS, RI, SE)
   mapped on the gene structure with genomic coordinates.

.. figure:: ../_static/event-centric_2.png
   :alt: Event selection and peptide comparison
   :align: center
   :width: 100%

   Alternative Splicing Events table with selected event information and
   Peptide Comparison visualization for a selected splicing event,
   highlighting the spliced region and affected peptides across transcript
   pairs.

.. figure:: ../_static/event-centric_3.png
   :alt: Detailed peptide data table
   :align: center
   :width: 100%

   Detailed Peptide Data table listing each peptide with its genomic
   positions, splice source, junction-spanning status, and AS-affected
   category.

.. figure:: ../_static/event-centric_4.png
   :alt: All-events peptide comparison
   :align: center
   :width: 100%

   All Events Peptide Comparison -- a gene-wide view of every splicing
   event (A3, SE, RI) overlaid on the transcript structures with
   AS-affected peptides coloured.

.. figure:: ../_static/event-centric_5.png
   :alt: All-events peptide summary table
   :align: center
   :width: 100%

   All Events Peptide Summary table with a breakdown of peptides, their
   event associations, junction-spanning status, and event-specific
   categories.

3. Isoform-Centric Analysis
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Compare peptides across multiple transcript isoforms with detailed protease
analysis.

**Features:**

* Multi-isoform peptide comparison
* Support for 6 proteases:

  - Trypsin
  - Chymotrypsin
  - AspN
  - LysC
  - LysN
  - GluC


.. figure:: ../_static/isoform-centric_1.png
   :alt: All isoforms visualization with highlighted peptides
   :align: center
   :width: 100%

   All Isoforms Visualization with a highlighted isoform and its peptide
   table showing peptide specificity (unique, shared, universal).

.. figure:: ../_static/isoform-centric_2.png
   :alt: Multi-isoform comparative analysis
   :align: center
   :width: 100%

   Multi-Isoform Comparative Analysis -- select two or more isoforms to
   visualize their peptides and compare them.

.. figure:: ../_static/isoform-centric_3.png
   :alt: Single isoform multi-enzyme coverage
   :align: center
   :width: 100%

   Single Isoform Multi-Enzyme Coverage Analysis comparing peptide
   coverage across multiple enzymes for a selected isoform with coverage
   statistics.

.. figure:: ../_static/isoform-centric_4.png
   :alt: Advanced multi-isoform multi-enzyme matrix
   :align: center
   :width: 100%

   Advanced Multi-Isoform Multi-Enzyme Matrix Analysis combining multiple
   isoforms and enzymes for comprehensive multi-dimensional peptide
   coverage analysis.

.. figure:: ../_static/isoform-centric_5.png
   :alt: Enzyme statistics and peptide specificity
   :align: center
   :width: 100%

   Enzyme Statistics showing coverage percentages, peptide counts, and
   unique peptide counts per isoform-enzyme combination, alongside
   Peptide Specificity Analysis.

Usage Workflow
~~~~~~~~~~~~~~

1. Start with **Overview** to select your gene of interest.
2. Use **Events-Centric** to analyse specific splicing events.
3. Apply **Isoform-Centric** for detailed peptide comparison across
   isoforms.
