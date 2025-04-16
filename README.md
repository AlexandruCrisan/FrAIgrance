# FrAIgrance 🌸༄👃
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwindcss&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=green) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![Auth0](https://img.shields.io/badge/Auth0-EB5424?style=for-the-badge&logo=auth0&logoColor=white) ![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)

**FrAIgrance** is an AI-powered platform that generates immersive, emotion-driven stories based on a fragrance's description and its brand identity. Designed to capture the soul of a scent, FrAIgrance transforms fragrance concepts into rich narratives that resonate with feeling and creativity.

![error image](https://github.com/AlexandruCrisan/FrAIgrance/blob/master/main.PNG?raw=true) 

---

## 🔗 Repositories

- 🌐 **Frontend (React + TailwindCSS + DaisyUI):** [FrAIgrance Frontend](https://github.com/AlexandruCrisan/FrAIgrance-fe)
- ⚙️ **Backend (Django + PostgreSQL):** [FrAIgrance Backend](https://github.com/AlexandruCrisan/FrAIgrance-be)

---

## 🌟 Features

- 🔐 **Google Authentication** via Auth0
- 💰 **Stripe integration** to buy credits for generation
- 🧠 **AI-powered story generation** using ChatGPT 3.5-turbo
- 📱 **Responsive UI** designed with TailwindCSS and DaisyUI
- 🗃️ **Robust backend** with Django & PostgreSQL

---

## 🛠️ Tech Stack

| Category       | Tech Used                                      |
|----------------|------------------------------------------------|
| **Frontend**   | ReactJS, TailwindCSS, DaisyUI                  |
| **Backend**    | Django (Python), PostgreSQL                    |
| **Auth**       | Auth0 with Google login, JWT-based validation  |
| **Payments**   | Stripe                                         |
| **AI**         | OpenAI's GPT-3.5-turbo                         |

---

## 🧠 How Story Generation Works

Users fill out a form detailing their fragrance preferences — mood, season, notes, etc. This data is sent to the backend, where it's passed into a prompt for OpenAI’s GPT-3.5-turbo. The result? A personalized scent narrative crafted with language and emotion, tailored to their input.

---

## 🔑 Authentication Flow

FrAIgrance uses **Auth0** to allow users to sign up or log in with their Google account. Once authenticated:

1. A JWT token is issued to the frontend.
2. The frontend stores it and uses it in each request.
3. The backend validates the token for secured operations like generation and purchasing.

---

## 💳 Payments

Using **Stripe**, users can buy "credits" which are required to generate stories. These credits are tracked in the backend and deducted per generation.

---

## [🎬 Demo Video](https://youtu.be/Ch4vuQ4F09I)


Click the link above to watch FrAIgrance in action!

## 📸 Screenshots

![error image](https://github.com/AlexandruCrisan/FrAIgrance/blob/master/p1.PNG?raw=true) 
![error image](https://github.com/AlexandruCrisan/FrAIgrance/blob/master/p3.PNG?raw=true) 
![error image](https://github.com/AlexandruCrisan/FrAIgrance/blob/master/p2.PNG?raw=true) 

---

## 📜 License

This project is licensed under the MIT License.

---

> Made with 💐 by [Crisan Alexandru](https://github.com/AlexandruCrisan)
