# Halo

Halo is a comprehensive Catholic faith platform designed to support and inspire users in their spiritual journey. With features like a guided virtual Rosary, Bible study tools, church activity finder, and spiritual growth tracking, Halo offers an interactive and engaging experience for users to deepen their faith and stay connected with their church community.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Virtual Rosary and Prayer Guide**: Guided Rosary with audio and visual aids, available in English and Spanish.
- **Prayer Library**: Access a collection of Catholic prayers and chants for personal or group prayer.
- **Bible Study**: Multiple Bible versions with interactive reading plans, commentary, and audio passages.
- **Church Finder**: Locate nearby Catholic churches with details on Mass times, confessions, and special activities.
- **Confessional Scheduling**: Schedule confession appointments with reminders.
- **Spiritual Growth Tracking**: Set and track goals for Bible reading, prayer frequency, and church attendance.
- **Community and Donations**: Connect with parishioners for group prayers and make secure donations to churches.
- **Real-Time Notifications**: Alerts about upcoming church events, Mass times, and prayer reminders.

## Tech Stack

### Backend

- **Node.js** with **TypeScript**: For server-side scripting and type safety.
- **Express.js**: For building RESTful APIs.
- **MongoDB** with **Mongoose**: To handle diverse and complex data like prayers, Bible readings, and user journals.

### Front-End

- **React** with **TypeScript**: For building an interactive and responsive user interface.
- **Redux Toolkit**: For managing state such as user progress, reminders, and Bible study plans.

### API

- **GraphQL**: For flexible querying of content like Bible verses, prayers, and user-generated data.

### Authentication

- **JWT (JSON Web Tokens)**: For secure, stateless user authentication.
- **OAuth 2.0** : For integrating social logins like Google or Facebook.

### Media and Audio

- **AWS S3** or **Cloudinary**: For storing and streaming audio/visual content like Rosary guides and Bible readings.

### Scheduling and Geolocation

- **Google Maps API**: For finding nearby churches and events.
- **FullCalendar.js**: For managing and displaying church schedules.

### Payment Integration

- **Stripe** or **PayPal**: For handling secure donations.

### Notifications

- **Firebase Cloud Messaging (FCM)**: For push notifications about reminders and church events.

### CI/CD

- **GitHub Actions**: For automated testing, building, and deployment.

### Containerization

- **Docker**: For consistent environment setup and deployment.

### Cloud Platform

- **Google Cloud Platform (GCP)**
  - **Google App Engine**: For app deployment and scaling.
  - **Firebase**: For real-time database if needed for community features.
  - **Firestore**: For handling user-generated content like reflections and journals.

### Testing

- **Jest**: For unit and integration testing.
- **React Testing Library**: For frontend component testing.
- **Cypress**: For end-to-end testing.

## Usage

1. **Virtual Rosary**: Use the guided Rosary with audio and visual aids to deepen your prayer experience.
2. **Explore the Prayer Library**: Access a variety of prayers and chants for personal or group worship.
3. **Bible Study**: Follow interactive Bible reading plans, listen to audio passages, and reflect on daily verses.
4. **Find Churches**: Use the church finder to locate nearby Catholic churches and view their Mass schedules and events.
5. **Track Your Growth**: Set spiritual goals and track your progress with visual charts.
6. **Community Engagement**: Join group prayers, share intentions, and participate in church activities.
7. **Donate Securely**: Make secure donations to churches or specific causes directly through the app.

## License

Halo is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

Alexis San Javier - [ucfknight2017@gmail.com](mailto:ucfknight2017@gmail.com)

- **Website**: [alexissj.net](https://www.alexissj.net)
- **LinkedIn**: [linkedin.com/in/alexissj](https://linkedin.com/in/alexissj)
