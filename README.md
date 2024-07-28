# Spring Boot WebSocket Chat App

![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)

A real-time chat application using Spring Boot and WebSockets.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Running the Application](#running-the-application)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project demonstrates how to create a real-time chat application using Spring Boot and WebSockets. It allows users to join a chat room and send messages to each other in real-time.

## Features

- Real-time messaging with WebSockets
- User-friendly interface with HTML and JavaScript
- Multiple chat rooms support
- Display active users
- Message timestamps

## Technologies Used

- Spring Boot
- WebSocket
- STOMP
- HTML, CSS, JavaScript

## Getting Started

### Prerequisites

- Java 17 or higher
- Maven 3.6.3 or higher

### Installation

1. Clone the repository:
   
   ```bash
   git clone https://github.com/your-username/springboot-websocket-chat-app.git
2. Navigate to the project directory:
   
   ```bash
   cd springboot-websocket-chat-app
3. Build the project using Maven:
   
   ```bash
   mvn clean install
   
4. Run the Spring Boot application:
      ```bash
      mvn spring-boot:run
5. Open your web browser and go to http://localhost:8080 to access the chat application.

### Usage

- Open the application in multiple browser tabs to simulate multiple users
- Enter your name to join the chat
- Start sending messages to the chat room
