🧬 DNA-Sequence-Analyzer

A **Python-based bioinformatics tool** to analyze DNA sequences. This project includes utilities for:

- ✅ GC Content Calculation  
- 🔁 Reverse Complement Generation  
- 🎯 Motif Finding (e.g., ATG, TATA box)

---

## 📌 Features

- **GC Content Calculator**  
  Calculates the percentage of G and C bases in a given DNA sequence.

- **Reverse Complement Generator**  
  Generates the reverse complement of DNA sequences.

- **Motif Finder**  
  Searches for specific motifs (short DNA subsequences) in input DNA sequences.

---

## 📁 Project Structure

DNA-Sequence-Analyzer/

├── dna_tools.py # Core functions (GC content, reverse complement, motif search)
├── dna_analyzer.py # Command-line interface (CLI)
├── examples/ # Folder with sample FASTA files
└── README.md # This documentation file

⚙️ How to Use

You can run the tool from the command line by providing a DNA sequence and motifs to search for.

python dna_analyzer.py -s ATGCGTACGTAGC -m ATG TATA

🔄 Output

Sequence: ATGCGTACGTAGC
GC Content: 53.85%
Reverse Complement: GCTACGTACGCAT

Motif Results:

ATG found at position(s): 0
TATA not found.

🎓 Educational Use Cases

This project is ideal for:

Students learning bioinformatics and genomics

Teaching fundamental DNA sequence operations

Beginners in Python-based biology projects

🙋 About the Author

Project by Raghav Gupta

🧪 B.Tech Biotechnology | Aspiring Bioinformatician










