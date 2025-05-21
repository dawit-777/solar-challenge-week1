

## 📦 Reproduce the Environment

Follow these steps to set up the development environment:

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
````

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the virtual environment

#### On Windows (PowerShell):

```bash
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process
.\venv\Scripts\Activate.ps1
```

#### On macOS/Linux:

```bash
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run CI locally (optional)

```bash
# Make sure required tools like pytest are installed
pytest
```

> GitHub Actions also runs CI automatically on every push and pull request.

```

---


