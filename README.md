# ✈️ Real-Time Flight Status Update System

**Welcome to the Real-Time Flight Status Update System project!** This innovative platform is designed to keep passengers informed about their flights by providing real-time updates. The system delivers crucial information, such as delays, cancellations, and gate changes, directly to passengers through various channels like SMS, email, and app notifications. By integrating with airport systems and using advanced technologies, the goal is to enhance the travel experience by ensuring passengers have the most accurate and timely information.

## 🚀 Features

### 🕒 Real-time Updates
- **Current Flight Status:** The system provides up-to-the-minute information on flight status, including delays, cancellations, and gate changes, ensuring passengers are always aware of any changes.
- **Interactive Dashboard:** The user interface is designed with React.js to offer an intuitive and responsive experience, allowing passengers to easily access all relevant flight details.

### 📲 Push Notifications
- **Stay Informed:** Firebase Cloud Messaging and RabbitMQ are used to send real-time notifications, ensuring passengers receive instant alerts via their preferred communication channels, such as SMS, email, or in-app notifications.
- **Flexible Notification Channels:** Passengers can choose how they receive updates, whether through text messages, emails, or app alerts.

### 🌐 Integration with Airport Systems
- **Accurate Data:** The system pulls data from airport databases to provide the most accurate and up-to-date flight information. During development and testing phases, mock data is used to simulate real-world scenarios, ensuring reliability and performance.
- **Seamless Integration:** The backend, developed using Python, interacts with various data sources to aggregate and process information efficiently.

## 🛠️ Technologies Used

### Frontend
- **React.js:** Utilized for building dynamic and interactive user interfaces, ensuring a smooth user experience.
- **CSS3:** For crafting a responsive and modern UI.

### Backend
- **Python:** The system's backend is built using Python, providing a robust and versatile foundation for data processing and integration.

### Database
- **PostgreSQL:** This relational database is used to store flight information and user preferences securely and efficiently, allowing for quick data retrieval and robust data management.

### Notifications
- **Firebase Cloud Messaging & RabbitMQ:** These technologies ensure that notifications are delivered reliably and promptly, regardless of the communication channel chosen by the user.

## 🚧 Getting Started

### Prerequisites
- **Node.js & npm:** For managing frontend dependencies and building the React application.
- **Python:** Set up the Python environment for backend development.
- **PostgreSQL:** Configure and set up your PostgreSQL database.

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/yourusername/flight-status-system.git](https://github.com/surabhichauhan609/flight-status-app)
   cd flight-status-system
   ```

2. **Install frontend dependencies:**
   ```bash
   cd frontend
   npm install
   ```

3. **Set up the backend:**
   - Navigate to the backend directory and follow the setup instructions for Python.

4. **Configure the database:**
   - Set up PostgreSQL and configure the connection settings.

5. **Run the application:**
   - **Frontend:** Start the React application using `npm start`.
   - **Backend:** Run the Python backend server.

## What Has Been Done

In this project, a comprehensive system has been developed that integrates real-time data from various airport databases and provides passengers with instant updates on their flight status. A range of technologies has been utilized to ensure that the system is scalable, reliable, and user-friendly. An intuitive frontend has been designed using React.js, while the backend, developed in Python, processes and delivers accurate flight information. A robust notification system has been implemented using Firebase Cloud Messaging and RabbitMQ, ensuring that passengers receive timely alerts through their preferred channels. Additionally, PostgreSQL has been used to manage and store data efficiently, providing quick access to critical information. The project also involved rigorous testing with mock data to simulate real-world scenarios and ensure the system's performance under various conditions.

---

Let's make air travel smoother and more predictable for everyone! ✈️
