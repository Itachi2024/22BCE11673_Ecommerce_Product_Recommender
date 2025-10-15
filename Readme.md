🧠 AI-Powered E-Commerce Recommendation System
==============================================

* **Developer:** Sourabh Joshi.
* **Institute:** Vellore Institute of Technology (VIT)
* **Registration No.:** 22BCE11673

💡 Overview
-----------

An intelligent **AI-driven product recommendation system** that transforms static PDF catalogs into a dynamic e-commerce experience.Built using **React, Node.js, Express.js, MongoDB**, and **multi-model LLMs**, this system automatically extracts products, stores them in a database, and generates **personalized recommendations** for users.

🚀 Key Features
---------------

*   **📄 Smart PDF Upload:** Extracts products via Regex, LLM, and Heuristic methods.
    
*   **🧠 AI Recommendations:** Personalized suggestions with natural language explanations.
    
*   **💾 MongoDB Persistence:** Stores products, queries, and user interactions.
    
*   **🎨 Modern UI:** Responsive pink-gradient interface with tabs for Query, Products & History.
    
*   **📊 Search & Filters:** Browse products by category, price, or keyword.
    
*   **📈 Interaction Tracking:** View previous queries and recommendations.
    

⚙️ Tech Stack
-------------

* **Frontend**React (Vite), CSS3, ESLint
* **Backend**Node.js, Express.js, Multer, Axios
* **Database**MongoDB + Mongoose
* **AI Models**Claude 3.5 Sonnet, GPT-4o-mini, Mistral 7B
* **Utilities**pdf-parse, dotenv, cors, nodemon

🧩 Core Logic
-------------

### 🧾 Multi-Strategy Extraction

1.  **Regex Parsing** – Structured catalog recognition
    
2.  **LLM Extraction** – Understands unstructured data
    
3.  **Heuristic Parsing** – Detects product lines via pricing patterns
    

🪄 **Smart Deduplication** via Levenshtein Distance🏷️ **Auto-Categorization & Tagging** for quick search

🛠️ Setup
---------
# Clone  git clone  && cd unthinkable  
# Server Setup  cd server && npm install  
# Client Setup  cd ../client && npm install   `

**.env (inside /server):**

 #PORT=8000  
 #MONGODB=mongodb://localhost:27017/recommendations  
 #OPENROUTER_API_KEY=your_api_key_here   `

▶️ Run the App
--------------

**Start Backend**

  #cd server  npm start   

**Start Frontend**

 # cd client  npm run dev   

Frontend: http://localhost:5173Backend: http://localhost:8000

📡 API Summary
--------------

* **MethodEndpointDescription** POST/api/chat/pdf-upload
* **Upload PDF and extract products** POST/api/chat/recommendGet 
* **personalized AI recommendations** POST/api/chat/askQuery 
* **products using natural language** GET/api/chat/products
* **Retrieve all stored products** GET/api/chat/interactions

🔍 Example Query
----------------

**Input:**

> “Suggest running shoes under $100 for marathon training.”

**AI Response:**

> “Based on your preferences, I recommend _RunMaster 3000_ — lightweight, breathable, and ideal for long-distance runs.”

🧱 Project Structure
--------------------

   unthinkable/  
       ├── client/     
           # React frontend  │   
               ├── components/  │   
               └── utils/  
               └── server/     
            # Express backend      
                ├── controllers/      
                ├── models/     
                ├── routes/     
                    └── db/   `

🌟 Future Enhancements
----------------------

*   🖼️ OCR for image-based PDFs
    
*   📊 CSV/Excel Upload Support
    
*   🌍 Multi-language AI recommendations
    
*   🔐 User Authentication
    
*   📱 Mobile App / PWA
    

🎓 Developer Profile
--------------------

* **👨‍💻 Name:** Sourabh Joshi
* **🏫 Institution:** Vellore Institute of Technology (VIT
* **🎓 Registration No.:** 22BCE11673
* **💬 Domain Interests:** AI, Backend Engineering, and Full-Stack Development

❤️ Acknowledgment
-----------------

Built with passion using **React, Express.js, MongoDB**, and **OpenRouter AI Models**.Turning traditional product catalogs into intelligent, conversational e-commerce system
