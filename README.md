# ResumeParser

ResumeParser is a Python script that facilitates the extraction of key information from resumes. It uses a combination of regular expressions, PDF text extraction, and natural language processing to parse resumes and retrieve details such as names, contact information, skills, education, and more.


## Libraries Used

### 1. `re` (Regular Expressions)

The `re` library is a built-in Python module used for working with regular expressions. In ResumeAnalyzer, it is employed to search for and extract patterns such as phone numbers and email addresses from the resume text.

### 2. `pdfminer` (PDF Text Extraction)

`pdfminer` is a PDF parsing library used for extracting text from PDF documents. In ResumeAnalyzer, it ensures accurate text extraction from resume PDFs, allowing for efficient analysis of the document content.

### 3. `spacy` (Natural Language Processing)

`spacy` is a popular natural language processing (NLP) library. In this project, it is utilized for named entity recognition (NER), enhancing the extraction of names from resumes.

### 4. `spacy.matcher` (spaCy Matcher)

The `spacy.matcher` module is part of the spaCy library and is used to create match patterns for identifying specific entities in text. In ResumeAnalyzer, the Matcher is employed for extracting names based on defined patterns.


## Usage

1. Navigate to the project directory:

   ```bash
   cd ResumeAnalyzer

2. Run the script with a resume file:

   ```bash
   python main.py path/to/resume.pdf

Replace path/to/resume.pdf with the actual path to the resume PDF file you want to analyze.

## Features

- **Information Extraction:** Extracts and displays candidate information from resumes, including names, contact information, email addresses, skills, and education details.

- **Customizable Skills List:** Allows for a customizable skills list, enabling tailored extraction based on specific requirements.

- **PDF Text Extraction:** Utilizes PDFMiner for accurate text extraction from PDF documents, ensuring reliable parsing of resume content.

- **Named Entity Recognition with spaCy:** Incorporates spaCy for named entity recognition, enhancing the extraction of names and improving overall accuracy.

## Contributing

If you'd like to contribute to ResumeAnalyzer, we welcome your contributions! Please follow these steps:

1. **Fork the Repository:** Click the "Fork" button on the top right of this repository to create your own copy.

2. **Create a New Branch:** Create a new branch for your feature or bug fix. For example:
   ```bash
   git checkout -b feature/my-feature

3. Commit Your Changes: Make your changes, commit them with a descriptive message:

   ```bash
   git commit -m 'Add new feature'

4. Push to the Branch: Push your changes to your forked repository:

   ```bash
   git push origin feature/my-feature

5. Submit a Pull Request: Open a pull request on the original repository. Provide a detailed description of your changes.

   ```bash
   cd ResumeAnalyzer


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

Copy and paste this content into your README.md file in your GitHub repository. Customize the licensing details in the [LICENSE](LICENSE) file according to your project's requirements.








