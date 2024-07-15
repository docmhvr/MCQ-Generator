# MCQ Generator using OpenAI, LangChain, and Streamlit

## Project Description
MCQ Generator is an application designed to automate the generation of Multiple Choice Questions (MCQs) from provided text inputs. This tool leverages the power of OpenAI for natural language processing and LangChain for managing API interactions, all within a Streamlit web interface.

## Functionalities
- **Text Input**: Users can input any text data.
- **MCQ Generation**: Automatically generate relevant MCQs from the input text using the OpenAI API.
- **Web Interface**: A user-friendly interface built with Streamlit to input text and view generated questions.

## Tech Used
- **Languages**: Python
- **Frameworks and Libraries**:
  - **OpenAI API**: For generating questions.
  - **LangChain**: To manage data and interactions.
  - **Streamlit**: For creating the web application interface.

## How to Run the Project Locally
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/docmhvr/MCQ-Generator.git
   cd MCQ-Generator
   ```

2. **Install Dependencies**:
   Make sure you have Python installed. Then, install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. **Input Data**:
   Ensure your text data is placed in `data.txt`, or upload the specific data from streamlit web interface.

4. **Run the Streamlit App**:
   Start the Streamlit application:
   ```bash
   streamlit run StreamlitApp.py
   ```

5. **Access the Web Interface**:
   Open your browser and navigate to `http://localhost:8501` to interact with the application.

## References
- [Streamlit Documentation](https://docs.streamlit.io/)
- [OpenAI API Documentation](https://beta.openai.com/docs/)
- [LangChain Documentation](https://langchain.readthedocs.io/)