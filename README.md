**WORK IN PROGRESS**

# ClipCentauri

Welcome to ClipCentauri – your ultimate clipboard manager that allows you to store and access up to 100 clipboard items effortlessly. With a stylish interface and powerful features, ClipCentauri ensures you never lose track of your copied content.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
  - [Viewing Clipboard History](#viewing-clipboard-history)
  - [Star Important Items](#star-important-items)
  - [Copy Items](#copy-items)
  - [Settings and Customization](#settings-and-customization)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

ClipCentauri is a powerful clipboard manager designed to help you store and access up to 100 clipboard items effortlessly. It features a stylish interface and a variety of functionalities to ensure that you never lose track of your copied content.

## Features

- **Store Up to 100 Items**: Keep a history of your last 100 copied items.
- **Quick Access**: Press Windows + V to view your latest 10 items, with an option to view more.
- **Star Items**: Mark important clipboard entries to keep them at the top of your list.
- **User-Friendly Interface**: An intuitive design for easy navigation and item management.

## Installation

1. **Download the Installer**
   - Download the latest version of the ClipCentauri installer from the [releases page](https://github.com/Sreechandh22/ClipCentauri/releases).

2. **Run the Installer**
   - Double-click the downloaded file to start the installation process.
   - Follow the on-screen instructions to complete the installation.

3. **Launch ClipCentauri**
   - Open ClipCentauri from the Start menu or desktop shortcut.
   - Grant necessary permissions if prompted.

## Usage

### Viewing Clipboard History

1. **Access Clipboard History**
   - Press `Windows + V` to open the clipboard history panel.
   - The latest 10 items are displayed, with an option to view all 100 items.

### Star Important Items

1. **Star Items**
   - Click the star icon next to an item to mark it as important.
   - Starred items appear at the top of your clipboard history.

### Copy Items

1. **Copy Items**
   - Click on any item in the clipboard history to copy it back to your clipboard.

### Settings and Customization

1. **Open Settings**
   - Click on the settings icon in the main interface.
   - Customize your clipboard history preferences and appearance.

## File Structure

    ClipCentauri/
    ├── ClipBoardManagerWPF/
    │ └── ClipboardManager/
    │ ├── Database/
    │ │ └── (Database-related files)
    │ ├── Helpers/
    │ │ └── (Helper functions and utilities)
    │ ├── ViewModels/
    │ │ └── (MVVM ViewModels)
    │ ├── Views/
    │ │ └── (XAML Views)
    │ ├── bin/Debug/net7.0-windows/
    │ ├── obj/
    │ ├── App.xaml
    │ ├── App.xaml.cs
    │ ├── AssemblyInfo.cs
    │ ├── ClipboardItem.cs
    │ ├── ClipboardManager.csproj
    │ ├── ClipboardService.cs
    │ ├── MainWindow.xaml
    │ ├── MainWindow.xaml.cs
    │ └── tasks.json
    ├── ClipboardManager.sln
    ├── README.md


- **ClipBoardManagerWPF/ClipboardManager**: Contains the source code for the clipboard manager application.
  - **Database**: Contains database-related files.
  - **Helpers**: Helper functions and utilities.
  - **ViewModels**: MVVM ViewModels.
  - **Views**: XAML Views.
  - **bin/Debug/net7.0-windows**: Binary output directory.
  - **obj**: Object files directory.
  - **App.xaml**: Application XAML file.
  - **App.xaml.cs**: Code-behind for the application XAML.
  - **AssemblyInfo.cs**: Assembly information file.
  - **ClipboardItem.cs**: Model for clipboard items.
  - **ClipboardManager.csproj**: Project file for the clipboard manager.
  - **ClipboardService.cs**: Service for managing clipboard operations.
  - **MainWindow.xaml**: Main window XAML file.
  - **MainWindow.xaml.cs**: Code-behind for the main window XAML.
  - **tasks.json**: Task configuration file.
- **ClipboardManager.sln**: Solution file for the project.
- **README.md**: Project overview and setup guide.

## Contributing

We welcome contributions to enhance ClipCentauri! If you have suggestions, bug reports, or feature requests, please open an issue on our GitHub repository.

### How to Contribute

1. **Fork the Repository**
   - Click the "Fork" button on the GitHub repository page.

2. **Clone Your Fork**
   - Clone your forked repository to your local machine:

    ```sh
    git clone https://github.com/Sreechandh22/ClipCentauri.git
    ```

3. **Create a Branch**
   - Create a new branch for your feature:

    ```sh
    git checkout -b feature/your-feature-name
    ```

4. **Make Changes and Commit**
   - Implement your changes and commit them with a descriptive message:

    ```sh
    git commit -m "Add new feature: your feature name"
    ```

5. **Push Changes**
   - Push your changes to your forked repository:

    ```sh
    git push origin feature/your-feature-name
    ```

6. **Submit a Pull Request**
   - Open a pull request on GitHub and provide a detailed description of your changes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For support or inquiries, please contact us at support@clipcentauri.com.
