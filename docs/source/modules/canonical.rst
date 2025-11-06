Canonical Module
================

The Canonical module provides comprehensive analysis of known peptides across different transcript isoforms. This module is divided into three complementary analysis approaches.

Module Overview
---------------

The Canonical module enables researchers to analyze canonical peptides through three distinct yet complementary approaches, allowing for comprehensive isoform-level peptide analysis.

Analysis Approaches
-------------------

1. Overview Analysis
~~~~~~~~~~~~~~~~~~~~

Gene selection and basic visualization interface.

**Features:**

* Gene search and selection
* Basic gene statistics display
* Transcript information visualization
* Quick peptide summary

2. Events-Centric Analysis
~~~~~~~~~~~~~~~~~~~~~~~~~~

Focus your analysis on specific splicing events and their peptide consequences.

**Features:**

* Splicing event selection
* Event-based peptide mapping
* Visualization of event impacts on peptides
* Comparative analysis across events

3. Isoform-Centric Analysis
~~~~~~~~~~~~~~~~~~~~~~~~~~~

Compare peptides across multiple transcript isoforms with detailed protease analysis.

**Features:**

* Multi-isoform peptide comparison
* Support for 6 proteases:

  * Trypsin
  * Chymotrypsin
  * AspN
  * LysC
  * LysN
  * GluC

* Configurable miscleavage settings (0-2 miscleavages)
* Interactive peptide alignment visualization
* Isoform-specific peptide identification

Usage Workflow
--------------

.. tip::
   **Recommended Workflow**

   1. Start with **Overview** to select your gene of interest
   2. Use **Events-Centric** to analyze specific splicing events
   3. Apply **Isoform-Centric** for detailed peptide comparison across isoforms

Input Requirements
------------------

The Canonical module accepts:

* Gene names or identifiers
* Transcript IDs
* Genomic coordinates

Output
------

The module generates:

* Peptide comparison visualizations
* Isoform-specific peptide lists
* Protease cleavage patterns
* Exportable data tables

For information about novel peptide identification, see :doc:`novel`.