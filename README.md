 # 🔗 URL Shortener Service

A simple **Java Console-Based URL Shortener Service** that converts long URLs into short, shareable links. The application uses a random short-code generation system and stores URL mappings using Java Collections.

---

## ✨ Features

- 🔗 Convert Long URLs into Short URLs
- 🚀 Redirect Short URLs to Original URLs
- 🔐 Unique Short Code Generation
- 📋 View All Stored URL Mappings
- ⚡ Fast URL Lookup Using HashMap
- 🖥️ Console-Based User Interface

---

## 🛠️ Technologies Used

- Java
- HashMap Collection Framework
- Random Class
- StringBuilder
- Scanner Class

---

## 📂 Project Structure

```
URL-Shortener-Service/
│
├── URLShortenerService.java
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/url-shortener-service.git
```

### 2. Navigate to Project Folder

```bash
cd url-shortener-service
```

### 3. Compile the Program

```bash
javac URLShortenerService.java
```

### 4. Run the Application

```bash
java URLShortenerService
```

---

## 📋 Application Menu

```
===== URL Shortener Service =====

1. Shorten URL
2. Redirect to Original URL
3. Show All URLs
4. Exit

Enter your choice:
```

---

## 🔍 How It Works

### 1. URL Shortening

The user enters a long URL:

```
https://www.example.com/my-long-web-page
```

The system generates a unique short code:

```
aB92xK
```

The generated short URL becomes:

```
http://short.ly/aB92xK
```

---

### 2. URL Redirection

The user enters the short code:

```
aB92xK
```

The system searches the stored database and returns:

```
Redirecting to:
https://www.example.com/my-long-web-page
```

---

## 🧱 Core Components

### URL Database

The application uses:

```java
HashMap<String, String>
```

to store:

```
Short Code → Original URL
```

Example:

```
aB92xK → https://example.com
```

---

### Short Code Generator

The application generates random 6-character codes using:

- Lowercase letters
- Uppercase letters
- Numbers

Example:

```
xY7pQ2
```

---

## 📊 Data Structures Used

| Data Structure | Purpose |
|---------------|---------|
| HashMap | Stores URL mappings |
| StringBuilder | Creates short codes |
| Random | Generates unique codes |

---

## 💻 Sample Output

```
===== URL Shortener Service =====

1. Shorten URL
2. Redirect to Original URL
3. Show All URLs
4. Exit

Enter your choice: 1

Enter Long URL:
https://github.com/example/project

Short URL:
http://short.ly/A8kP92
```

---

## 🧠 OOP & Java Concepts Used

- Classes and Objects
- Static Methods
- Encapsulation
- Collections Framework
- Exception Handling
- Loop Control
- User Input Handling

---

## 🔮 Future Enhancements

- 🌐 Real Web-Based Redirection
- 💾 Database Storage (MySQL/MongoDB)
- 👤 User Accounts
- 📊 URL Click Analytics
- ⏳ URL Expiration
- 🔒 Custom Short Links
- 📱 REST API Integration
- ☁️ Cloud Deployment

---

## ⚠️ Current Limitations

- URLs are stored only in memory.
- Data is lost after program termination.
- Short URLs work only inside the application.
- No actual browser redirection server is implemented.

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Commit your changes.
5. Push your branch.
6. Open a Pull Request.

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

**MADHVEDNRA PANDEY**
 
