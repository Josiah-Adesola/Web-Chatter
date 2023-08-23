# Web-Chatter


This Streamlit app allows you to input a website link and generate questions from the content of that website using Langchain and OpenAI's GPT-3.

## Getting Started

Follow these steps to set up and run the app locally.

### Prerequisites

Before you begin, make sure you have the following prerequisites:

- Python 3.x
- pip (Python package manager)
- OpenAI API key

### Installation

1. Clone this repository:

   ```shell
   git clone https://github.com/yourusername/Web-Chatter.git
2. Navigate to the project directory:
   ```shell
   cd Web-Chatter
3. Install the required Python packages:
   ```shell
   pip install -r requirements.txt
   
### Prerequisites
You will need to set your OpenAI API key as an environment variable. You can do this by creating a `.env` file in the project directory and adding your API key as follows:

```OPENAI_API_KEY=your-api-key-here```

### Usage

1. Run the Streamlit app:
   ```shell
   streamlit run app.py
2. Open the app in your web browser by following the link displayed in the terminal.
3. Input a website link into the provided field and click the "Generate Questions" button.
4. The app will retrieve content from the website, process it, and generate questions using OpenAI's GPT-3 model.
5. View the generated questions on the app's interface.

### How it Works

The app follows these steps:
* Imports the necessary libraries and loads the OpenAI API key from the environment.
* Utilizes Langchain to split the data from the website link.
* Creates embeddings from the extracted content.
* Sets up a retriever from a Chroma vector database to retrieve relevant information.
* Constructs a retrieval-based question-answering model.
* Runs a prompt generation after creating the prompt template.
* Finally, builds the user interface with Streamlit.

### Contributors
* Your Name (josiahadesola2018@gmail.com)


   



