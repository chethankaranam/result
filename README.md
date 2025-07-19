# 📊 Student Grade Tracker Web App


![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?logo=javascript&logoColor=black)
![JSON](https://img.shields.io/badge/JSON-Data-lightgrey?logo=json)


> A lightweight, responsive web application that allows students to instantly view their academic grades and performance analytics by simply entering their roll number. Designed to solve a real-world problem of fragmented, inaccessible grade reporting in many colleges.

---

## 🚀 Our Story

In 2020, we noticed a recurring issue at our college: students could only access their grades through PDF files published on the college website—one per department, per semester. These files were often outdated, hard to search through, and not mobile-friendly. To make matters worse, access to smartphones and personal computers was restricted on campus, making the process even more frustrating.

What seemed like a small inconvenience was actually a real pain point for students every semester.

To address this, we built a lightweight web app that made grade lookup fast, easy, and accessible.

- **Chethan Sai Karanam** focused on developing the backend, handling PDF parsing using Python and structuring the extracted data into clean, queryable JSON.
- **Harisrujan C** worked on the ideation and built the front-end interface using HTML, CSS, and JavaScript to ensure it was lightweight, responsive, and intuitive.

The result? A streamlined, searchable web app where students could simply enter their roll number (e.g., `18691A0544`) and instantly view their grades, percentages, and basic performance analytics. It may seem simple now, but at that time, it solved a real, everyday problem for many of our peers.

---

## ✨ Features

- 🔍 **Searchable Grade Interface** – Enter a roll number to instantly access student grades.
- 📄 **PDF Parsing** – Automatically extracts data from official grade PDF files using Python.
- 🧩 **Structured JSON Data** – Enables efficient querying and storage.
- ⚡ **Real-Time Results** – Grades and analytics appear instantly.
- 📱 **Responsive Design** – Mobile-friendly and lightweight front-end.

---

## 🛠 Tech Stack

| Layer      | Technology              |
|------------|--------------------------|
| Frontend   | HTML, CSS, JavaScript    |
| Backend    | Python (PDF parsing)     |
| Data Format| JSON                     |

---

## 🌐 Live Demo

Try it with this sample roll number: `18691A0520`

🔗 **[Live Demo](https://chethankaranam.github.io/result/)**  


---

## 📦 Installation

1. **Clone the repository:**
   ```bash
   git clone https://chethankaranam.github.io
   cd result
   ```

2. **Install Python dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Parse the PDF and generate JSON:**
   ```bash
   python parse_grades.py
   ```

4. **Start a local server (optional but recommended):**
   ```bash
   python -m http.server 8000
   ```

5. **Open the app:**

   - Go to [http://localhost:8000](http://localhost:8000)
   - Enter a roll number to view grades.

---

## 📖 Usage

- Input a valid roll number (e.g., `18691A0544`) into the search bar.
- Instantly view:
  - Individual subject grades
  - Total percentage
  - Basic performance analytics
- Ensure the JSON output from the PDF parser is placed in the appropriate directory for the app to access.

---

## 🤝 Contributing

Contributions are welcome and appreciated!

### How to Contribute:

1. **Fork** the repository.
2. **Create a new branch**:
   ```bash
   git checkout -b feature-name
   ```
3. **Commit your changes**:
   ```bash
   git commit -m 'Add feature'
   ```
4. **Push to your forked repo**:
   ```bash
   git push origin feature-name
   ```
5. **Submit a Pull Request**.

Please open an issue first if you'd like to discuss a major feature change.

---

## 📄 License

This project is licensed under the **MIT License**.  
See the [LICENSE](./LICENSE) file for details.

---

## 🙌 Acknowledgements

Thanks to our peers who tested and used the app during its early iterations—it was built for you.
