📄 PDF Comparison Tool

A Python-based script to compare two PDF files and check if they are identical or different.
The tool performs binary comparison, text content comparison, and metadata comparison to ensure accurate results.

🚀 Features

🔑 Binary Comparison – Uses MD5 hashing to check if PDFs are identical at the binary level.

📝 Text Content Comparison – Extracts and compares text using pdfplumber, highlights differences with difflib.

📑 Metadata Comparison – Extracts metadata (author, title, creation date, etc.) using PyPDF2.

📊 Detailed Report – Generates a summary of differences found.

⏱️ Time Tracking – Displays time taken for the entire comparison process.

🛠️ Tools & Libraries

hashlib → Generates MD5 hashes for binary comparison.

PyPDF2 → Extracts and compares metadata from PDFs.

pdfplumber → Extracts text for content comparison.

difflib → Highlights differences in human-readable format.

📂 Project Workflow

Input PDFs → User provides two PDF files.

Binary Comparison → MD5 hash values compared.

Text Comparison → Extracted text compared line by line.

Metadata Comparison → Author, title, and creation date checked.

Report Generation → Comprehensive report with differences & summary.

⚙️ Installation

Clone the repository:

git clone https://github.com/your-username/pdf-comparison-tool.git
cd pdf-comparison-tool


Install dependencies:

pip install -r requirements.txt


Run the script:

python compare_pdfs.py file1.pdf file2.pdf

📜 Requirements

Python 3.10+

PyPDF2

pdfplumber

difflib (built-in with Python)

hashlib (built-in with Python)

Sample requirements.txt:

PyPDF2==3.0.1
pdfplumber==0.10.3

📌 Future Improvements

🖼️ Image-Based Comparison (for PDFs with images/graphics).

🖥️ GUI Integration (simple interface for non-technical users).

⚡ Speed Optimization (parallel processing for large PDFs).

👨‍💻 Author

Sourav Paul
📧 Email: souravpaul043@gmail.com
