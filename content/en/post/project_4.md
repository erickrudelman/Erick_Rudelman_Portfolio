---
date: 2023-08-08T10:58:08-04:00
description: "Count the nucleotide in you DNA and more!"
featured_image: "/images/dna.jpg"
tags: []
title: "Project IV: DNA Nucleotide Count Web App"
---

The **DNA Nucleotide Count and Analysis Web App** is designed as a versatile tool for analyzing DNA sequences, offering functions to count nucleotides, compute reverse complements, find open reading frames (ORFs), and translate DNA into protein sequences. This Streamlit app empowers users to explore DNA-related insights and conduct basic genetic analyses.

The app workflow and its various features can be outlined as follows:

The app starts by displaying an image of a DNA logo and its title, introducing its purpose and functionality. Users can input a DNA sequence composed of adenine (A), cytosine (C), guanine (G), and thymine (T) nucleotides. The sequence's validity is checked using regular expressions. The app calculates and displays the count of each nucleotide (A, T, G, C) using a dictionary. The dictionary containing nucleotide counts is displayed. The counts of individual nucleotides are presented in text format.

A DataFrame is generated from the nucleotide count dictionary and displayed in tabular form. The app creates a bar chart using Altair to visualize nucleotide counts. Each nucleotide is represented by a unique color. Users can compute the reverse complement of the input DNA sequence. The app identifies and displays open reading frames (ORFs) within the input DNA sequence.

The app translates the input DNA sequence into a protein sequence using a codon table. Users can save analysis results to a text file, including nucleotide counts and protein sequence. A download button enables downloading the saved results.

In addition to core Python libraries, the app also utilizes libraries such as `pandas`, `streamlit`, `re` for regular expressions, `altair` for visualization, and `PIL` (Pillow) for image display.

In summary, the DNA Nucleotide Count and Analysis Web App provides a user-friendly platform for exploring DNA sequences, performing basic analyses, and gaining insights into genetic information. It caters to individuals interested in molecular biology, genetics, and bioinformatics, offering a convenient and interactive tool for quick DNA analysis.

---

[Link to GitHub Repository](https://github.com/rudicr/data_science_projects/blob/Data-Science-Projects/dna-app.py)
