# 🚀 multim-project — Developer Multi-Agent AI Project Workspace

A persistent, secure, scalable AI Project Workspace inspired by ChatGPT Projects, Claude Projects, and Gemini Workspaces built specifically for software developers and technical teams.

```
                                  +---------------------------------------+
                                  |    Next.js / React Frontend (Client)   |
                                  |  Bootstrap 5 + Modern Developer UI    |
                                  +-------------------+-------------------+
                                                      | REST API / SSE
                                                      v
                                  +---------------------------------------+
                                  |        FastAPI Backend (Server)       |
                                  +-------------------+-------------------+
                                                      |
                  +-----------------------------------+-----------------------------------+
                  |                                   |                                   |
                  v                                   v                                   v
    +---------------------------+       +---------------------------+       +---------------------------+
    |  Supervisor Agent Router  |       |   RAG & Document Engine   |       | Project Memory & Context  |
    +-------------+-------------+       | (PyPDF/Text -> Chunking   |       | (Fact Extraction, Rules,  |
                  |                     |  -> RAG Vector Search)    |       |  Dynamic Context Assembly)|
       +----------+----------+          +---------------------------+       +---------------------------+
       |          |          |
       v          v          v
  +--------+  +--------+  +--------+
  | Coding |  | Arch.  |  | Doc    |
  | Slave  |  | Slave  |  | Slave  |
  +--------+  +--------+  +--------+
```

---

## 🌟 Key Features & Capabilities

1. **Multi-Agent Orchestrator**:
   - **Supervisor Agent (Master Router)**: Evaluates developer query intent & length. Answers simple queries directly for maximum speed.
   - **Coding Specialist Agent (Slave-1)**: Full-stack code generation, refactoring, unit tests, and script execution.
   - **Architecture Specialist Agent (Slave-2)**: System architecture blueprints, microservices design, and **Mermaid.js** diagrams.
   - **Research & RAG Specialist Agent (Slave-3)**: RAG document search over uploaded PDFs, Markdown, and codebase files with citations.
   - **Review & QA Specialist Agent (Slave-4)**: Code review, security auditing, and test validation.
2. **Persistent Context & Instructions**:
   - Dynamic context assembly: System Rules → Developer Rules → Project Instructions → Class Instructions → Memories → RAG Chunks → Chat History.
3. **Configurable Workstream Classes**:
   - 12 standard department classes + `+ Add Class` modal for custom workstreams (Mobile, ML, Payments, etc.).
4. **Private Personal Assistant**:
   - Floating `✨ Personal Assistant` drawer button with 100% private conversation history.
5. **Project State & Task Kanban Board**:
   - Kanban Board, List View, Roadmap Timeline, and AI Subtask Generator.
6. **Artifacts Studio**:
   - Persistent code snippets, Mermaid diagrams, version history, version restoration, and downloading.

---

## 📁 Directory Structure

- `client/`: Next.js / React app with Bootstrap 5 & modern dark glassmorphism stylesheet.
- `server/`: Python FastAPI app with Async SQLAlchemy, LangChain multi-agent framework, and RAG service.

---

## ⚡ How to Run

### Method 1: Double-Click Launcher
Double-click `start_workspace.bat` inside `multim-project`.

### Method 2: Manual Commands
```bash
# Backend (Server)
cd server
python run.py

# Frontend (Client)
cd client
npm run dev
```
<img width="1600" height="805" alt="image" src="https://github.com/user-attachments/assets/648babc1-497f-4b91-b513-b0de1700f97c" />
<img width="1600" height="752" alt="image" src="https://github.com/user-attachments/assets/418c135a-40cb-4df6-930f-adeac4c63c6c" />
<img width="1600" height="748" alt="image" src="https://github.com/user-attachments/assets/1311b014-3af9-4861-bee6-0ee1bac24b38" />
<img width="1600" height="744" alt="image" src="https://github.com/user-attachments/assets/4f9f55dc-6abe-4707-b062-573d4e7b1608" />
<img width="1600" height="803" alt="image" src="https://github.com/user-attachments/assets/d382b826-df77-4fc3-9589-173ec9462f41" />
<img width="1600" height="812" alt="image" src="https://github.com/user-attachments/assets/6da3da34-a71a-4717-8b30-78e9210f3549" />
<img width="1600" height="815" alt="image" src="https://github.com/user-attachments/assets/6403ad54-ec22-4524-a06d-e55b5e63a760" />
<img width="1600" height="812" alt="image" src="https://github.com/user-attachments/assets/66c07daa-d5cb-40db-b78b-4a629a1c1a32" />
<img width="1600" height="811" alt="image" src="https://github.com/user-attachments/assets/a1b3df37-71dc-467a-970b-9541f4a3b6f6" />
<img width="1600" height="787" alt="image" src="https://github.com/user-attachments/assets/1ed59423-e0c7-4570-bc62-f4a3105a749e" />







