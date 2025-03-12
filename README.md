# DevShowCase - My Android Portfolio 🚀  

## 📌 About the Project  
**DevShowCase** is an Android application designed to **showcase my skills as an Android developer**.  
This project serves as a **portfolio for recruiters and technical professionals** who want to learn more about my work.  

The goal is to build a **functional and scalable** app using **modern Android technologies and best practices**.  
It incorporates **MVVM architecture, design patterns, automated testing, safe navigation, dependency injection, and more**.  

---

## 🛠️ Technologies Used  

This project leverages a modern technology stack to ensure **quality, scalability, and performance**:  

### **Tech Stack**  
- **Kotlin**: Official language for Android development.  
- **Coroutines & Flow**: For efficient asynchronous operations and reactivity.  
- **Jetpack Compose**: Modern declarative UI framework.  
- **Material Theme 3**: Updated and native Android design.  
- **Hilt**: Dependency injection for modularity.  
- **Firebase Authentication**: Login with Google and Email/Password.  
- **Firebase Firestore**: Cloud storage for favorites.  
- **Firebase Crashlytics**: Error monitoring and crash reporting.  
- **Firebase Functions (Planned)**: For backend logic execution.  
- **Room Database**: Offline storage for favorites.  
- **Retrofit**: REST API consumption (GitHub API).  
- **Paging 3**: Efficient paginated list loading.  
- **Coil**: Efficient image loading (GitHub avatars).  
- **Jetpack Navigation**: Safe navigation between screens.  

---

## 🏛️ Architecture  

The project follows the **MVVM (Model-View-ViewModel) architecture** to separate concerns and improve maintainability:  
- **Data Layer**: Repositories, data sources (Firestore, Retrofit, Room), and DTOs.  
- **Domain Layer**: Use Cases encapsulating business logic.  
- **Presentation Layer**: ViewModels and UI using Jetpack Compose.  

✅ This approach enhances **testability** and **modularity**.  

---

## ✅ Testing  

The project includes a **robust testing suite** to ensure code reliability:  
- **Unit Tests**: Validate business logic in Use Cases and Repositories.  
- **UI Tests (Compose Testing)**: Verify UI using Jetpack Compose.  
- **Instrumentation Tests**: Simulate real user interactions.  
- **MockK**: Used for creating mocks in unit tests.  
- **JUnit**: Primary framework for test execution.  

These tests help prevent **regressions** and **unexpected issues**.  

---

## 🚀 Features  

### 1️⃣ Login & Signup  
✔️ Login with Google and Email/Password.  
✔️ Persistent user session.  

### 2️⃣ Repository Search  
✔️ Search GitHub repositories by name or technology.  
✔️ Display **stars, forks, open issues, and main language**.  
✔️ Sync **favorites with Firestore and Room**.  

### 3️⃣ Repository Details  
✔️ Show **description, main language, commit count, and contributors**.  
✔️ Open repository in a **browser**.  

### 4️⃣ Developer Exploration  
✔️ Search GitHub users.  
✔️ Display **bio, location, followers, and public repositories**.  

### 5️⃣ Dark Mode  
✔️ Toggle between **light and dark themes** using **Material Theme 3**.  

---

## 🛣️ Project Roadmap  

📌 **Phase 1 - Initial Setup**  
✅ Create GitHub repository.  
✅ Configure **Kotlin, Jetpack Compose, Hilt, and Retrofit**.  
✅ Set up **MVVM + Use Cases structure**.  
✅ Configure **GitHub API consumption**.  
✅ Set up **Firebase Authentication and Firestore**.  

📌 **Phase 2 - MVP Development**  
✅ Implement **login screen** with Firebase Auth.  
✅ Implement **repository search screen** (API + Paging 3).  
✅ Implement **repository details screen**.  
✅ Implement **developer search screen**.  
✅ Implement **favorites with Firestore (cloud) and Room (offline)**.  
✅ Implement **light/dark mode toggle**.  

📌 **Phase 3 - Refinement & Testing**  
✅ Add **Firebase Crashlytics**.  
✅ Implement **unit and UI tests**.  
✅ Refine **UI/UX with animations in Compose**.  
✅ Implement **Firebase Functions for backend logic**.  

---

## 🏗️ How to Run the Project  

### 1️⃣ Clone the repository:  
```bash
git clone https://github.com/your-username/DevShowCase.git
```

### 2️⃣ Open in Android Studio  
- Open **Android Studio**.  
- Select **File > Open...** and choose the project folder.  
- Wait for Gradle to sync and index the project.  

### 3️⃣ Compile and run on an emulator or physical device  
- Choose a target **emulator** or **connect a real device**.  
- Click on **Run ▶️** in Android Studio.  
- Ensure **Firebase services** are configured if applicable.  

### ⚙️ Requirements  
- ✅ **Android Studio Flamingo** or newer  
- ✅ **JDK 11+**  
- ✅ **Firebase configured**  

---

## 📸 Screenshots  
### 2️⃣ Open in Android Studio  
- Open **Android Studio**.  
- Select **File > Open...** and choose the project folder.  
- Wait for Gradle to sync and index the project.  

### 3️⃣ Compile and run on an emulator or physical device  
- Choose a target **emulator** or **connect a real device**.  
- Click on **Run ▶️** in Android Studio.  
- Ensure **Firebase services** are configured if applicable.  

### ⚙️ Requirements  
- ✅ **Android Studio Flamingo** or newer  
- ✅ **JDK 11+**  
- ✅ **Firebase configured**  

---

## 📸 Screenshots  
<img src="https://github.com/user-attachments/assets/f57b759b-08a6-47b5-ac34-3d3e8fa51385" alt="Project Screenshot" width="600"/>


---

## 📜 License  
This project is **open-source** and can be used for **learning purposes**.  
If you use it as a base, **please give credit**.  

---

## ✉️ Contact  
Interested in my work? Want to **hire me** or discuss **Android development**?  
Feel free to reach out!  

📧 **Email:** [felipe.au.pereira.santos@gmail.com](mailto:felipe.au.pereira.santos@gmail.com)  
🔗 **LinkedIn:** [linkedin.com/in/felipepsh](https://www.linkedin.com/in/felipepsh/)  

🚀 **I hope this project is useful and inspires other developers!**

---

## 📜 License  
This project is **open-source** and can be used for **learning purposes**.  
If you use it as a base, **please give credit**.  

---

## ✉️ Contact  
Interested in my work? Want to **hire me** or discuss **Android development**?  
Feel free to reach out!  

📧 **Email:** [felipe.au.pereira.santos@gmail.com](mailto:felipe.au.pereira.santos@gmail.com)  
🔗 **LinkedIn:** [linkedin.com/in/felipepsh](https://www.linkedin.com/in/felipepsh/)  

🚀 **I hope this project is useful and inspires other developers!**
