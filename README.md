# EventPulse - Event Management App
EventPulse is a demo event management app that showcases best practices in Flutter development. It demonstrates a modern approach to handling forms, custom views, third-party library integration, Firebase features, and API calls. This project is designed to highlight the ability to create efficient, scalable, and user-centric applications using Flutter.

# Features
## Core Functionalities:
1. Event Browsing

Users can browse upcoming events fetched via the Eventbrite API.
Event details such as title, date, time, and description are displayed in a clean, intuitive layout.

2. RSVP Management

Users can mark events as "Interested" or RSVP to receive reminders.
Firebase Cloud Messaging is used to send reminders for RSVP'd events.

3. Custom Views

A custom card layout for event listings.
Custom-designed RSVP status chips (Interested, Going).


4. Search Functionality

Users can search for events by keywords or categories using Eventbrite's search API.


5. Push Notifications

Firebase Cloud Messaging is implemented to send real-time notifications for event updates or reminders.


6. Event Filters

Users can filter events by date, location, and category.

# Additional Functionalities:

## Form Handling

A simple feedback form to collect user opinions about events, integrated with Firebase Firestore for backend storage.

## Favorites Management

Users can add events to their favorites list, saved locally using shared preferences.

# Architecture
This project follows the Clean Architecture pattern for better code organization and scalability:

Presentation Layer: Flutter Widgets for UI.

Domain Layer: Business logic and use cases.

Data Layer: Handles API integration and Firebase interactions.


# Tech Stack
1. Flutter & Dart

The primary framework for building the application.

2. Firebase Integration

Firebase Cloud Messaging for notifications.
Firebase Firestore for storing feedback forms.

3. Third-Party Libraries

Eventbrite API for fetching event data.
Flutter Local Notifications for in-app reminders.

4. UI Design

Leveraging Flutter's widget library to create responsive, custom layouts.

5. State Management

Provider for state management.
