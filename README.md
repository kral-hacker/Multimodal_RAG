# 🎥 Multimodal RAG for YouTube Video Retrieval

This project implements a **multimodal retrieval system** for YouTube videos using both **transcripts** and **video frames**. It allows users to perform semantic search across video content using natural language queries.

---

## 🧠 Key Features

- 🔍 **Multimodal Search**: Retrieve relevant video segments using both text and visual information.
- 🧩 **Joint Embedding Model**: Uses the [BridgeTower](https://huggingface.co/BridgeTower) model to generate **joint text-image embeddings**.
- 📦 **Efficient Retrieval**: Stores and queries embeddings using **LanceDB** with **cosine similarity**.

---

## ⚙️ How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/your-username/multimodal-video-retrieval.git
```

### 2. (Recommended) Create and activate a virtual environment


```bash
# For Windows
python -m venv venv
venv\Scripts\activate

# For Linux/macOS
python3 -m venv venv
source venv/bin/activate
```

### 3.  Install dependencies
``` bash
pip install -r requirements.txt
```

### 4. Run the Project

 Run the multimodal_embeddings.ipynb file


