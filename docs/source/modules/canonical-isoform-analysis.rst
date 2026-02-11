Canonical Isoform Analysis
==========================

Analyze canonical peptides across isoforms.

The Canonical module provides comprehensive analysis of known peptides across
different transcript isoforms. It is divided into three complementary analysis
approaches, accessible via the tabs at the top of the page.

.. figure:: ../_static/Analysis_control.png
   :alt: Analysis Parameters panel
   :align: center
   :width: 100%

   Analysis Parameters -- select a gene, enzyme, missed-cleavage allowance,
   and intron display mode before updating the view.

1. Overview Analysis
~~~~~~~~~~~~~~~~~~~~

Gene selection and basic visualization interface.

**Features:**

* Gene search and selection
* Basic gene statistics display
* Transcript information visualization
* Quick peptide summary

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
* Event-based peptide mapping
* Visualization of event impacts on peptides
* Comparative analysis across events

.. figure:: ../_static/Events_centric_view_1.png
   :alt: Events-centric view -- AS structure and events table
   :align: center
   :width: 100%

   Alternative Splicing Analysis Overview showing the splicing structure
   and a table of detected splicing events with their types and affected
   transcripts.

.. figure:: ../_static/Events_centric_view_2.png
   :alt: Peptide comparison visualization for a selected event
   :align: center
   :width: 100%

   Peptide Comparison visualization for a selected skipped-exon (SE) event,
   highlighting the spliced region and affected peptides across transcript
   pairs.

.. figure:: ../_static/Events_centric_view_3.png
   :alt: Peptide table for a selected event
   :align: center
   :width: 100%

   Detailed Peptide Data table listing each peptide with its genomic
   positions, splice source, junction-spanning status, and AS-affected
   category.

.. figure:: ../_static/Events_centric_view_4.png
   :alt: All-events peptide comparison
   :align: center
   :width: 100%

   All Events Peptide Comparison -- a genome-wide view of every splicing
   event (A3, SE, RI) overlaid on the transcript structures with
   AS-affected peptides coloured in red.

.. figure:: ../_static/Events_centric_view_5.png
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

* Configurable miscleavage settings (0--2 miscleavages)
* Interactive peptide alignment visualization
* Isoform-specific peptide identification

.. figure:: ../_static/Overview_1.png
   :alt: Isoform-centric peptide visualization
   :align: center
   :width: 100%

   Peptide Visualization showing peptide maps across all transcript
   isoforms for the selected gene, enzyme, and cleavage settings.

Usage Workflow
~~~~~~~~~~~~~~

1. Start with **Overview** to select your gene of interest.
2. Use **Events-Centric** to analyse specific splicing events.
3. Apply **Isoform-Centric** for detailed peptide comparison across
   isoforms.
