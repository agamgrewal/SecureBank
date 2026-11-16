# SecureBank API

A banking REST API built using Python and FastAPI.

## Getting Started

### Prerequisites

- Python 3.10+
- Git

### 1. Clone the repository

```bash
git clone <repository-url>
cd securebank-api
```

### 2. Create a virtual environment

```bash
python3 -m venv .venv
```

Activate the environment:

**macOS / Linux**
```bash
source .venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
fastapi dev main.py
```

The API will be available at:

- **API:** http://127.0.0.1:8000
- **Interactive API docs:** http://127.0.0.1:8000/docs

### 5. Run tests

```bash
pytest
```

## Tech Stack

- Python
- FastAPI
- pytest