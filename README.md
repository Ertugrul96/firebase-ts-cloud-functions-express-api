## 🚀 Cloud Functions for Firebase: Typescript ile NoSQL Veri Modellemesi

### 🎯 Project Vision and Architectural Focus

I initiated this project to demonstrate robust expertise in building a highly scalable **Serverless Social Media API** using **TypeScript**. The core objective was to showcase proficiency in **NoSQL data modeling** within **Firestore** and implement a strong **event-driven** architecture.

**My key development goals included:**

* **Data Consistency:** Proving my ability to manage complex, relational data effectively within a **NoSQL (Firestore)** environment, complementing my experience in traditional **SQL/PostgreSQL** systems.
* **Event-Driven Design:** Leveraging **Cloud Functions Triggers** to ensure the application automatically responds to complex events (likes, follows) in real-time.
* **Scalability:** Structuring the entire microservice foundation for seamless integration with high-performance tools like **Kafka** and **Redis**.

---

### 🛠️ Key Capabilities & Technology Stack

This solution exemplifies a best-practices approach to Serverless development, highlighting key technical strengths:

* **Platform & Serverless:** **Firebase Cloud Functions (2nd Gen)**—Mastery of scalable, cloud-native backend deployment.
* **Database:** **Cloud Firestore**—Demonstrates expertise in advanced **NoSQL Data Modeling** and indexing for large-scale social network relationships.
* **Language:** **TypeScript**—Utilized throughout the codebase to guarantee type safety, maintainability, and enterprise-level reliability.
* **Asynchronous Processing:** The event-driven nature (using Firestore triggers) confirms a strong understanding of patterns highly compatible with **Kafka** for resilient microservice communication.
* **Performance:** The architecture is intentionally designed for future integration with **Redis** to handle high-speed caching of frequently accessed data.

---

### 📝 Functional Architecture and Data Consistency

I engineered the following critical workflows using Firestore triggers and dedicated functions to ensure data consistency and real-time user experience:

* **User Feed Management:** Functions were implemented to update user feeds instantly when they follow or un-follow another user.
* **Real-time Notifications:** Developed systems to automatically update the user's Events collection and send notifications when their posts receive a like or comment.
* **Data Denormalization & Integrity:** Created logic to automatically and consistently update denormalized data (e.g., user profiles) across all related collections (posts, comments) when a user changes their profile information.

---

### 💡 Justification of Technology Choices

#### Why Firestore?

I chose Firestore for its inherent **NoSQL flexibility** and its support for real-time listeners, which are crucial for a social application. This approach contrasts with, and complements, my experience in **SQL** systems by focusing on high-read performance and horizontal scaling necessary for dynamic web services.

#### Why TypeScript?

**TypeScript** was non-negotiable for this project. Given the complexity of the serverless triggers and data manipulation, TypeScript's strong typing guarantees reliability and prevents runtime errors. This ensures a clean, consistent, and robust codebase, reflecting my commitment to high-quality software engineering practices.

---

### 💻 Instructions (Setup & Deployment)

1.  Clone this repository.
2.  Set `firebase-tools` to use your project with `firebase use <YOUR_PROJECT>`.
3.  Move inside the `functions\` folder.
4.  Update your dependencies with `npm install`.
5.  Deploy your functions with `npm run deploy`.