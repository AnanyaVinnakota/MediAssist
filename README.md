# Smart MediAssist

**Smart MediAssist** is an intelligent healthcare assistance platform designed to help users manage their medicines, track doctor appointments, and receive basic health guidance through an AI-based caretaker assistant. The application focuses on improving medication management, healthcare awareness, and accessibility for users through a simple and user-friendly interface.

## Project Overview

Managing medicines and healthcare appointments can be difficult, especially for elderly patients or individuals who need regular medical care. Smart MediAssist provides a centralized platform where users can easily upload medicine details, receive reminders for expiry or low stock, book doctor appointments, and get general health suggestions.

The system aims to simplify healthcare management by combining medicine tracking, appointment scheduling, and AI-powered assistance in one platform.

## Features

### Medicine Management

Users can upload and manage medicine information including:

* Medicine name
* Number of tablets
* Manufactured date
* Expiry date
* Intake schedule

The system generates alerts when:

* Medicine stock is low
* Medicine is about to expire

### Doctor Appointment Booking

Users can schedule doctor appointments by selecting:

* Doctor name
* Date
* Time

Appointments can also be **rescheduled or cancelled**, and reminders are provided for upcoming visits.

### AI Caretaker Chatbot

The built-in AI caretaker chatbot provides basic health suggestions related to:

* Diet
* Exercise
* Ayurveda
* Home remedies
* Common health conditions such as cold, cough, diabetes, and blood pressure

### Medicine Ordering Links

The application provides quick access to trusted online medicine platforms including:

* Netmeds
* Tata 1mg
* Apollo 24/7

### Multi-Language Support

Smart MediAssist supports multiple languages to improve accessibility:

* English
* Telugu
* Hindi

### Alert and Reminder System

The system notifies users about:

* Medicine expiry dates
* Low tablet count
* Upcoming doctor appointments

### App Sharing

Users can easily share the application with others using a built-in share option.

## Technologies Used

The project uses a combination of modern web and application technologies:

* **Frontend:** HTML, CSS, JavaScript, Flutter
* **Backend:** Python
* **AI Components:** Basic NLP for chatbot responses
* **Data Storage:** Local Storage / Structured Database
* **Tools & Platforms:** GitHub, GitHub Pages, Flutter SDK

## System Architecture

The Smart MediAssist system is structured into several layers:

### User Interface Layer

Provides the main interface where users interact with the system to upload medicines, book appointments, and chat with the AI assistant.

### Application Logic Layer

Handles processing of user inputs, scheduling reminders, and managing application workflows.

### AI Assistance Layer

Implements a simple NLP-based chatbot that provides health-related suggestions and guidance.

### Data Storage Layer

Stores medicine information, user data, and appointment details.

## GitHub Pages Demo

A web interface demonstration of the project is available through GitHub Pages.

**Live Demo:**
`https://your-username.github.io/mediassist`

The `.html` file in this repository is used to host a simple project overview page that showcases the features and functionality of MediAssist.

## Installation

To run the project locally:

1. Clone the repository

```bash
git clone https://github.com/your-username/mediassist.git
```

2. Navigate to the project directory

```bash
cd mediassist
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Run the application

```bash
python app.py
```

## Future Improvements

* Integration with real-time health monitoring devices
* Advanced AI-based medical recommendations
* Integration with hospital management systems
* Multilingual chatbot support
* Secure patient data encryption

## Contributing

Contributions are welcome. If you would like to improve MediAssist, feel free to fork the repository and submit a pull request.

## License

This project is intended for academic and research purposes.

