# Simple C++ HTTP Web Server

A lightweight, fork-based HTTP server written in C++ that serves static files, handles basic HTTP requests (GET, POST, PUT), and can be extended to support an in-memory database.

## 🚀 Features

- Handles `GET`, `POST`, and `PUT` HTTP requests
- Serves static files (HTML, CSS, JS, images, etc.)
- Can be extended with an in-memory database for data handling
- Supports simple routing and content-type detection
- Uses C++17 and standard sockets (POSIX)

## 📁 Project Structure

├── main.cpp # Main server logic
├── index.html # Sample homepage
├── InMemoryDB.* # (Optional) In-memory database files
├── README.md

## 🛠 Build Instructions

Make sure you have a C++17-compatible compiler installed (e.g., g++).

```bash
g++ main.cpp -o server -std=c++17

```Makefile
make

**##🧪 Running the Server**
./server
