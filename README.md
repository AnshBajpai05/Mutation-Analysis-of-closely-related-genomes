# 🧬 COVID-19 Mutation Analysis

This project analyzes mutations in different SARS-CoV-2 variants by comparing their genomes to the reference sequence (GenBank: **MN908947.3**). It combines **mutation detection** with **Multiple Sequence Alignment (MSA)** to map mutations onto gene/protein regions and study evolutionary patterns across variants.

---

## 🔍 Features
- Parse and extract **gene/protein annotations** from the reference genome.  
- Identify mutations (SNPs, insertions, deletions) in variant genomes.  
- Map mutations to **specific protein-coding regions**.  
- Perform **Multiple Sequence Alignment (MSA)** to compare multiple variants at once.  
- Visualize mutation hotspots and conserved regions across variants.  

---

## 📂 Dataset
- **Reference Genome:** MN908947.3 (GenBank).  
- **Variant Genomes:** Complete SARS-CoV-2 genomes in FASTA format.  

---

## 🛠️ Tech Stack
- **Python** – core analysis  
- **Biopython** – genome parsing, alignments (AlignIO)  
- **MAFFT / Clustal Omega** – Multiple Sequence Alignment  
- **Pandas / NumPy** – mutation data handling  
- **Matplotlib / Plotly** – visualization of genomes & alignments  

---

## 🚀 Workflow
1. **Reference Parsing** – Extract annotated genes/proteins from GenBank.  
2. **MSA** – Align variant genomes with MAFFT/Clustal Omega.  
3. **Mutation Detection** – Identify SNPs, insertions, deletions relative to reference.  
4. **Mapping** – Associate mutations with specific genes/protein regions.  
5. **Visualization** – Generate genome maps, alignment plots, and mutation summaries.  

---

## 📊 Example Outputs
- **Mutation tables** (variant vs reference).  
- **Alignment views** showing conserved and mutated regions.  
- **Genome plots** highlighting mutation hotspots.  
- **Summary reports** of affected proteins across variants.  

---

## 📌 Applications
- Tracking **evolutionary changes** in SARS-CoV-2.  
- Identifying **conserved regions** for drug/vaccine targets.  
- Supporting **bioinformatics & genomic epidemiology research**.  

---

## 📖 References
- NCBI GenBank: [MN908947.3](https://www.ncbi.nlm.nih.gov/nuccore/MN908947.3)  
- Biopython Documentation: https://biopython.org/wiki/Documentation  
- MAFFT: https://mafft.cbrc.jp/alignment/software/  
