### **About**

Lingmin Zhan

Master’s Degree

Research interests: Deep Learning, Multi-omics, Drug Discovery



Algorithm Engineer at the Hangzhou Institute of Medicine, Chinese Academy of Sciences. Graduated from Shanxi Agricultural University with a major in Bioinformatics, where the research focused on predicting transcriptional effects induced by gene or drug perturbations. Current work primarily involves building a tumor vaccine discovery pipeline and developing NGS variant detection algorithms.


### **Projects**

**1、Neovar**

A deep network that fuses “spatial visual features” with “biological semantic information.” First, a stack of Conv2D convolutional layers is used to extract local features from Pileup Tensors. The core breakthrough of this model lies in the DNA–RNA Cross-Attention mechanism. Through a two-stage attention interaction, the model, much like a human expert, automatically seeks supporting evidence from the RNA modality upon detecting DNA variant signals. In addition, the model innovatively incorporates the Evo2 genomic foundation model developed by the Stanford University team. Evo2 endows the model with an “evolutionary intuition,” enabling it to understand the genomic context grammar within a 221 bp window. This multi-dimensional modeling—from local pixels to global semantics—is the key technical factor that allows it to significantly outperform existing state-of-the-art approaches.



**1.1 EnsembalVar**

To address the core challenge of “label noise,” we constructed a consensus-based “silver standard” labeling pipeline. Rather than relying on a single algorithm, we adopted an ensemble strategy that deeply integrates Google’s DeepSomatic, the Broad Institute’s Mutect2, and Illumina’s Strelka2. In this way, we are able to cross-validate DNA variant calls using transcriptomic signals from RNA-seq. This multi-omics orthogonal validation not only “rescues” true variants in low-depth regions but also effectively filters out systematic false positives caused by FFPE artifacts or PCR amplification, providing high-quality Ground Truth for downstream model training.



**2、NeoVaxFinder**

A lightweight, highly available, end-to-end neoantigen prediction pipeline. Following the main workflow of “data input – variant identification – neoantigen prediction – hierarchical rule-based filtering,” it takes common sequencing data as input and outputs candidate epitopes suitable for vaccine design. With a modular architecture, additional processing modules or evaluation frameworks can be easily integrated in the future.



**2.1 VCF2PEPTIDES**

VCF-FASTA is an integrated bioinformatics pipeline designed to systematically extract protein-level genetic variation information from Variant Call Format (VCF) files and generate corresponding peptide sequences.



**3、TranscriptionNet**

A deep learning model designed to systematically predict, on a genome-wide scale, the transcriptional consequences induced by different gene perturbations. It leverages transcriptional profiling data from the L1000 project—covering thousands of genes across three perturbation types (RNAi, CRISPR, and overexpression)—and is trained in conjunction with multi-layered functional gene networks.



### **Publication**

(1) A genome-scale deep learning model to predict gene expression changes of genetic perturbations from multiplex biological networks. Briefings in Bioinformatics. (First author)

(2) A Natural Glucan from Black Bean Inhibits Cancer Cell Proliferation via PI3K-Akt and MAPK Pathway. Molecules. (Second author)

(3) Specific gene module pair-based target identification and drug discovery. Frontiers in Pharmacology. (Second author)


### **Contact**

zhanlm52@163.com

