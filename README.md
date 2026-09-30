# Online-Hobby-Skills-Tracker-with-Community-Sharing-on-Cloud
A Google Colab-ready Hobby &amp; Skills Tracker that combines HTML, CSS, JavaScript, local storage, charts, login, and an interactive dashboard into one runnable cell. Track hobbies, skills, progress, goals, and activities directly in your browser.
# Hobby & Skills Tracker

A lightweight, interactive web application for tracking hobbies, developing skills, setting goals, and monitoring personal progress. The project is designed to run directly in **Google Colab** using a single executable cell.

## 🚀 Features

* 📊 Interactive dashboard for tracking progress
* 🎯 Set and monitor personal goals
* 🧩 Manage hobbies and skills
* 📈 Visualize progress with interactive charts
* 💾 Store data using browser `localStorage`
* 🔐 Simple demo login system
* 📱 Responsive web interface
* ⚡ Runs entirely from a single Google Colab cell
* 🌐 No separate web hosting or installation required

## 🛠️ Technologies Used

* **HTML5** – Application structure
* **CSS3** – Responsive styling and interface design
* **JavaScript** – Application logic and interactivity
* **Chart.js** – Data visualization
* **Browser LocalStorage** – Client-side data persistence
* **Python** – Local web server and Google Colab integration

## 📂 Project Structure

The project is packaged so that the complete application can be launched from one Google Colab cell.

```text
Hobby & Skills Tracker
│
├── HTML
├── CSS
├── JavaScript
├── Chart.js
├── LocalStorage
└── Google Colab Launcher
```

## ▶️ Running in Google Colab

1. Open the provided `.ipynb` notebook in Google Colab.
2. Run the single code cell.
3. The application will automatically:

   * Create the HTML application.
   * Start a local web server.
   * Open the tracker inside Colab.
4. Use the application through the displayed interface.

No additional installation or configuration is required.

## 🔑 Demo Login

The application includes a demonstration login:

```text
Username: alice
Password: demo1234
```

> The demo credentials are intended for demonstration purposes only and should not be used for production authentication.

## 💾 Data Storage

User-entered information is stored locally in the browser using **LocalStorage**.

This means:

* Data persists between browser sessions on the same browser.
* Data is stored on the user's device/browser.
* No external database is required.
* Clearing browser storage may remove saved application data.

## 📊 Dashboard

The dashboard provides an overview of tracked hobbies and skills, allowing users to monitor their development and visualize progress through charts and statistics.

## 🔒 Security

This project is intended as a personal/demo application. The included login system is **not a production-grade authentication system**.

For a production deployment, authentication should be replaced with a secure backend system using password hashing, session management, authorization, and appropriate security controls.

## 🌐 Deployment

The application can be adapted for deployment outside Google Colab by hosting the HTML, CSS, and JavaScript components on a web server or static hosting platform.

For the current version, Google Colab provides a convenient environment for running and demonstrating the application without additional setup.

## 📌 Use Cases

The Hobby & Skills Tracker can be used for:

* Personal skill development
* Hobby management
* Goal tracking
* Learning progress monitoring
* Portfolio demonstrations
* Academic projects
* Web development demonstrations

## 🔮 Future Improvements

Potential enhancements include:

* User registration and secure authentication
* Cloud database integration
* Multi-user support
* Export/import functionality
* Advanced analytics
* Progress reminders and notifications
* Mobile application support
* Cloud synchronization
* Custom themes and personalization

## 📄 License

Add your preferred open-source license here, such as **MIT**, if you intend to distribute the project publicly.

## 👤 Author- Debankita Panja

Developed as an interactive **Hobby & Skills Tracker** project designed for easy execution and demonstration through Google Colab.
