** Text Similarity API with FastAPI **

A REST API built with FastAPI that measures similarity between two text inputs. Using TF-IDF vectorization and cosine similarity, it returns a score that reflects how closely the texts are related.

📌**Objective**
Develop an API that allows users to send two text inputs and receive an instant similarity score.

🚀 **Key Highlights**

🧠 TF-IDF + Cosine Similarity: Computes similarity between two text strings.

🚀 FastAPI Backend: Provides a high-performance REST API endpoint.

🖥 JSON Response: Clean output, easy to integrate with other systems.

🔧 Reusable Service: Can be extended to chatbots, search engines, or recommendation systems.

📊 **Tech Stack**

Python

FastAPI

Scikit-learn (TF-IDF Vectorizer, Cosine Similarity)

Uvicorn (server)

📂 Dataset

No external dataset required.

Input text comes from the user (via API request).

🧪 Example Usage
Request:

POST /similarity  
{  
  "text1": "I love machine learning",  
  "text2": "Machine learning is amazing"  
}  


Response:

{  
  "similarity_score": 0.87  
}  


📂 Project Structure

├── main.py                # FastAPI app with similarity endpoint  
├── requirements.txt       # Dependencies  
└── README.md              # Project documentation  


⚡ How to Run the Project

Clone the repository or download the ZIP file.

Install dependencies: pip install -r requirements.txt

Start the API server: uvicorn main:app --reload

Open http://127.0.0.1:8000/docs to test the API interactively.
