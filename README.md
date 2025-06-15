# 💬 ABHI-VAADAN – Video Chat App

A full-stack video conferencing platform modeled after Microsoft Teams, developed as part of the Microsoft Engage 2021 program, enabling seamless real-time communication and collaboration.

---

## 👩‍💻 Author

**Shivangi Chauhan**

---

## 🧠 About the Project

**ABHI-VAADAN** is a video chat app that simplifies virtual meetings. It allows users to create or join meetings, with secure login and features like live chat, peer-to-peer video, and user notifications.  

It replicates core functionalities of platforms like Microsoft Teams, offering a seamless video-calling experience with integrated chat and authentication.

---

## 🚀 Features

- ✅ **Create or Join Meetings** via secure room links.
- 🔒 **User Authentication** using Auth0.
- 🎥 **Video & Audio Toggle** during calls.
- 💬 **Real-Time Chat** using Socket.IO.
- 👥 **Multiple User Support** with user join notifications.
- 🔗 **Shareable Room Links** via modal popup.
- 🧭 **Smooth Navigation** with clear UI/UX.

---

## 🛠️ Technologies Used

| Functionality       | Stack / Tools Used                        |
|---------------------|-------------------------------------------|
| **Video Calling**   | PeerJS, WebRTC                            |
| **Authentication**  | Auth0 SDK                                 |
| **Real-Time Chat**  | Socket.IO                                 |
| **UI/UX**           | HTML, CSS, JavaScript, EJS Template Engine|
| **Backend**         | Node.js, Express                          |

---

## 📸 Screenshots
- **Home Page**
![image](https://github.com/user-attachments/assets/41a7c8a8-fb7b-4997-8d96-056f33ecee39)

- **Authentication Page**
  
    ![authentication](https://github.com/user-attachments/assets/e644a959-16d1-4712-a9b0-1908cbc89d93)

- **Chat View**
![Chat view](https://github.com/user-attachments/assets/c4756c35-883f-40b1-8120-bfbf9456bf94)

- **Room View**
![room page](https://github.com/user-attachments/assets/93fc6510-9db5-4f3a-9399-5837131c3562)

- **Multiple Users**
![multipleusersgood](https://github.com/user-attachments/assets/b0ad173e-f852-4407-a27c-53353db55c18)







---

## 🧩 Application Overview

- **Home Page**  
  - `New Meeting` to start a call  
  - `Join` to enter an existing room  
  - `Logout` to exit securely

- **Authentication**  
  - Protected room access using Auth0 to ensure privacy.

- **Room Page Features**
  - 🔊 Audio/Video toggles  
  - 💬 Chat toggle  
  - ➕ Add user modal with room link  
  - ❌ End call confirmation with redirect

- **Live Chat**
  - Chat displays username & timestamp  
  - Real-time updates with message push

- **New User Notifications**
  - Real-time alert when new users join a room

---

## 🖥️ Setup Instructions

```bash
# Clone the repo
git clone https://github.com/Flaming-Phoenix24/ABHI-VAADAN.git

# Navigate to project directory
cd ABHI-VAADAN

# Install dependencies
npm install

# Run the server
npm start
