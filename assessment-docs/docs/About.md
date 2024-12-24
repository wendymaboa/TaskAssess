# About 📑
## Project Plan
### Objective.
Develop a custom mobile app for FitLife Studios to enhance customer experience.
### Phases and Tasks and Milestones.
#### 1. Project Initiation / Discovery
- **Duration**: week 1
- **Tasks**:
  - Meet with FitLife stakeholders(Studio Manager, Brand Manager, Lead Trainer, IT Consultant).
  - Define project scope and objectives.
  - Set up the project team and communication channels.
  - Create the project timeline and budget plan.
- **Deliverables**: Project initiation document, project timeline.

#### 2. Requirements Gathering
- **Duration**: Weeks 2-3
- **Tasks**:
  - Conduct meeting with stakeholders to discuss and understand the business goals and user needs.
  - Document requirements for features(user accounts,booking system,payment system, push notification).
  - Define integrations with third-party services (perharps the the stakeholders would like to use paypal for payments).
  - Identify scalability requirements for future user growth (FitLife currently has 1000 users but has the potential of growing so the app has to accomodate that).
- **Deliverables**: Requirements Document.
- **Dependencies**: Input from all stakeholders, The IT consultant needs to be available fot the system integration details.

#### 3. UX/UI Design
- **Duration**: Weeks 4-5
- **Tasks**:
  - Develop wireframes and prototypes for key app screens (login, user profile, booking, payment, workout progress, notifications and alerts).
  - Create user flow diagrams.
  - Gather feedback from stakeholders and iterate on designs.
  - Ensure the design is responsive for both iOS and Android.
- **Deliverables**: Wireframes, Interactive prototype, UI design documentation.
- **Dependencies**: Design feedback and approval from stakeholders. Design should be User-friendly and intuitive.

###### 🏆 Milestone 1: Wireframe approval
#### 4. Mobile App Development (iOS and Android)
- **Duration**: Weeks 6-10
- **Tasks**:
  - Set up development environments and define tools for iOS and Android.
  - Start with the core features such as user account creation, class booking, and fitness tracking.
  - Integrate the booking system with Mindbody or Acuity Scheduling API
  - Implement payment system integration (Stripe/PayPal).
  - Set up push notifications for reminders and updates.
  - Perform unit testing during development.
- **Deliverables**: MVP build (iOS and Android), functional integrations.
- **Dependencies**: Integration with third-party services (Mindbody, Stripe/PayPal), availability of APIs and documentation.

###### 🏆 Milestone 2: MVP Build Completion.

#### 5. Backend Development (API and Database)
- **Duration**: Weeks 6-9
- **Tasks**:
  - Design and set up backend infrastructure and tools (API, database, authentication).
  - Integrate with the third-party booking and payment systems.
  - Implement data storage and security for user accounts and payment information.
  - Test backend APIs for performance and security.
- **Deliverables**: Backend API documentation, database schema, working API endpoints.
- **Dependencies**: Coordination with mobile app developers, third-party system integration.

#### 6. Testing
- **Duration**: Weeks 11-12
- **Tasks**:
  - Unit testing for individual components.
  - Integration testing to ensure smooth communication between app features and backend services.
  - User Acceptance Testing (UAT) with FitLife stakeholders.
  - Bug fixing and performance optimization.
  - Conduct load testing to simulate app performance under expected user load (1,000 users).
- **Deliverables**: Test reports, UAT feedback, final bug fixes.
- **Dependencies**: Availability of the app and backend system for testing.

###### 🏆 Milestone 3: UAT sign-off

#### 7. Deployment to App Stores
- **Duration**: Weeks 13-14
- **Tasks**:
  - Prepare app store assets (screenshots, app descriptions, and keywords).
  - Submit the app to the Apple App Store and Google Play Store for review. (takes longer for google playstore to review the app)
  - Address any feedback or issues raised during the review process.
  - Ensure compliance with app store guidelines.
- **Deliverables**: Published app on the App Store and Google Play.
- **Dependencies**:  App approval from Apple and Google.

###### 🏆 Milestone 4: App Store Submission

#### 8. Post-launch Support
- **Duration**: Months 2-6
- **Tasks**:
  - Monitor app performance and user feedback.
  - Address any bugs or issues raised by users.
  - Provide regular updates for bug fixes and minor enhancements.
  - Implement new features based on user feedback.
