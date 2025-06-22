# ChatApp WebSocket - Spring Boot Group Chat Application

A real-time group chat backend application built using **Spring Boot**, **WebSocket**, and **MongoDB**.

## 🚀 Features

- ✅ Users can **join an existing room** by entering a room ID.
- ✅ Users can **create a new room** with a unique room ID.
- ✅ Chat messages are stored in **MongoDB** for persistence.
- ✅ Users can see previously saved messages upon joining a room.
- ✅ **Real-time** messaging updates for all users using WebSockets.

---

## 🛠️ Tech Stack

- **Spring Boot** - Backend Framework
- **WebSocket (STOMP)** - For real-time communication
- **MongoDB** - For message and room data persistence

---

## 📦 Functional Requirements

### Room Management

#### 1. Create Room
- Users can create a new room using a unique room name or ID.
- System validates room uniqueness.
- Room data is saved in MongoDB.

#### 2. Join Room
- Users can join an existing room by providing a valid room ID.
- On success, they can view past messages and begin chatting.
- Invalid IDs return an error message.

---

## 🧑‍💻 Getting Started

### Prerequisites
- Java 17+
- Maven
- MongoDB running locally or Atlas URI

### Steps

```bash
git clone https://github.com/your-username/chatapp.git
cd chatapp-websocket
