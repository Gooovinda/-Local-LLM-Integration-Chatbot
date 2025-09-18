# 🤖 **Text Similarity API with FastAPI**

**📌 Objective**  
I created a lightweight REST API that computes similarity between two text inputs. The API uses TF-IDF vectorization and cosine similarity to return a numeric similarity score suitable for integration with search, validation, or recommendation systems.

**🚀 Key Highlights**  
- 🧠 **TF-IDF + Cosine Similarity**: Robust and fast method for text similarity.  
- 🚀 **FastAPI Backend**: High-performance REST API endpoint for easy integration.  
- 🖥 **JSON Response**: Clean output structure for applications to consume.  
- 🔧 **Reusable Service**: Can be extended into chatbots, search, or content-matching systems.

**📊 Tech Stack**  
- Python  
- FastAPI  
- Scikit-learn (TF-IDF Vectorizer, Cosine Similarity)  
- Uvicorn (server)

**📂 Dataset**  
- No external dataset required — the API accepts user-provided texts.

**🧪 Example Usage**  
Request:
```json
POST /similarity
{
  "text1": "I love machine learning",
{
  "similarity_score": 0.87
}
⚡ How to Run the Project

Clone the repository or download the ZIP file.

Install dependencies: pip install -r requirements.txt

Start the API server: uvicorn main:app --reload

Open http://127.0.0.1:8000/docs to test the API interactively.
  "text2": "Machine learning is amazing"
}
