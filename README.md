# Gene Prediction Project - CS123A

## Team Members
- Mahek Kothari (Programmer)
- Aziza Asangarieva (Non-Programmer)
- Amirah Jabr (Non-Programmer)
- Emily Alvarez (Non-Programmer)
- Kevin Arredondo (Non-Programmer)

## Description
This project compares gene prediction tools (GeneMark, Glimmer, Prodigal) with a custom-built HMM model in Python for prokaryotic gene finding.

## How to Run
1. Open `HMM_Gene_Prediction.ipynb` in Google Colab.
2. Ensure Biopython is installed: `!pip install biopython`
3. Run all cells to generate prediction results.
4. Compare predictions with published tools' outputs in `/output`.

## Notes
- FASTA input: `example_genome.fa`
- Gene prediction outputs are compared and printed in the notebook.
"""

with open("README.md", "w") as f:
    f.write(readme_text)
