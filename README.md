# Broadcast Server

A lightweight real-time broadcast server built with Go.  
It allows multiple clients to connect simultaneously and receive messages instantly through a shared broadcasting system.

This project was built to demonstrate concurrency, networking, and real-time communication concepts using Go.

---

## Features

- Multiple client connections
- Real-time message broadcasting
- Concurrent connection handling with Goroutines
- Lightweight TCP/WebSocket architecture
- Fast and efficient message delivery
- Clean and simple project structure
- Easy to extend for chat or notification systems

---

## How It Works

1. Start the server  
2. Clients connect to the server  
3. Any incoming message is broadcast to all connected clients  
4. Connected users receive messages instantly in real time

---



```bash
git clone https://github.com/HosseinForouzan/broadcast-server.git
cd broadcast-server
