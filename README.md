<h1 align="center">🎭 Movie Script Analysis using Hadoop MapReduce</h1>

<h3 align="center">
Big Data Processing | Hadoop MapReduce | Java | Text Analytics
</h3>

<p align="center"><em>"Analyzing movie dialogues to extract character-level insights using distributed computing."</em></p>

---

## ✨ Overview

This project analyzes **movie script dialogues** using **Hadoop MapReduce** to extract insights about character speech patterns.

It processes large text data to identify **frequent words, dialogue lengths, and unique vocabulary per character**, demonstrating scalable text analytics using distributed systems.

---

## 🚀 Key Features

- 📥 Processing large text datasets using Hadoop  
- 🔤 Word frequency analysis per character  
- 📏 Dialogue length computation  
- 🧠 Unique vocabulary extraction  
- ⚡ Distributed processing using MapReduce  

---

## 🧠 Tech Stack

![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![Hadoop](https://img.shields.io/badge/Hadoop-FFCA28?style=for-the-badge&logo=apachehadoop&logoColor=black)
![MapReduce](https://img.shields.io/badge/MapReduce-FF6F00?style=for-the-badge)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

---

## 📂 Project Structure
- input/
- ├── movie_dialogues.txt

src/
- ├── Mapper.java
- ├── Reducer.java
-├── Driver.java

output/
- ├── task1/ # Word frequency
- ├── task2/ # Dialogue length
- ├── task3/ # Unique words

---

## 🔍 Analysis Performed

### 📌 Word Frequency Analysis
- Identified most frequently spoken words by each character  

---

### 📌 Dialogue Length Analysis
- Calculated total dialogue length per character  

---

### 📌 Unique Word Analysis
- Extracted distinct words used by each character  

---

## ⚙️ How to Run

```bash
mvn clean install
```
```bash
hadoop jar <your-jar-file> <DriverClass> <input> <output>
```
### 📌 Project Highlights
- Built a distributed text processing system
- Implemented custom MapReduce jobs
- Processed large-scale dialogue data
- Extracted character-level insights
- Used Hadoop ecosystem tools effectively
---
