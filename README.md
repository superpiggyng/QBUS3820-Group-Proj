
## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/superpiggyng/QBUS3820
```

### 2. Create a Virtual Environment

Create a Python virtual environment to isolate project dependencies.

```bash
python3 -m venv env
```

Activate the environment:

**macOS / Linux**

```bash
source env/bin/activate
```

**Windows**

```bash
env\Scripts\activate
```

### 3. Install Dependencies

Install the required Python packages listed in `requirements.txt`.

```bash
pip install -r requirements.txt
```


----

# Dataset Documentation

Official dataset documentation and variable descriptions can be found here:

https://cunningjames.github.io/completejourney_py/

----

# Making Contributions

## Git Workflow

Before making changes, always pull the latest version of the repository to avoid conflicts.

### 1. Pull the latest changes

```bash
git pull origin main
```

---

### 2. Make your changes

Edit or add the files required for your task (e.g., notebooks, scripts, or documentation).

---

### 3. Stage the changes

Add the modified files to the staging area.

```bash
git add <filename>
```

To stage all changes:

```bash
git add .
```

---

### 4. Commit the changes

Create a commit with a short descriptive message.

```bash
git commit -m "Brief description of the changes"
```

Example:

```bash
git commit -m "Add EDA notebook and initial visualisations"
```

---

### 5. Push the changes

Upload the commit to the remote repository.

```bash
git push origin main
```

---

This workflow should generally follow:

```
pull → edit → add → commit → push
```

to ensure everyone works on the most up-to-date version of the project.