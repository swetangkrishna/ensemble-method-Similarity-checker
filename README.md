📄 Query-Based Document Parsing Evaluation Framework

This repository contains the evaluation of multiple document parsing methods across various documentation sources (PostgreSQL, MySQL, W3Schools) using different query strategies including Regex, TF-IDF, Bag of Words (BoW), and an Ensemble method.

The project includes:
	•	📊 Accuracy comparison charts
	•	🔍 A notebook for testing various query strategies
	•	📐 Architectural PDF for the parsing workflow

📁 Repository Contents

├── test_parsing_tool.ipynb                # Main notebook for document parsing evaluation

├── similarity-checker_parsing-tool-architecture.pdf  # System architecture diagram

├── graph.png                              # Exact/Ensemble/Regex comparison

├── graph1.png                             # TF-IDF and BOW methods added

├── graph2.png                             # Final comparative view across all methods

📌 Evaluation Overview

Document parsing was tested across three major documentation sources:
	•	PostgreSQL
	•	MySQL
	•	W3Schools

Query Techniques Evaluated:
	•	🔹 Exact Keyword Search
	•	🔹 Regex Search
	•	🔹 TF-IDF Vector Matching
	•	🔹 Bag of Words (BoW)
	•	🌟 Ensemble Method (combines all the above for optimal performance)

⸻

📊 Accuracy Comparisons

✅ Basic Query Comparison

🔄 With TF-IDF & BoW Methods

🏁 Final Ensemble & Method Comparison

🧪 How to Run the Evaluation

	1.	Clone this repository
 
	2.	Open test_parsing_tool.ipynb in Jupyter or Colab
 
	3.	Run all cells sequentially to execute and visualize the document parsing evaluations

 🧠 Architecture Diagram

The following workflow outlines the similarity-checker pipeline that powers the ensemble document parsing system:

📄 → Query → 🔍 Match → 🧠 LLM → 🌐 Fetch → 📂 Parse → ✅ Result

📎 Refer to: similarity-checker_parsing-tool-architecture.pdf for a detailed breakdown.
 
