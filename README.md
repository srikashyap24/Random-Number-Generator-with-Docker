# 🎲 Random Number Generator with Docker

This project demonstrates how to run a Python script interactively inside a Docker container. The script generates a random number between a user-defined range.

## 📁 Files Included

- `rng.py` – Python script to generate a random number.
- `Dockerfile` – Docker configuration to run the script.

## 🐳 Requirements

- Docker

## 🚀 How to Use

1. Clone the repository:

   git clone https://github.com/srikashyap24/Random-Number-Generator-with-Docker 
   cd Random-Number-Generator-with-Docker

2. Build the Docker image:

   docker build -t rng-app .

3. Run the container interactively:

   docker run -it rng-app

You will be asked to enter a minimum and maximum number, and it will print a random number in that range.

## 📌 Example Output

Please enter the min number: 5  
Please enter the max number: 15  
9

## 📚 What I Learned

- Writing a Python script with `randint`
- Creating and using a `Dockerfile`
- Running interactive containers using Docker

## 📦 Purpose

A simple exercise to understand interactive container usage with Docker and Python.

---
🛠️ Built with Python & Docker  
🎓 For learning and practice