- **Deliverables**:  Post-launch support report, app updates.
- **Dependencies**:  User feedback, app monitoring tools.

### Integration Considerations
- Stripe or Paypal needs to be set up early in the backend development phase.
- Integration with Mindbody or Acuity Scheduling ia essential for bookings so it must be done during the mobile app development phase
- Push notification services must be integrated after the core features are implemented. 

### Timeline.

| Phase                  | Objective                                | Start Date | Due Date    | Duration   |
|------------------------|------------------------------------------|------------|-------------|------------|
| Project Initiation     | Define the scope, stakeholders, and high-level project goals.                     | week 1      | week 2      | 1 week     |
| Requirements Gathering | Gather detailed functional and non-functional requirements.                   | week 2      | week 3      | 1 week     |
| UX/UI Design           | Design the app's user interface and experience based on requirements. | week 4     | week 5      | 1 week     |
| Mobile Development     | Develop the front-end of the mobile app for both iOS and Android platforms. | week 6     | week 10      | 4 weeks    |
| Backend Development    | Develop and integrate the backend system to handle user data, booking, and payment. | week 6     | week 9      | 3 weeks    |
| Testing                | Conduct thorough testing to ensure app functionality and performance. | week 11     | week 12     | 1 week     |
| Deployment             | Submit the app for review and approval on both iOS and Android platforms. | week 13     | week 14.5   | 1.5 weeks  |
| Post-Launch Support    | Monitor the app post-launch for issues and gather user feedback. | Month 2     | Month 6     | 4 months   |

[Download The Gannt Chart](https://docs.google.com/spreadsheets/d/1kafvYfcGw_IjjDqBUk8TvzqWyGrsG8ASci3G75kcOKo/edit?usp=sharing)

### Risks and Mitigations.
- **Delays in API Integration**: Early communication with third-party providers can help mitigate integration delays.
- **App Store Rejection**: Ensuring the app complies with Apple and Google’s guidelines can minimize rejections.

## Resource Plan

| **Role**              | **Effort Estimate** | **Weekly Hours** | **Responsibilities**                                   |
|------------------------|---------------------|------------------|-------------------------------------------------------|
| **Project Manager**    | 15% (0.6 months)   | 6 hours/week     | Oversee project, manage timelines and communication.  |
| **Business Analyst**   | 15% (0.6 months)   | 6 hours/week     | Gather requirements, draft business goals.           |
| **UX/UI Designer**     | 20% (0.8 months)   | 8 hours/week     | Create wireframes, prototypes, and polished designs.  |
| **Mobile App Developer** | 40% (1.6 months) | 16 hours/week    | Build and test iOS/Android apps, integrate systems.   |
| **Backend Developer**  | 30% (1.2 months)   | 12 hours/week    | Develop APIs, database, and integrate systems.        |
| **QA Tester**          | 20% (0.8 months)   | 8 hours/week     | Perform unit, integration, and user testing.          |

## Budget Plan

| **Role**              | **Weekly Hours** | **Total Hours** | **Hourly Rate** | **Cost**   |
|------------------------|------------------|-----------------|-----------------|------------|
| **Project Manager** x 1    | 10 hours/week     | 24 hours        | $60/hour        | $1,440    |
| **Business Analyst** x 1  | 7 hours/week     | 16.8 hours        | $50/hour        | $840     |
| **UX/UI Designer** x 2    | 10 hours/week     | 32 hours       | $60/hour        | $3,840     |
| **Mobile App Developer** x 4 | 16 hours/week   | 102.4 hours       | $40/hour        | $16,384    |
| **Backend Developer** x 4 | 12 hours/week    | 57.6 hours       | $70/hour        | $16,128     |
| **QA Tester**  x 2        | 8 hours/week     | 25.6 hours       | $40/hour        | $2,048     |
| **Total**              |                  |                 |                 | **$40,680**|


#### Additional costs

| **Category**                     | **Cost**        |
|-----------------------------------|-----------------|
| **Hardware and Software Tools**  | $5,000          |
| **Third-Party Integration**      | $8,000          |
| **App Store Fees**               | $3,000          |
| **Marketing/User Training**      | $7,000          |
| **Post-Launch Support**          | $10,000         |
| **Contingency (10% of Total Budget)** | $12,000     |
| **Total Other Costs**            | **$45,000**     |

## Reporting Template
[View Template](https://www.notion.so/Monthly-Reports-166a0ad2df5f80dbb879e757c198852d?pvs=4)
