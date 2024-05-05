Project Overview: Exploration of Textual Similarities in Network Communication
Aim of the Project
This research project aims to explore textual similarities and word patterns within network communications, focusing on two distinct datasets: the Enron email corpus and a dataset of scientific paper citations. The project investigates whether individuals within these networks exhibit linguistic convergence or divergence based on their communication interactions and content.

Technologies Used
Python & NetworkX: Utilized for graph construction and network analysis, particularly for handling large datasets and performing complex network manipulations.
n-gram Vectorization: Used to transform text data into vector formats, allowing for the analysis of textual similarities through unigrams to trigrams.
Cosine Similarity Measures: Applied to quantify the degree of similarity between different text vectors, providing a basis for creating networks of textual similarity.
Jaccard Index: Used for statistical analysis to measure the overlap between networks of communication and textual similarities, helping to understand the degree of linguistic convergence.
Spacy: Advanced natural language processing toolkit used for semantic analysis, including lemmatization and synonym detection, which aids in understanding semantic correlations in text data.
Project Workflow
Data Preprocessing:
Emails and scientific papers were cleaned and standardized using functions from Kaggle and GitHub sources to ensure data consistency.
Email addresses were separated, and non-essential information was removed to focus on relevant textual content.
Graph Construction:
Constructed two types of graphs for each dataset: a communication graph (based on direct interactions) and a textual similarity graph (based on cosine similarity of text content).
Network Analysis:
Analyzed the constructed graphs to identify and visualize structural patterns, interaction dynamics, and clusters of similar textual content.
Overlap Calculation:
Employed the Jaccard Index to quantify the overlap between the networks of communication and the networks of textual similarities, providing insights into linguistic convergence.
Results and Evaluation:
Results were interpreted to understand the extent of textual similarities and their implications on network communication patterns. The findings indicated varying levels of linguistic convergence across different types of networks.
Allocation of Project Tasks
Mingwei Shi (Chair):
Leadership and project coordination.
Writing significant portions of the report, including the abstract, introduction, and methodology.
Implementing email graph modeling and coordinating communications with faculty.
Juliette van Marken (Recorder):
Responsible for the literature review, specifically sections 2.1 and 2.2, and the future work section.
Managed documentation and meeting minutes.
Akash Garg (Accountant):
Handled data visualization and analysis.
Wrote sections on related works, discussion, and clustering analysis.
Georgios Kanellopoulos (Ambassador):
Reviewed and contributed to the methodology and implementation sections.
Engaged in peer review summaries and integration of feedback into the final report.
Xinyi Li (Monitor):
Focused on enhancing the interpretation of results and methodological consistency.
Contributed to dataset construction and comparative analysis sections.
Indrajeet Kumar (Verifier):
Developed the graph construction methods for the citation dataset.
Contributed to hypothesis formulation and verification in the introduction and conclusion sections.
