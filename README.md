# XYZ Q&A: My Question and Answer System

Hey there! Welcome to the XYZ Q&A project – a creation born out of my passion for developing smart solutions. In this endeavor, I've crafted an end-to-end Question and Answer (Q&A) system using the potent combination of Google Palm Language Model (LLM) and LangChain. This system empowers users to seamlessly ask questions and receive insightful answers through the magic of natural language processing.

## Project Highlights

- **Real CSV File Usage**: I've harnessed the real-world effectiveness of a CSV file filled with frequently asked questions (FAQs). This file is a treasure trove of information, previously handled by dedicated staff to assist users.
  
- **Human Staff Assistance**: The heart of this Q&A system is to alleviate the workload of our human staff. Now, users can get quick answers without waiting for manual responses.

- **LangChain + Google Palm**: For the linguistic wizardry, I've seamlessly integrated LangChain for natural language processing and the Google Palm LLM for generating precise and context-aware answers.

- **Streamlit UI**: A user-friendly web interface using Streamlit makes the interaction smooth and intuitive. Users can simply ask their questions and get answers at their fingertips.

- **Huggingface Instructor Embeddings**: Leveraging Huggingface instructor embeddings, I've ensured that the text representations are robust and reflective of the richness of the content.

- **FAISS Vector Database**: To make data retrieval swift and efficient, I've employed FAISS for creating and managing a vector database.

## Learning Journey

This project has been an incredible learning journey for me. Here's a glimpse of the skills I've honed:

- **Q&A System Development**: Building a Q&A system from scratch has provided insights into the intricacies of handling user queries effectively.

- **UI Development with Streamlit**: Crafting a user interface using Streamlit has been an engaging process, adding a touch of simplicity to the system.

- **Text Embeddings with Huggingface**: Learning to use Huggingface instructor embeddings has enhanced my understanding of representing text in a meaningful way.

- **Vector Database Management with FAISS**: Managing data efficiently using FAISS has been a crucial aspect of ensuring quick and accurate responses.

## Installation – Let's Get Started

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/yourusername/xyz_qa.git
    ```

2. **Navigate to the Project Directory:**
    ```bash
    cd xyz_qa
    ```

3. **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Acquire a Google API Key:**
   - Visit [makersuite.google.com](https://makersuite.google.com/) to obtain an API key.
   - Place the key in the `.env` file:
        ```env
        GOOGLE_API_KEY="your_api_key_here"
        ```

## Usage – Dive In!

1. **Run the Streamlit App:**
    ```bash
    streamlit run main.py
    ```

2. **Explore the Interface:**
    - To create a knowledgebase of FAQs, click the "Create Knowledgebase" button. This may take a moment, so grab a coffee.
    - Once the knowledge base is set, find the `faiss_index` directory in your project folder.
    - Now, you're ready to engage! Type your questions in the "Question" box and hit Enter.

## Sample Questions – Test the Waters

- Does the platform offer internships, and what are the payment options available?
- Is there a dedicated course for learning Python programming?
- What sets apart Machine Learning from Artificial Intelligence?
- I use a Linux system. Can I access the platform's resources seamlessly?
- How do I reset my password on the platform?

## Project Structure – Behind the Scenes

- **main.py:** The heart of the application, where the Streamlit magic happens.
- **langchain_helper.py:** My creation housing all the LangChain-related code.
- **requirements.txt:** A guide for installing the necessary Python packages.
- **.env:** The secret keeper – holds your Google API key.
