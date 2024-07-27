# InnerFriend - journal writing app

InnerFriend simplifies journal writing by allowing users to write on-the-go, add visual elements through image uploads or AI-generated images, and organize their entries for easy reflection.

## Motivations
* Addressing Limitations: InnerFriend aims to tackle the drawbacks of traditional journaling methods, offering improved convenience, organization, and accessibility for users.
* Minimalistic Design Focus: By prioritizing simplicity and minimizing distractions (no ads or other services such as guided meditation), InnerFriend provides an environment that allows users to focus solely on writing, thoughts, and reflections.
* Enhanced Journaling Experience: Through its user-friendly platform and simplified design, InnerFriend aims to enhance the journaling experience, encouraging consistent and meaningful self-expression and reflection.

## Project aims and objectives
To develop a complete mobile application that enables users to write journals more interactively and conveniently. In addition to journal entries of text and images, AI features of text to speech/speech to text and image generation were incorporated to further elevate user engagement.

## App features
* **User Authentication**: create an account, log in securely, and manage personal information.
* **Diary Entry Creation**: writing text (title, content, etc), adding images (upload from local or generated by AI)
* **Viewing the past entries**: seeing journals in list view, select a particular journal to view details
* **Image gallery**: view collection of uploaded/generated images
* **Edit/Delete journal**: update text/image or completely remove the entry.
* **Privacy and Security**: Users' personal information and diary entries should be securely stored and protected from unauthorized access.

## Technologies used
* **Frontend**: Built using the React Native framework for an interactive and responsive user interface.
* **Backend**: Utilized NodeJS and ExpressJS for robust backend development.
* **Database**: MongoDB for efficient data storage and retrieval.
* **Additional Services**: Integrated Firebase Store for image storage and leveraged OpenAI's Dalle model for image generation
  
<div align="center"><img width="452" alt="image" src="https://github.com/user-attachments/assets/2426dbfa-c333-4c2e-8b15-77c315adbc55"></div>

## System architecture
1. Life cycle without backend interaction: A1 -> A5
2. Life cycle with backend interaction: A1 -> A2 -> B1 -> B5 -> A3 -> A4 ->A5
3. Life cycle with extended services: A1 -> A2 -> C1 -> C2 -> A3 -> A4 -> A5
4. Interact with Firebase service: A1 -> A2 -> D1 -> D2 -> A3 -> A4 -> A5

<div align="center"><img width="452" alt="image" src="https://github.com/user-attachments/assets/58d645f9-dedd-4e00-88cb-fb2bf2d02e17"></div>

## UMl Use case diagram 
<div align="center"><img width="452" alt="image" src="https://github.com/user-attachments/assets/c4508ca1-b693-4682-aa5d-5fe86a2adcc9"></div>

## Demo
<div align="center">
  <img width="230" alt="Screenshot 2024-07-27 at 1 18 41 PM" src="https://github.com/user-attachments/assets/d38541ac-dfc2-4107-a9ac-895cd90f2ea2">
  <img width="230" alt="Screenshot 2024-07-27 at 8 39 15 AM" src="https://github.com/user-attachments/assets/9a38cf48-192a-4ca3-b3bf-e14b019e9fb7">
  <img width="230" alt="Screenshot 2024-07-27 at 8 39 24 AM" src="https://github.com/user-attachments/assets/ce060d17-073d-4982-8f50-a0d49e2bc283">
  <img width="230" alt="Screenshot 2024-07-27 at 10 19 54 AM" src="https://github.com/user-attachments/assets/1a241430-bb2e-42fc-9ab2-f55767152f72">
</div>

<div align="center">
<img width="230" alt="Screenshot 2024-07-27 at 1 16 47 PM" src="https://github.com/user-attachments/assets/c25958d3-5bfc-4648-b448-60bbabdffa6c">
<img width="230" alt="Screenshot 2024-07-27 at 1 26 35 PM" src="https://github.com/user-attachments/assets/8a386a6a-ba66-43a2-a9d1-42218f556dff">
<img width="230" alt="Screenshot 2024-07-27 at 1 26 44 PM" src="https://github.com/user-attachments/assets/6839f0ef-a86f-4129-abba-eb17f4a5f492">
<img width="230" alt="Screenshot 2024-07-27 at 1 26 28 PM" src="https://github.com/user-attachments/assets/f4de044a-c904-4dee-941a-a69eb91cb044">
<img width="230" alt="Screenshot 2024-07-27 at 1 20 39 PM" src="https://github.com/user-attachments/assets/62ce77f7-b2ab-4e26-987e-d0ff30266cc3">
</div>

## Getting started
1. Clone the repository.
2. Install the necessary dependencies by "npm install" in the root directory and root/api.
3. Set up MongoDB database.
4. Set up Firebase Fire store.
5. Create API key for using Open AI Dalle 2 model.
6. Create .evn files and add API keys used for both backend and frontend.
7. Begin your journaling journey with InnerFriend!



