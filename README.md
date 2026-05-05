# 🚀 Python CI/CD Pipeline using GitHub Actions

## 📌 Project Description

This project demonstrates a simple **CI/CD (Continuous Integration) pipeline** for a Python application using GitHub Actions.
Whenever code is pushed to the repository, the pipeline automatically runs tests to ensure the correctness of the program.

---

## ⚙️ Tech Stack

* **Python** – Application logic
* **pytest** – Testing framework
* **GitHub Actions** – CI/CD automation

---

## 📂 Project Structure

```
devops-python-pipeline/
├── my_program.py        # Main Python program
├── test_program.py     # Test cases using pytest
└── .github/
     └── workflows/
          └── ci.yml    # CI/CD pipeline configuration
```

---

## 🔄 How the CI/CD Pipeline Works

1. Code is pushed to the `main` branch
2. GitHub Actions automatically triggers the workflow
3. A virtual environment is created
4. Python is installed
5. Dependencies (pytest) are installed
6. Test cases are executed
7. Pipeline passes or fails based on test results

---

## ▶️ How to Run Locally

### 1. Clone the repository

```
git clone https://github.com/your-username/devops-python-pipeline.git
cd devops-python-pipeline
```

### 2. Install dependencies

```
pip install pytest
```

### 3. Run tests

```
pytest
```

---

## ✅ Sample Test

```python
from my_program import add

def test_basic():
    assert add(2, 2) == 4
```

---

## 📸 CI Pipeline Output

👉 Add a screenshot here:

* Go to **Actions tab**
* Take a screenshot of the successful run (green tick)
* Upload it here

Example:

```
![CI Pipeline Success](screenshot.png)
```

---

## 💡 Key Learnings

* Implemented CI/CD using GitHub Actions
* Automated testing using pytest
* Understood workflow automation on code push
* Learned how to structure a DevOps project

---

## 🎯 Future Improvements

* Add Docker support
* Add more test cases
* Deploy application to cloud
* Integrate code coverage tools

---

## 👨‍💻 Author

Protorthi Saha
