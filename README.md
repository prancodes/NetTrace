# NetTrace – IP Address Finder 🔍

**NetTrace** is a lightweight Java-based desktop application that helps you:
- 🔎 Find the IP address of any website/domain.
- 💻 View your own system's local IP address.

Built using **Java Swing GUI** and the **InetAddress** class.

---



## 🚀 Features

- Input any website (e.g., `www.google.com`) to fetch its IP address.
- Detect your local machine's IP address with one click.
- Smooth, clean interface using Java Swing.
- Works offline for local IP detection.

---

## 🛠️ Tech Stack

- Java 17+ (or compatible JDK)
- Java Swing (GUI Framework)
- InetAddress (Java Networking API)

---

## 📦 Folder Structure

```
NetTrace/
├── src/
│   └── main/
│       ├── java/
│       │   └── netPackage/
│       │       └── IpFinder.java
│       └── resources/
│           └── assets/
│               └── app.ico
├── .gitignore
├── pom.xml
└── README.md
```

---

## 🚀 How to Run

Run this Java Swing project easily via terminal — no IDE required!


### ✅ Steps:

1. **Open terminal or command prompt**

2. **Clone or download this repository**

   - Using Git:
     ```sh
     git clone https://github.com/prancodes/NetTrace.git
     ```
   - OR download ZIP from GitHub and extract it.

3. **Navigate to the project folder**:
   ```sh
   cd NetTrace
    ```
4. Compile the code:
    ```sh
    javac -d target/classes src/main/java/netPackage/IpFinder.java
    ```
5. Run the app:
    ```sh
    java -cp target/classes netPackage.IpFinder
    ```

---


## 🧑🏻‍💻 Author

< Made by Pranjal Singh />

---

