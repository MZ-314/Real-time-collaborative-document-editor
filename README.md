# Real-time-collaborative-document-editor
COMPANY: CODTECH IT SOLUTIONS
NAME: MUSTAFIZ AHMED
INTERN ID: CT04WR245
DOMAIN: FULL STACK WEB DEVELOPMENT
DURATION: 4 WEEKS
MENTOR: NEELA SANTHOSH KUMAR

PROJECT LINK: https://drive.google.com/file/d/1FF7MW5p2imo5urJJ7pKJuQ3_CL_1hDpD/view?usp=sharing

Real-Time Collaborative Document Editor
This project implements a modern, web-based collaborative document editor that allows multiple users to simultaneously edit the same document in real-time. Combining the power of React for the frontend and Node.js with Socket.IO for the backend, the application provides a seamless collaborative editing experience similar to Google Docs or Notion.
Key Features

Real-Time Collaboration: Multiple users can edit the same document simultaneously, with changes instantly visible to all participants.
User Presence: See who else is currently viewing and editing the document with active user indicators.
Document Management: Create, open, save, and manage multiple documents stored in MongoDB.
Rich Text Editing: Built with Draft.js to provide a robust rich text editing experience with formatting options.
Responsive Design: Clean, intuitive interface that works well on various screen sizes.

Technical Stack

Frontend: React.js with Draft.js for rich text editing
Backend: Node.js with Express
Real-Time Communication: Socket.IO for bi-directional, event-based communication
Database: MongoDB for document storage
Styling: CSS with flexbox for responsive layouts

Architecture
The application follows a client-server architecture where:

The React frontend handles UI rendering and user interactions
Socket.IO establishes a persistent connection between clients and server
The Node.js backend coordinates changes between users and manages document storage
MongoDB provides persistent storage for documents and their content

When a user edits a document, changes are immediately sent to the server which broadcasts them to all other users viewing the same document. This creates a seamless collaborative experience where everyone sees changes in real-time.
Implementation Details

User authentication via username identification
Document rooms to isolate collaboration sessions
Efficient synchronization of document content using operational transforms
Automatic saving of documents to preserve work
Visual indicators showing who is currently active in each document

This collaborative document editor provides a solid foundation that can be extended with additional features like commenting, version history, access controls, and more advanced formatting options to create a full-featured collaborative workspace.

![Image](https://github.com/user-attachments/assets/287e03ff-4983-4dc7-81a3-b420740a2ee6)
![Image](https://github.com/user-attachments/assets/8fb273f5-552b-4a38-a3f2-a1cbe5cad6bf)
![Image](https://github.com/user-attachments/assets/570d557c-811b-417a-a6ec-9890af524560)
![Image](https://github.com/user-attachments/assets/4a069e6e-0742-4df1-87c8-61fab8034e63)
