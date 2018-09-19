# TriplexRNA
A multi-organism database of cooperating microRNAs and their mutual targets.

The triplexRNA contains predicted RNA *triplexes* composed of two cooperatively acting microRNAs (miRNAs) and their mutual target mRNA.  
MiRNA cooperativity has been experimentally characterised by [Sætrom *et al.* (2007)](https://doi.org/10.1093/nar/gkm133]) as a strong regulatory pattern, whose formation inhibits the transcription of a target gene. The phenomenon is explained in detail by [Schmitz *et al.* (2014)](https://doi.org/10.1093/nar/gku465), and illustrated below. Here, a target mRNA can be repressed by either a single miRNA (right), or by a pair of cooperating miRNAs (left). While in the first case miRNA and target form a duplex structure, the second case leads to the formation of a RNA triplex.  
Even if the expression of the cooperating miRNAs is only mildly up-regulated, an enhanced repressive effect can be observed as compared to the cases where single miRNAs are highly up-regulated.
<p align="center">
<img align="center" src="assets/img/triplex_duplex_patterns.png" width="600px" alt="RNA triplex and RNA duplex regulatory patterns" valign="top"/>
</p>

## Data
The TriplexRNA contains predicted RNA triplexes for Human and Mouse. Each triplex is characterized by
- Statistics (Gibbs free energy, energy gain, seed distance, length)
- Dot-bracket notation assembly
- Graphical illustration of its simulated econdary structure
- Graphical illustration of its predicted equilibrium concentration

## Metabolic pathways
Since the presence of miRNAs can be correlated with the progression of known diseases, the TriplexRNA provides an interface for the navigation of known metabolic [KEGG](https://doi.org/10.1093/nar/28.1.27) pathways, within the framework of cooperative miRNA targets.  
This feature allows researchers to identify and test disease-specific miRNAs that could be used as diagnostic and prognostic biomarkers.  
The metabolic pathway function is illustrated below. Here, mutual targets of the selected miRNA pair *hsa-miR-374a* and *hsa-miR-590-3p* within the KEGG disease pathway *Asthma* are highlighted in yellow.
<p align="center">
<img align="center" src="assets/img/metabolic_pathway_integration.png" width="600px" alt="Targets of selected cooperative miRNAs are interactively highlighted within the specified KEGG metabolic pathway" valign="top"/>
</p>

