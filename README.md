# RAG_LLM
**Project Name:** RAG-QA-PDF

**Description:**
RAG-QA-PDF is a project aimed at performing question answering (QA) on PDF files using the RAG (Retrieval-Augmented Generation) model. The project utilizes LLama-2 chat as a model and incorporates Adjacent Sequence Clustering for chunking the document based on semantic similarity.

**Features:**
- **PDF Question Answering:** Allows users to input PDF files and query them for specific questions related to that pdf.
- **RAG Model:** Utilizes the powerful RAG (Retrieval-Augmented Generation) model for question answering tasks.
- **LLama-2 Chat:** Integrates LLama-2 chat as a model for enhancing question answering capabilities.
- **Adjacent Sequence Clustering:** Implements Adjacent Sequence Clustering to chunk the document based on semantic similarity, enhancing the efficiency of question answering.

**Installation:**
1. Clone the repository:
   ```
   git clone https://github.com/your-username/RAG-QA-PDF.git
   ```

**Usage:**
1. Place your PDF file in the `input` directory.
2. Run the main script:
   ```
   python main.py --pdf_file your_file.pdf
   ```
3. Input your question when prompted.
4. View the generated answer.

**Dependencies:**
- Python 3.x
- PyTorch
- Transformers
- Other dependencies listed in inital cells of Notebook File

**Contributing:**
Contributions are welcome! If you have ideas for improving RAG-QA-PDF or want to report any issues, please open an issue or submit a pull request on GitHub.

**Acknowledgments:**
- LLama-2 Chat Team: Thanks to the LLama-2 Chat team for providing their model for integration into this project.

**Disclaimer:**
This project is intended for educational and personal use only. Users are responsible for ensuring compliance with any applicable laws and regulations when using this software.
