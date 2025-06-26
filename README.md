This Python project is a **Student Examination Management System** designed to:

### 📚 **Main Purpose**

To **collect, store, analyze, and visualize student exam data** across multiple departments, batches, and courses using CSV files as the database and `matplotlib` for graphical reports.

---

### 🔍 **What It Does**

1. **Data Entry & Storage**

   * Takes student details (name, stream, batch, roll number, marks).
   * Automatically generates a unique Student ID.
   * Stores data in structured CSV files:

     * `Student.csv`, `Batch.csv`, `Course.csv`, `Department.csv`, `Examination.csv`.

2. **Report Card Generation**

   * Creates a personalized **report card text file** with marks, total score, percentage, and grade.
   * Opens it in Notepad for review.

3. **Duplicate Check & Deletion**

   * Checks for duplicate entries.
   * Allows deleting student data immediately after report generation if desired.

4. **Grade Calculation**

   * Converts marks into percentages.
   * Assigns letter grades (A to F) based on performance.

5. **Data Analysis & Visualization**

   * **Batch-wise Grade Pie Chart**: Distribution of grades for a specific batch.
   * **Course-wise Grade Line Chart**: How students performed in each subject.
   * **Department-wise Average Bar Chart**: Average performance of batches across departments.

6. **Initial Setup**

   * On first run, creates necessary folders/files like `ReportCards`, and populates master CSVs with stream/course information.

---

### 🛠️ **Key Tools & Concepts Used**

* `CSV` module for structured file handling.
* `os` and `subprocess` for file and process management.
* `matplotlib` for plotting graphs.
* Input validation and file updating mechanisms.
* Simple GUI simulation via Notepad + CLI interaction.

---

### 🧑‍💻 **Who It's For**

* CS students learning file handling, data visualization, and basic data management.
* Schools/Colleges looking for a basic CLI-based examination reporting tool.
* Anyone interested in how structured CSV data can be used to simulate databases.

---
