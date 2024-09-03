RNA -SEQ

RNA-Seq is a powerful tool transforming transcriptome study. It provides scientists with detailed insights into unseen changes in diseases, drug responses, environmental impacts, and various research scenarios. This sensitive method quantifies **gene expression**, revealing known and novel features in one test, identifying **transcript isoforms**, gene fusions, and **single nucleotide variants** without requiring prior knowledge. RNA sequencing (RNA-seq) measures the transcription of each gene in a biological sample (i.e. a group of cells or a single cell.)

MOLECULAR BIOLOGY AND WORKFLOW OF RNA SEQ –

Initially, RNA-seq utilized Sanger sequencing, which was groundbreaking but had low output and high costs. The introduction of **NGS technology** significantly enhanced RNA-seq's capabilities. The RNA-seq process includes **RNA extraction**, **reverse transcription to cDNA**, **adapter ligation**, **amplification**, and **sequencing**. Single-end sequencing is faster and more affordable, while paired-end sequencing offers better data reconstruction post-sequencing.

RNA-seq data analysis involves three key steps:
Primary Analysis: Performed on the sequencer, this step includes base calling and converting raw sequencing data (BCL files) into **FASTQ files**.
Secondary Analysis:
Mapping: Reads are aligned to a reference genome or transcriptome using tools like **STAR**, or de novo assembled if no reference exists, using tools like Trinity.
Quality Control: Tools like **FASTQC** check for biases, errors, and other quality issues in the sequencing data.
Transcript Quantification: Reads are mapped to specific transcripts for expression quantification using tools like **RSEM or Salmon**.
Tertiary Analysis: Involves downstream analyses such as differential expression, variant detection, and functional annotation using databases like KEGG or Gene Ontology.

ROLE OF RNA-SEQ IN CANCER RESEARCH-

RNA sequencing plays a crucial role in cancer research, primarily through differential gene expression analysis which helps identify genes with varying activity across different species, tissues, and conditions. This aids in uncovering potential cancer biomarkers and molecular mechanisms, such as gene fusions which are significant in oncogenesis and serve as both diagnostic and therapeutic targets.

A case study of application of RNA SEQ in cancer research are the Gene fusions in clinical samples which are primarily detected by RNA-CaptureSeq. It has been reported that the **NUP98-PHF23 fusion gene** is likely to be a novel therapeutic target in acute myeloid leukemia (AML).

Conclusion-

RNA-seq has revolutionized transcriptome studies, offering unparalleled insight into gene expression and molecular processes. This technique quantifies expression with high sensitivity, discovers new transcript isoforms, and detects gene fusions and single nucleotide variants in a single experiment. The shift from Sanger to NGS has greatly enhanced its capabilities, making it indispensable in cancer research. RNA-seq reveals intricate cancer molecular landscapes, pinpoints critical biomarkers and therapeutic targets, and is fundamental to understanding oncogenesis, tailoring treatments, and improving patient outcomes. Its significance is in uncovering complex gene expression patterns and molecular changes, which are crucial in the ongoing fight against cancer.
