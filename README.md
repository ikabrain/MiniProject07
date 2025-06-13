# 📝 Mini Project 07 - Marks Adding
> **Course**: [Thapar's Machine Learning Summer School, 2025](https://www.thaparsummerschool.com/)
> 
> **Student Name**: Ikansh Mahajan
>
> **Student Roll No.**: 102303754

## 🔎 Problem Statement
Given a CSV file containing roll nums and marks, add marks of each roll num and write the CSV to an output file.
![image](https://private-user-images.githubusercontent.com/7460892/243881755-9be14aa0-eaa0-403a-9575-32771724f0e2.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDk3OTQ1MzIsIm5iZiI6MTc0OTc5NDIzMiwicGF0aCI6Ii83NDYwODkyLzI0Mzg4MTc1NS05YmUxNGFhMC1lYWEwLTQwM2EtOTU3NS0zMjc3MTcyNGYwZTIucG5nP1gtQW16LUFsZ29yaXRobT1BV1M0LUhNQUMtU0hBMjU2JlgtQW16LUNyZWRlbnRpYWw9QUtJQVZDT0RZTFNBNTNQUUs0WkElMkYyMDI1MDYxMyUyRnVzLWVhc3QtMSUyRnMzJTJGYXdzNF9yZXF1ZXN0JlgtQW16LURhdGU9MjAyNTA2MTNUMDU1NzEyWiZYLUFtei1FeHBpcmVzPTMwMCZYLUFtei1TaWduYXR1cmU9ZTA4MGUwODBjMGFhYWM2MGYxMDI5YTNlMDZmM2RjZWM3OTgxYmE4Y2NiZTFmNjdlZGNkY2RjYTNjYzM4OGY3MyZYLUFtei1TaWduZWRIZWFkZXJzPWhvc3QifQ.qVkc5VSu1HxyH8U8J16HXQaj3tptBdGclaYyyYHtHuI)

## 🔬 Solution
```mermaid
flowchart TD
A[Start Program] --> B["Open 'marks.csv' in read mode"]
B --> C[Initialize csvreader and skip header]
C --> D["Loop through each row: (rollno, marks)"]
D --> E{"Is rollno already in result?"}
E -- Yes --> F[Add marks to existing entry]
E -- No --> G[Create new entry in result]
F --> H[Next row]
G --> H
H --> I{"All rows processed?"}
I -- No --> D
I -- Yes --> J["Open 'output.csv' in write mode"]
J --> K[Write header]
K --> L[Loop through result dict]
L --> M[Write rollno and total marks]
M --> N{"More entries?"}
N -- Yes --> L
N -- No --> O[End Program]
```

## 🚀 How to Run Notebook
Click on the  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">  button on top of the notebook to open it in Google Colab and experiment with my solution by copying it to your Drive.

![07 57 08 PM](https://github.com/user-attachments/assets/e65efa6e-aa6b-45a3-a5e4-c11ea84ecb99)

## 🧾 Reflections
This assignment gave me hands-on exposure to using csv files in Python

## ⚠️ Report Issues
Create an issue ticket using the `Issues` section up above.
