🧠 AI-Powered E-Commerce Recommendation System
==============================================

**Developer:** _Sourabh Joshi_**Institute:** _Vellore Institute of Technology (VIT)_**Registration No.:** _22BCE11673_

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

LayerTechnology**Frontend**React (Vite), CSS3, ESLint**Backend**Node.js, Express.js, Multer, Axios**Database**MongoDB + Mongoose**AI Models**Claude 3.5 Sonnet, GPT-4o-mini, Mistral 7B**Utilities**pdf-parse, dotenv, cors, nodemon

🧩 Core Logic
-------------

### 🧾 Multi-Strategy Extraction

1.  **Regex Parsing** – Structured catalog recognition
    
2.  **LLM Extraction** – Understands unstructured data
    
3.  **Heuristic Parsing** – Detects product lines via pricing patterns
    

🪄 **Smart Deduplication** via Levenshtein Distance🏷️ **Auto-Categorization & Tagging** for quick search

🛠️ Setup
---------

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   # Clone  git clone  && cd unthinkable  # Server Setup  cd server && npm install  # Client Setup  cd ../client && npm install   `

**.env (inside /server):**

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   PORT=8000  MONGODB=mongodb://localhost:27017/recommendations  OPENROUTER_API_KEY=your_api_key_here   `

▶️ Run the App
--------------

**Start Backend**

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   cd server  npm start   `

**Start Frontend**

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   cd client  npm run dev   `

Frontend: http://localhost:5173Backend: http://localhost:8000

📡 API Summary
--------------

MethodEndpointDescriptionPOST/api/chat/pdf-uploadUpload PDF and extract productsPOST/api/chat/recommendGet personalized AI recommendationsPOST/api/chat/askQuery products using natural languageGET/api/chat/productsRetrieve all stored productsGET/api/chat/interactionsView user interaction history

🔍 Example Query
----------------

**Input:**

> “Suggest running shoes under $100 for marathon training.”

**AI Response:**

> “Based on your preferences, I recommend _RunMaster 3000_ — lightweight, breathable, and ideal for long-distance runs.”

🧱 Project Structure
--------------------

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   unthinkable/  ├── client/     # React frontend  │   ├── components/  │   └── utils/  └── server/     # Express backend      ├── controllers/      ├── models/      ├── routes/      └── db/   `

🌟 Future Enhancements
----------------------

*   🖼️ OCR for image-based PDFs
    
*   📊 CSV/Excel Upload Support
    
*   🌍 Multi-language AI recommendations
    
*   🔐 User Authentication
    
*   📱 Mobile App / PWA
    

🎓 Developer Profile
--------------------

**👨‍💻 Name:** Sourabh Joshi**🏫 Institution:** Vellore Institute of Technology (VIT)**🎓 Registration No.:** 22BCE11673**💬 Domain Interests:** AI, Backend Engineering, and Full-Stack Development

❤️ Acknowledgment
-----------------

Built with passion using **React, Express.js, MongoDB**, and **OpenRouter AI Models**.Turning traditional product catalogs into intelligent, conversational e-commerce system