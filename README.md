# ChatApplication
🚀 Project Title & Tagline
============================
### Real-Time Chat Application 📱💬
#### Connecting people in real-time, one message at a time 🕒💬

📖 Description
---------------
This project is a real-time chat application built using Java Spring Boot and Maven. The application allows users to send and receive messages in real-time, creating a seamless and interactive experience. The project utilizes WebSockets to establish a bi-directional communication channel between the client and server, enabling efficient and instantaneous message exchange.

The application consists of a simple and intuitive user interface, where users can input and send messages. The messages are then broadcasted to all connected clients, creating a real-time chat experience. The project also includes a basic testing framework to ensure the application's functionality and reliability.

The Real-Time Chat Application is designed to be scalable and flexible, allowing for easy integration with other services and features. The project's architecture is modular and well-structured, making it easy to maintain and extend. Whether you're building a simple chat application or a complex messaging platform, this project provides a solid foundation for your real-time communication needs.

The application's features and functionality are designed to provide a seamless and engaging user experience. With its real-time messaging capabilities, the application is perfect for a wide range of use cases, from simple chat applications to complex collaborative platforms. The project's codebase is well-organized and maintainable, making it easy to customize and extend the application to meet your specific needs.

✨ Features
-----------
The following are the key features of the Real-Time Chat Application:
* **Real-Time Messaging**: Send and receive messages in real-time, creating a seamless and interactive experience.
* **WebSocket Support**: Establish a bi-directional communication channel between the client and server, enabling efficient and instantaneous message exchange.
* **Simple and Intuitive UI**: Easy-to-use interface for users to input and send messages.
* **Broadcasting**: Messages are broadcasted to all connected clients, creating a real-time chat experience.
* **Testing Framework**: Basic testing framework to ensure the application's functionality and reliability.
* **Modular Architecture**: Well-structured and modular architecture, making it easy to maintain and extend.
* **Scalability**: Designed to be scalable and flexible, allowing for easy integration with other services and features.
* **Security**: Basic security features to ensure the application's security and integrity.

🧰 Tech Stack Table
-------------------
| Technology | Description |
| --- | --- |
| **Frontend** | HTML, CSS, JavaScript |
| **Backend** | Java Spring Boot, Maven |
| **Tools** | Spring Boot, Maven, WebSocket, SockJS, Stomp.js |
| **Database** | In-Memory Database (for simplicity) |
| **Testing Framework** | JUnit |

📁 Project Structure
---------------------
The project is structured into the following folders:
* **`com.chat.app`**: Main application package, containing the `AppApplication` class.
* **`com.chat.app.controller`**: Package containing the `ChatController` class, responsible for handling chat-related requests.
* **`com.chat.app.Config`**: Package containing the `WebSocketConfig` class, responsible for configuring WebSocket settings.
* **`com.chat.app.model`**: Package containing the `ChatMessage` class, representing a chat message.
* **`resources`**: Folder containing static resources, such as HTML, CSS, and JavaScript files.
* **`test`**: Folder containing test classes, such as `AppApplicationTests`.

⚙️ How to Run
---------------
To run the application, follow these steps:
### Setup
1. Clone the repository using `git clone`.
2. Navigate to the project directory using `cd`.
3. Install dependencies using `mvn clean install`.

### Environment
1. Set up your Java environment by installing JDK 8 or later.
2. Set up your Maven environment by installing Maven 3.6 or later.

### Build
1. Build the application using `mvn clean package`.
2. The application will be packaged into a JAR file.

### Deploy
1. Run the application using `java -jar target/app.jar`.
2. The application will start on port 8080 by default.
3. Open a web browser and navigate to `http://localhost:8080` to access the application.

🧪 Testing Instructions
-----------------------
To run tests, follow these steps:
1. Navigate to the project directory using `cd`.
2. Run tests using `mvn test`.
3. The test results will be displayed in the console.

📸 Screenshots
----------------
Unfortunately, we cannot provide actual screenshots here. However, you can run the application and see the UI in action.

📦 API Reference
----------------
The application provides a simple API for sending and receiving messages. The API endpoints are as follows:
* **`/chat`**: Send a message to the chat room.
* **`/chat/messages`**: Get all messages in the chat room.

👤 Author
-----------
The Real-Time Chat Application was developed by [Your Name].

📝 License
-----------
The Real-Time Chat Application is licensed under the [MIT License](https://opensource.org/licenses/MIT).
