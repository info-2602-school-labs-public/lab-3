## Setup Instructions

### 1. Create a virtual environment
```bash
python -m venv venv
```

### 2. Activate the virtual environment

- **Windows:**
```bash
venv\Scripts\activate
```

- **Mac / Linux:**
```bash
source venv/bin/activate
```

### 3. Install dependencies
```bash
pip install -e .
```

### 4. Initialize the database
```bash
python app/cli.py initialize
```

### 5. Run the development server
```bash
fastapi dev
```

If the port is already in use:
```bash
fastapi dev --port 9090
```

### 6. Open in browser

Click the link shown in the terminal.

If you used a custom port:
```bash
http://localhost:9090
```
