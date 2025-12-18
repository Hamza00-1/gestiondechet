# Gestion Déchet (Waste Management System)

## Project Overview

**Gestion Déchet** is a desktop application developed in C++ using the Qt framework, designed to manage and track waste-related data. This system provides a structured interface for users to interact with a waste management database, offering features such as user authentication and a dedicated dashboard for operational oversight.

The name "Gestion Déchet" is French for "Waste Management."

## Features

*   **User Authentication:** Secure login and registration system.
*   **User Management:** Stores user credentials (username, email, password) in a local file (`utilisateurs.txt`).
*   **Dashboard:** A central hub for viewing key information and navigating the application's features.
*   **Waste Data Management:** Dedicated section for handling and tracking waste-related entries.

## Technology Stack

*   **Language:** C++
*   **Framework:** Qt (for cross-platform desktop application development)
*   **Build System:** Visual Studio Project Files (`.vcxproj`, `.sln`)

## Getting Started

### Prerequisites

To build and run this application, you will need:

1.  **C++ Compiler:** A modern C++ compiler (e.g., MSVC, GCC, Clang).
2.  **Qt Framework:** The appropriate version of the Qt framework installed (version used in development appears to be compatible with Visual Studio).
3.  **Visual Studio:** The project files are configured for Visual Studio.

### Installation and Setup

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Hamza00-1/gestiondechet.git
    cd gestiondechet
    ```

2.  **Open the Solution:**
    Open the `gestiondechet.sln` file in Visual Studio.

3.  **Configure Qt:**
    Ensure your Visual Studio project settings are correctly configured to link against your installed Qt libraries.

4.  **Build and Run:**
    Build the solution. The executable will be generated in the output directory (e.g., `x64/Debug/gestiondechet.exe`).

## Project Structure

The core application logic is contained within the following files:

| File | Description |
| :--- | :--- |
| `main.cpp` | Application entry point. |
| `gestiondechet.h`/`.cpp` | Main application window and UI logic (login/registration). |
| `gestion_utilisateurs.h`/`.cpp` | Handles user data, authentication, and file-based persistence. |
| `dashboard.h`/`.cpp` | The main application dashboard view. |
| `GestionDechetsPage.h`/`.cpp` | Logic for the specific waste management feature. |
| `utilisateurs.txt` | Local file used to store user credentials. |

## Contributing

If you wish to contribute to this project, please feel free to fork the repository and submit a pull request.

## License

[License information here, e.g., MIT License]
