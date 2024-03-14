## LegalLexa: Your AI Legal Companion

LegalLexa is an advanced Legal Language Model (LLM) built on the Google Gemini API and implemented by LangChain. It is designed to streamline legal research and analysis by parsing multiple PDF files, particularly focusing on the Constitution of India. 

### Features:
- **Google Gemini API**: LegalLexa leverages the powerful capabilities of the Google Gemini API to provide accurate and insightful answers to legal queries.
- **LangChain Implementation**: LangChain's expertise in natural language processing and AI technologies ensures the robustness and efficiency of LegalLexa.
- **PDF Parsing**: LegalLexa extracts text from multiple PDF files, storing it in a vector database for efficient retrieval and analysis.
- **Answer Generation**: The model is fine-tuned to provide precise answers to a wide range of questions about the Indian Constitution. It is trained to indicate when an answer is not found or not in context, ensuring reliability.
- **Streamlit Integration**: LegalLexa is seamlessly integrated into Streamlit, offering a user-friendly interface with beautiful UI design for a smooth and enjoyable user experience.
- **Useful for Students and Professionals**: LegalLexa is a valuable tool for students, researchers, and legal professionals alike, providing quick and accurate insights into constitutional matters.

### How It Works:
1. **PDF Text Extraction**: LegalLexa extracts text from each page of the PDF files using RecursiveCharacterTextSplitter.
2. **Vector Database Creation**: The extracted text is converted into vectors using GoogleGenerativeAIEmbeddings and stored in a FAISS database.
3. **Question Answering**: LegalLexa is capable of answering various questions about the Indian Constitution, utilizing its trained knowledge base.
4. **User Interface**: The user interacts with LegalLexa through the intuitive Streamlit interface, receiving prompt and accurate responses to their queries.

### Temperature Setting:
LegalLexa operates with a temperature of 0.5, ensuring a balanced and reliable response generation process.

LegalLexa is not just a legal assistant, but a trusted companion for navigating the complexities of Indian constitutional law. Whether you're a student, researcher, or legal professional, LegalLexa is here to simplify your legal research journey.
