# 📧 Cold Mail Generator  

Cold Mail Generator is a tool that helps service-based companies reach potential clients through personalized cold emails.  

Users can provide the URL of a company’s careers page, and the tool will automatically extract job listings. Based on these listings, it generates tailored cold emails that include relevant portfolio links retrieved from a vector database, ensuring that the outreach is contextually aligned with the company’s needs.  

**Example use case:**  
- A large brand is hiring for a Principal Software Engineer role.  
- Instead of spending resources on recruitment and onboarding, they could benefit from external support.  
- A business development executive at a software services company can use this tool to craft a personalized cold email to highlight their company’s offerings for that exact role.  

![img.png](imgs/img.png)  

## 🏗 Architecture  
![img.png](imgs/architecture.png)  

## ⚙️ Setup  

1. Generate an API key from [Groq Console](https://console.groq.com/keys).  
   Add it to `app/.env` as the value for `GROQ_API_KEY`.  

2. Install dependencies:  
   ```bash
   pip install -r requirements.txt

3. Run the Streamlit application:
    ```bash
   streamlit run app/main.py

