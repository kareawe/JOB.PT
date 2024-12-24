# JOB.PT

**Project Description:**

JOB.PT is a web application designed to help job seekers by providing curated job opportunities based on their skills and career interests. The platform crawls academic papers and news articles to gather relevant information and uses OpenAI’s GPT-4 mini model to generate precise job-related answers. The application displays job titles, key required skills, and links to three job listing websites for each job position.

**Key Features:**

- **Data Crawling:** The platform crawls academic papers and news articles to gather insights into various job roles and required skills.
- **AI-Powered Responses:** OpenAI’s GPT-4 mini model is used with prompt engineering and Chain of Thought (CoT) reasoning to generate accurate job information and skills.
- **Job Listings:** The application displays a list of jobs along with the top three job posting sites for each role.
- **User-Friendly Interface:** Built with Streamlit, the site provides an intuitive and interactive way to explore job opportunities and skills.

**Technologies Used:**

- Web Crawling: Python (BeautifulSoup, Requests)
- Backend: Python (Streamlit)
- AI Integration: OpenAI GPT-4 mini model
- Hosting: [Platform Used, e.g., Heroku, Streamlit Sharing, etc.]

**How to Use:**

1. Visit the site at [URL].
2. Enter the job role or skill you're interested in.
3. The platform will retrieve relevant information about the job, required skills, and direct links to job listings.
4. Explore the curated job opportunities with detailed insights into each role.

**Important:**

- **API Key Required:** To run the application locally or on a server, you must provide a valid OpenAI API key. Without it, the application will throw an error.
  
  - Set up your API key by adding it to your environment variables or directly in the code (though environment variables are recommended for security reasons).

**Installation:**

1. Clone the repository:
   ```bash
   git clone <repository-url>
Install dependencies:


pip install -r requirements.txt
Set up your environment variables for the OpenAI API key. You can do this by creating a .env file in the root directory and adding:


OPENAI_API_KEY=your_api_key_here
Run the application:


streamlit run app.py
Contributors:

[김민재]
[양지훈]
[최은렬]
[박건균]
[이민성]


Just replace the placeholder `[URL]`, `[repository-url]`, and contributor names with your specific details. Let me know if you need any further adjustments!





