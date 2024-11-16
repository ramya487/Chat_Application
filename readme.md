# Chat Application

## Description

This is a sophisticated chat application that allows us to perform one-on-one as well group chats. Seamlessly perform real-time chatting with users in any part of the world. With this project, hope to show how cutting-edge technology may be integrated to provide a safe, flexible messaging platform that meets the demands of contemporary communication.

## Features

- Authentication: Performed with email and password as credentials. JSON Web Tokens stored in cookies for login session management
- Search User: Functionality to search user using email or user name
- Update Profile Image: Integrated Supabase Storage to store and retrieve user profile images
- Real-time messaging: Utilised socket.io to implement messaging in real-time so that changes are reflected on the page without the need to reload
- One-on-One chat: Functionality to chat with a particular user
- Group chat: Functionality to perform chatting with a set of users simultaneously
    - Create group chat: Select members and choose group name. Proceed to create
    - Add members: Select additional members. Proceed to add.
    - Remove members: Select the member to remove. Confirm.
    - Rename group: Edit the group name. Submit
    - Exit group: Exit the group. Confirm

## Additional Points
- Loading indicators: Implemented UI to indicate if the information is being fetched/processed in the backend
- Error handling: Seamlessly handled errors in the backend and displayed appropriate messages in the frontend
- Edge case handling: Handled edge cases such as data not availability by displaying appropriate information in the UI
- Form validation: Implemented form validation using formic and yup
- Responsiveness: A responsive UI that works seamlessly across all screen sizes

## Tech Stack

- Frontend: Next.js, Typescript, Tailwind, Chakra UI, Formik, Yup, Zustand
- Backend: Node.js, Express.js, JWT, Typescript, Multer
- Database: MongoDB
- Storage: Supabase
- Real-time communication: Socket.IO

## Demo


