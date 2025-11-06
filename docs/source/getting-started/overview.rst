Overview
========

IsoPepTracker Architecture
--------------------------

IsoPepTracker is organized into four main modules, each designed for specific aspects of peptide and alternative splicing analysis:

Module Overview
---------------

1. **Canonical Module**
   
   Provides comprehensive analysis of known peptides across different transcript isoforms with three analysis approaches:
   
   * Overview Analysis
   * Events-Centric Analysis  
   * Isoform-Centric Analysis

2. **Novel Module**
   
   Identifies and characterizes novel peptides that arise from alternative splicing events using BLASTP annotation.

3. **Peptide Search Module**
   
   Offers powerful search capabilities across the entire IsoPepTracker database.

4. **Alternative Splicing Analysis Module**
   
   Provides visualization and analysis of five types of alternative splicing events.

Key Technologies
----------------

IsoPepTracker integrates several important bioinformatics tools:

* **rMATS**: For alternative splicing event detection
* **SplAdder**: For splicing analysis compatibility
* **BLASTP**: For functional annotation of novel peptides
* **Multiple Proteases**: Support for Trypsin, Chymotrypsin, AspN, LysC, LysN, and GluC

Workflow Philosophy
-------------------

The tool is designed with a modular workflow approach:

1. **Data Input**: Support for various input formats
2. **Analysis Selection**: Choose appropriate module based on research goals
3. **Parameter Configuration**: Customize analysis parameters
4. **Results Visualization**: Interactive visualization of results
5. **Data Export**: Export results for further analysis

For detailed information about each module, proceed to the :doc:`../modules/canonical` section.