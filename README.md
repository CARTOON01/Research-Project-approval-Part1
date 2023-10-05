### <h2>ContinuousContinuous Authentication Website</h2>

Enhancing Security Through Continuous Keystroke Authentication

<h2>Project Overview</h2>

I am Brian Ngugi, the sole member of this project, serving as the Project Lead and Full-Stack Developer. My responsibilities include overseeing the project's development and actively participating in both frontend and backend development.
Technologies

For this simple web application, I have chosen the MEAN Stack, comprising MongoDB, Express, Angular 4, and Node.js. An alternative technology stack considered was the MERN Stack, but I opted for MEAN due to my familiarity with Angular for the frontend. In terms of the database, I've selected MongoDB over PostgreSQL because of its suitability for handling unstructured data and scalability for user profiles.
Challenge Statement

The Continuous Authentication Website addresses the challenge of enhancing security through continuous monitoring and analysis of users' keystrokes to detect anomalies and verify their identities. However, it does not cover multi-factor authentication (MFA) or traditional password management. This project is designed to benefit organizations and individuals seeking an extra layer of security beyond conventional authentication methods. It is suitable for users who require continuous authentication for their accounts, and it is not dependent on any specific locale since keystroke dynamics are universally applicable.
Risks

Technical Risks:

    There is a potential impact of technical issues with data collection, analysis, or server maintenance on the system's effectiveness. To mitigate these risks, I have implemented regular testing, monitoring, and backups to ensure data integrity and system availability.

Non-Technical Risks:

    Potential risks related to user privacy concerns or legal issues tied to data collection and storage are addressed through transparent privacy policies, compliance with data protection regulations, and user consent for data collection.

Infrastructure

To manage the project's infrastructure, I have adopted a standard Git workflow, such as Gitflow or GitHub flow, for branching and merging. The project can be seamlessly deployed to Heroku. Data for user profiles is collected through user interactions, primarily keystroke dynamics, and stored securely in a MongoDB database, with strict data privacy measures in place.
Testing

Testing is a crucial aspect of this project. My testing strategy encompasses comprehensive unit and integration testing, and I leverage automation using tools like Jasmine for Angular. Sample keystroke data is employed for quality assurance, and I also apply security testing procedures to identify vulnerabilities.
Existing Solutions

While specific existing solutions are not mentioned in this document, established continuous authentication solution providers in the field include BioCatch, TypingDNA, and BehavioSec. These solutions often offer a broader range of behavioral biometrics beyond keystroke dynamics.