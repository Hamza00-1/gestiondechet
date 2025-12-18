# Gestion Déchet (Waste Management System)

[![Project Status](https://img.shields.io/badge/Status-Academic%20Project-blue.svg)](https://github.com/Hamza00-1/gestiondechet)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 🌟 Project Overview

**Gestion Déchet** is a robust desktop application developed using **C++** and the **Qt framework**. Its primary purpose is to provide a comprehensive system for managing and tracking waste-related data.

The application is designed with a focus on user experience, featuring a secure authentication system and a dedicated dashboard for operational oversight. The name "Gestion Déchet" is French for "Waste Management."

### Academic Context

This project was developed as part of the curriculum at the **École d'Ingénierie Digitale et d'Intelligence Artificielle (EIDIA)** at the **Université Euro-Méditerranéenne de Fès (UEMF)**. It serves as a practical application of C++ and object-oriented programming principles in a real-world scenario.

## ✨ Features

*   **Secure User Authentication:** Implements a secure system for user registration and login.
*   **Local User Management:** Handles user data persistence by storing credentials in a local file (`utilisateurs.txt`).
*   **Intuitive Dashboard:** A central hub providing an overview and navigation to all application features.
*   **Dedicated Waste Management Module:** A specific section (`GestionDechetsPage`) for handling and logging waste-related entries and data.

## 🛠️ Technology Stack

| Component | Technology | Purpose |
| :--- | :--- | :--- |
| **Language** | C++ | Core application logic. |
| **Framework** | Qt 5/6 | Cross-platform desktop application development and UI. |
| **Build System** | Visual Studio | Project files (`.sln`, `.vcxproj`) are configured for MSVC compilation. |
| **File Handling** | Git LFS | Used to store the main project archive (`gestiondechet.zip`). |

## 🚀 Getting Started

Follow these steps to set up and run the project on your local machine.

### Prerequisites

Before you begin, ensure you have the following installed:

1.  **Git:** For cloning the repository.
2.  **Git LFS (Large File Storage):** Essential for downloading the main project archive.
    ```bash
    # Install Git LFS (instructions vary by OS)
    git lfs install
    ```
3.  **Visual Studio:** The project is configured as a Visual Studio solution.
4.  **Qt Framework:** The appropriate Qt version (compatible with your Visual Studio installation) must be installed and configured in Visual Studio.

### Installation and Setup

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Hamza00-1/gestiondechet.git
    cd gestiondechet
    ```

2.  **Download the Project Archive (using Git LFS):**
    The core project files are contained within a large zip archive tracked by Git LFS. You must pull the actual file content:
    ```bash
    git lfs pull
    ```
    *This command will download the `gestiondechet.zip` file.*

3.  **Extract the Project Files:**
    Unzip the archive to reveal the project structure. It is recommended to extract it into a new folder to keep the repository root clean.
    ```bash
    unzip gestiondechet.zip -d extracted_project
    ```
    *Note: The actual project files (including the `.sln` file) are likely inside the extracted folder.*

### Running the Application

1.  **Open the Solution:**
    Navigate to the extracted folder and open the main solution file in Visual Studio:
    ```
    extracted_project/gestiondechet/gestiondechet.sln
    ```

2.  **Configure and Build:**
    *   Ensure your Visual Studio project settings are correctly configured to link against your installed Qt libraries.
    *   Select the desired configuration (e.g., `x64-Debug`).
    *   Build the solution (`Build > Build Solution`).

3.  **Execute:**
    Run the application directly from Visual Studio (`Debug > Start Debugging` or `F5`).

## 📂 Project Structure

The main application logic is found within the extracted project folder:

| File/Directory | Description |
| :--- | :--- |
| `gestiondechet.zip` | **(LFS File)** Compressed archive containing the full project source and solution. |
| `gestiondechet.sln` | The main Visual Studio solution file. |
| `gestion_utilisateurs.h`/`.cpp` | Handles user data, authentication, and file-based persistence. |
| `dashboard.h`/`.cpp` | The main application dashboard view. |
| `GestionDechetsPage.h`/`.cpp` | Logic for the specific waste management feature. |
| `utilisateurs.txt` | Local file used to store user credentials. |

## 🤝 Contributing

We welcome contributions! Please see the [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines.

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.
