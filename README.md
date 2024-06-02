## Ghana Health Services Resource Hub

**Empowering Healthcare with Centralized Information**

The Ghana Health Services Resource Hub is a comprehensive solution designed to streamline access to health-related information for authorized users within the GHS. This project offers a unified platform for managing, accessing, and sharing essential documents and resources, fostering improved healthcare delivery throughout the organization.

**Components Working in Harmony**

The Resource Hub is comprised of three key components, each leveraging powerful technologies to deliver a robust user experience:

* **Web App (React & Ant Design):** This user-friendly web application serves as the central hub for resource management. Authorized users can:
    * **Upload** new health-related documents and resources.
    * **Download** existing documents for offline access.
    * **Edit** document details to ensure information remains current.
    * **Delete** documents when necessary.
    * **Navigate** through the interface with ease thanks to the intuitive design built with Ant Design.
    * (Optional) **Search** for specific resources using a powerful search functionality (to be implemented).

* **Mobile App (React Native):** Designed for on-the-go access, the mobile application empowers healthcare professionals to:
    * **Browse** and access a wide range of available health resources.
    * **Download** documents for offline use, ensuring critical information is readily available in any situation.
    * **Experience** an intuitive and user-friendly interface optimized specifically for mobile devices.

* **Backend (Express & Postgres):** The robust backend API serves as the central data hub for the entire system. It provides functionalities for:
    * **Document Management API:** This API empowers authorized users to upload, download, edit, and delete documents through well-defined endpoints.
    * (Optional) **User Management API:** This functionality can be implemented to manage user registration, login, and role-based permissions within the system.
    * (Temporary) **Authentication API:** Currently, user authentication relies on a temporary solution using email and passkey verification. This necessitates an upgrade to a more robust and secure authentication system.

**Technology Stack:**

* Web App: React, Ant Design (UI framework)
* Mobile App: React Native (cross-platform mobile development framework)
* Backend: Express.js (web framework), PostgreSQL (relational database)
* File Storage: Likely handled by the backend server (implementation details may vary depending on chosen approach)
* User Authentication: Nodemailer (temporary solution - email & passkey verification)


