# Large_Protein_Families
Bioinformatic tool for grouping peptide sequences of large protein families

Contents:
-Folders
  - Alignment Files: fasta files of RRs aligned by hmmAlign or MAFFT (note hhmAlign alignments are used in dimensional reductions)
  - Alphaproteobacteria_subcluser - Hypothesis testing for alphaproteobacteria RRs
    - CDS: coding sequences of alphaproteobacteria RRs using different models
      - Genomes_CDS: protein coding sequences of samples genomes
      - HyPhy Results: output from HyPhy
      - iqree_Results: output from iqtree
  - cognateHK_files: using the tool to search for cognate kinases (note that this data was not used in the paper, but could be useful for others)
  - Figures: Static figures used in this paper
  - GenomeDBs: All genomes for different taxanomic ranks available in MISTDB
  - SampledGenomes: All sampled genomes used in this study (be careful, theses can be overwritten)
  - SampledTCS: All sampled TCS with corresponding DB number from sampled genomes used in this study (be careful, theses can be overwritten)
  - Source_Files: source hmm files
  - Supplementary_Data_Files: supplementary data files for Garber et al.
      - Supplemental Data 1: Results log from DataMonkey version of HyPhy’s absREL and MEME. Contents include original fasta, log.txt, result.json, results tree, results table (if applicable), and results summary figure.
      - Supplemental Data 2: Results log and output from ColabFold for PP_1066, PP_1066* (PP_1066_mut)  and PP3551* (PP_3551_mut).
      - Supplemental Data 3: Results output from motif calling with orthologous RRs. Each tab contains data for each ortholog.
      - Supplemental Data 4: Raw output from DAP-seq peak calling.
  - subclusterRR_files: parent and recombined REC domains in alphaproteobacteria, gammproteobacteria, and proteobacteria
  - TSNEoutput: static TSNE output used to find alphaproteobacteria subscluster
- jupyter notebooks
  - cognateHKs.ipynb: code to find samples cognate HKs to sampled RRs from the sampled TCS
  - Genome_TCS_curation.ipynb: code to randomly sample genomes from MISTDB
  - Search_Alphaproteobacteria.ipynb: code to search for subcluster and code for hypothesis testing in alphaproteobacteria subcluster
  - Subcluster.ipynb: parent and recombined REC domains in alphaproteobacteria, gammproteobacteria, and proteobacteria
  - Summary of Data Collection.ipynb: code to summarize the data collected for the paper
  - TCS_playground_formalized_OFCFigures.ipynb: code to generate dimensionally reduced and cluster REC domains (used to generate figures for the paper)
  - TCS_playground_Formalized.ipynb: redundant code to generate dimensionally reduced and cluster REC domains (not used to generate figures for the paper)
