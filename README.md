# 🧩 Sample 02 — Insertion Sort

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![DSA](https://img.shields.io/badge/Topic-Data%20Structures%20%26%20Algorithms-orange)
![Algorithm](https://img.shields.io/badge/Algorithm-Insertion%20Sort-green)

A simple Python implementation of the **Insertion Sort** algorithm using a class-based approach.

This repository is part of my **Python & DSA learning journey**, where I practice fundamental algorithms and problem-solving techniques.

---

## 📌 About the Project

**Insertion Sort** is a simple sorting algorithm that builds the final sorted array one element at a time.

It works similar to how we arrange playing cards in our hand:

1. Pick one element.
2. Compare it with the elements before it.
3. Shift larger elements to the right.
4. Insert the element into its correct position.
5. Repeat until the array is sorted.

---

## 🛠️ Technologies Used

* 🐍 Python 3
* 🧠 Data Structures & Algorithms
* 💻 Object-Oriented Programming

---

## 📂 Project Structure

```text
sample-02/
│
├── app.py       # Insertion Sort implementation
├── sample.py    # Sample Python file
└── README.md    # Project documentation
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/ashfaq-ahmed02/sample-02.git
```

### 2. Enter the project directory

```bash
cd sample-02
```

### 3. Run the Python file

```bash
python app.py
```

---

## 💡 Example

### Input

```python
arr = [5, 3, 4, 1, 2]
```

### Sorting Process

```text
[5, 3, 4, 1, 2]
[3, 5, 4, 1, 2]
[3, 4, 5, 1, 2]
[1, 3, 4, 5, 2]
[1, 2, 3, 4, 5]
```

### Output

```text
[1, 2, 3, 4, 5]
```

---

## 🧠 How the Code Works

The main method is:

```python
def insertionSort(self, arr):
```

The algorithm starts from the second element:

```python
for i in range(1, len(arr)):
```

The current element is stored as `key`:

```python
key = arr[i]
```

Then previous elements are compared with the key:

```python
while j >= 0 and arr[j] > key:
```

If an element is larger, it is shifted one position to the right:

```python
arr[j + 1] = arr[j]
```

Finally, the key is placed in its correct position:

```python
arr[j + 1] = key
```

---

## ⏱️ Complexity

| Case         | Time Complexity |
| ------------ | --------------- |
| Best Case    | O(n)            |
| Average Case | O(n²)           |
| Worst Case   | O(n²)           |

**Space Complexity:** `O(1)`

Insertion Sort is an **in-place sorting algorithm**, meaning it does not require an additional array for sorting.

---

## 🎯 Learning Goals

Through this project, I am practicing:

* Python fundamentals
* Classes and methods
* Arrays
* Loops
* Sorting algorithms
* Time and space complexity
* Problem-solving skills

---

## 👨‍💻 Author

**Ashfaq Ahmed**

CSE Student | Python & DSA Learner | DevOps & Cybersecurity Enthusiast

🔗 GitHub: [@ashfaq-ahmed02](https://github.com/ashfaq-ahmed02)

---

⭐ If you find this repository useful, feel free to **star the repository**!
