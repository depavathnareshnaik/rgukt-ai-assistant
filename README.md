# RGUKT AI Assistant

## Project Title
RGUKT AI Assistant

## Description
RGUKT AI Assistant is an AI-powered chatbot designed to help students, faculty, and visitors quickly access university-related information. It uses advanced AI techniques like Retrieval-Augmented Generation (RAG) to provide accurate answers from academic regulations, documents, and web data.

The system simplifies access to scattered information by converting it into a conversational interface, making it easy to use and efficient.

## Features
- Intelligent chatbot for academic queries  
- Provides answers from university documents (PDF-based knowledge)  
- Semantic search using embeddings  
- Real-time chat interaction  
- Session-based chat history  
- FastAPI backend for high performance  
- Responsive frontend using React  
- Fallback mechanism when no data is found  

## Technologies Used

### Backend
- Python  
- FastAPI  

### AI / Machine Learning
- LangChain  
- Groq API  
- HuggingFace Embeddings  
- FAISS / Chroma Vector Database  

### Frontend
- React  
- Vite  
- Tailwind CSS  
- Axios  

## Installation

### Clone Repository
```bash
git clone https://github.com/depavathnareshnaik/rgukt-ai-assistant.git
cd rgukt-ai-assistant
```

### Backend Setup
```bash
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

Create a `.env` file and add:
```env
GROQ_API_KEY=your_api_key_here
```

Run backend server:
```bash
python start_server.py
```

### Frontend Setup
```bash
cd frontend
npm install
npm run dev
```

## Usage
- Open the frontend in your browser  
- Ask questions related to academics, placements, or university rules  
- The chatbot will respond with relevant answers  

## Project Structure
```
rgukt-ai-assistant/
│
├── app/              
├── frontend/         
├── requirements.txt  
├── start_server.py   
└── README.md
```

## Use Cases
- Students can get instant academic information  
- Faculty can refer to regulations quickly  
- New students can explore university details  
- Helps reduce time spent searching for information  

## Future Enhancements
- Multi-language support  
- Voice-based interaction  
- Mobile application  
- Integration with university portals  

## Contributing
- Fork the repository  
- Create a new branch  
- Submit a pull request  

## License
MIT License

## Author
Naresh Depavath
