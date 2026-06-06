# Rebox — Second-Hand Sneaker Marketplace

An Android marketplace application for buying and selling second-hand sneakers, built with Kotlin and Firebase.

## Screenshots
<img width="635" height="1411" alt="2026-06-06 17_38_38-Rebox" src="https://github.com/user-attachments/assets/77687e23-0733-445a-8f07-08bc1a305afd" />
<img width="631" height="1409" alt="image" src="https://github.com/user-attachments/assets/20d7b72d-9692-44f9-98db-1185f8e1aeb4" />
<img width="635" height="1412" alt="image" src="https://github.com/user-attachments/assets/64f76c59-f257-4891-aa38-b4b061d590fb" />

## Features
- User Authentication (Login & Register) via Firebase
- Product listing with photo upload (Cloudinary)
- Filter & Search items
- Buy & order flow with transaction history
- User profile with store management
- Real-time chat using Firebase Cloud Messaging (FCM)
- Change password

## Tech Stack
- **Language:** Kotlin
- **Architecture:** View Binding
- **Backend:** Firebase (Auth, Firestore, FCM)
- **Storage:** Cloudinary
- **UI:** XML Layouts, Bottom Navigation

## Getting Started

### Prerequisites
- Android Studio
- Firebase project setup
- Cloudinary account

### Installation
1. Clone the repo
   ```bash
   git clone https://github.com/valmosee/Rebox-marketplace.git
   ```
2. Open in Android Studio
3. Add your `google-services.json` from Firebase Console
4. Configure Cloudinary credentials in the project
5. Build and run on emulator or device

## Team & Contribution

This project was built by 2 people. I was the one who initiated the concept and handled task delegation.

| Member | Contributions |
|--------|--------------|
| Joice | Project idea & task delegation, Login & Register,  Buy flow,  Change password, Real-time chat (FCM), Photo upload |
| Darrel | Home page, Product listing & filter/search, Transaction history, User profile & store page |

## 📄 License
This project is for educational purposes.
