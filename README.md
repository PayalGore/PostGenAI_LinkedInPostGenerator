
# PostGenAI: AI-Powered LinkedIn Post Generator

PostGenAI is a cutting-edge tool designed to assist LinkedIn influencers in crafting impactful posts effortlessly, matching their unique writing style. By analyzing a user's historical LinkedIn posts, PostGenAI helps generate new content based on the influencer's past patterns, preferences, and style.



![App Screenshot](https://github.com/PayalGore/PostGenAI_LinkedInPostGenerator/blob/ad2dc9227e1d0733a92615bf6c82746cfbf20000/tool.png)
## Features

- **Topic Extraction:** Automatically identifies key topics from past LinkedIn posts.
- **Customizable Post Generation:** Allows users to specify topic, length, and language for new posts.
- **Few-Shot Learning:** Uses past posts as examples to guide the AI in generating posts that match the user's writing style.
- **User-Friendly Interface:** Built with Streamlit for an intuitive and interactive experience.







## Technical Achitecture

![App Screenshot](https://github.com/PayalGore/PostGenAI_LinkedInPostGenerator/blob/98fcdd122234181d9fadea8201f9343210e8f3b0/ARCHITECTURE.png)


## Tech Stack

**1. Programming Language
Python:** The primary language for backend logic, data processing, and AI integration.

**2. AI and Machine Learning**
- Llama 3.2: The Large Language Model (LLM) used for generating LinkedIn posts.

- Groq API: Provides fast inference for Llama 3.2.

**3. Web Framework
Streamlit:** Used to build the user-friendly web interface.

**4. Data Processing
Pandas:** For data manipulation and analysis (e.g., extracting metadata from JSON files).

**5. Environment Management
python-dotenv:** For managing environment variables (e.g., Groq API key).
## Project Structure

![App Screenshot](https://github.com/PayalGore/PostGenAI_LinkedInPostGenerator/blob/eafd3b6df6f6977a7f39173dbed1a6948541f2fd/Project%20Structure.png)

## Set-up and Installation:

To get started, follow these easy steps:

**1. Obtain an API Key:**

- First, sign up and get an API key from Groq API Console.
- Once you have your key, store it in your .env file by adding the line:

```bash
GROQ_API_KEY=your_api_key_here
```

**2. Install Dependencies:** Clone the repository, navigate to the project folder, and install the required Python dependencies:

```bash
pip install -r requirements.txt
```

**3. Run the Streamlit App:** Start the app by running the following command:

```bash
streamlit run main.py
```

Now you're all set to use PostGenAI!   