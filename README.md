# Next-Generation-Sequencing-Analysis
NGS Data Analysis: Genomic Read Mapping This repository documents a complete Next-Generation Sequencing (NGS) workflow for processing genomic reads from Dicentrarchus labrax (European Sea Bass). The project covers the pipeline from raw sequence quality control to the extraction of high-quality paired-end alignments.

🛠 Bioinformatics Pipeline
Quality Control: Initial assessment of raw .fastq files using FastQC to evaluate read length, GC content, and base quality.

Trimming & Filtering: Processing reads with Trimmomatic to remove low-quality bases and adapter sequences.

Genome Indexing: Preparing the reference genome (D_labrax_genome.fasta) using BWA (Burrows-Wheeler Aligner).

Alignment: Mapping paired-end reads to the reference genome to generate .sam files.

Post-Processing:

Conversion to .bam (Binary Alignment Map) format.

Filtering for high mapping quality (Q > 30) and properly paired reads using Samtools.

Sorting and indexing for downstream visualization.

💻 Technical Stack
Alignment: BWA (Burrows-Wheeler Aligner)

Processing: Samtools

Quality Control: FastQC, Trimmomatic

Environment: Linux/HPC Cluster

📂 Key Files
Giouv_NGS.docx: Detailed documentation of the commands used and the results obtained for each task.

ERR4973948_1_dg.fastq: Sample paired-end genomic reads.

📊 Summary of Results
Initial Reads: 2,000,000+ total sequences identified in the raw data.

Mapping Precision: Extracted properly paired reads with a mapping quality threshold of 30 to ensure high-confidence genomic analysis.

GC Content: Successfully verified the biological consistency of the library prep (approx. 40-41% GC).

<img width="601" height="284" alt="image" src="https://github.com/user-attachments/assets/231223b7-6621-4e0e-908d-bf362dfa63e8" /> 
<img width="562" height="310" alt="image" src="https://github.com/user-attachments/assets/4b4f5765-b1e6-4302-ad88-4ae51cbcaf89" />
<img width="638" height="355" alt="image" src="https://github.com/user-attachments/assets/c71373a2-3554-42b6-9975-224fea33eb7d" />
<img width="523" height="291" alt="image" src="https://github.com/user-attachments/assets/a8e203f0-7448-45fe-a7c4-a4bc117eca35" />
<img width="764" height="224" alt="image" src="https://github.com/user-attachments/assets/3d7fdc6a-8db4-4c13-8c2a-bebfc486f409" />
<img width="764" height="224" alt="image" src="https://github.com/user-attachments/assets/d0189c53-a4fc-41c9-8cc8-6af40af72787" />
<img width="703" height="234" alt="image" src="https://github.com/user-attachments/assets/30e0d70d-fc71-43b1-ab23-f2c835eb4040" />
<img width="594" height="332" alt="image" src="https://github.com/user-attachments/assets/ec41950b-bc12-4a01-a5ab-8a63fbecee0b" />
<img width="692" height="286" alt="image" src="https://github.com/user-attachments/assets/86f1f7c2-6967-4b90-9bb2-9fe850fe3b69" />
<img width="547" height="305" alt="image" src="https://github.com/user-attachments/assets/609db355-6ee0-4c26-8030-2ebc082e06a5" />
<img width="691" height="290" alt="image" src="https://github.com/user-attachments/assets/b6133cf3-ab88-4f55-aaea-d9206ced10d7" />
![Uploading image.png…]()










