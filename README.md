# Microbial Contamination Workflow

This is a computational workflow for detecting coordinates of microbial-like sequences in eukaryotic reference genomes. The workflow accepts a reference genome in FASTA-format and outputs coordinates of microbial-like regions in BED-format. The workflow builds a Bowtie2 index of the eukaryotic reference genome and aligns pre-computed microbial GTDB v.207 (https://gtdb.ecogenomic.org/) pseudo-reads to the reference, then custom scripts are used for detection of the positions of covered regions and quantification of most abundant microbial contaminants.

The workflow was developed by Nikolay Oskolkov, Lund University, Sweden, within the NBIS SciLifeLab long-term support project, PI Tom van der Valk, Centre for Palaeogenetics, Stockholm, Sweden.

If you use the workflow for your research, please cite our manuscript:

Nikolay Oskolkov, Chenyu Jin, Samantha López Clinton, Flore Wijnands, Ernst Johnson, Benjamin Guinet, Verena Kutschera, Cormac Kinsella, Peter D. Heintzman and Tom van der Valk, Disinfecting eukaryotic reference genomes to improve taxonomic inference from environmental ancient metagenomic data, manuscript in preparation

Questions regarding the dataset should be sent to nikolay.oskolkov@scilifelab.se

The pre-computed microbial pseudo-reads are available at the SciLifeLab Figshare https://doi.org/10.17044/scilifelab.28491956
