# Obsidian Auto Tasks 🚀

![Obsidian Auto Tasks](https://img.shields.io/badge/Download%20Latest%20Release-blue?style=for-the-badge&logo=github&link=https://github.com/DanielCarlosLena/obsidian-auto-tasks/releases)

Welcome to the **Obsidian Auto Tasks** repository! This project allows you to extract actionable tasks from your Obsidian notes and automatically add them to your todo list or calendar via CalDAV. With this tool, you can streamline your workflow and ensure that your tasks are always up to date.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Supported Platforms](#supported-platforms)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features 🌟

- **Automatic Task Extraction**: The tool scans your Obsidian notes for tasks and extracts them.
- **Seamless Integration**: Easily sync tasks with your preferred todo list or calendar using CalDAV.
- **Customizable Settings**: Adjust settings to suit your workflow.
- **Multi-Platform Support**: Works on various operating systems.
- **Lightweight and Fast**: Minimal resource usage ensures smooth operation.

## Installation 🛠️

To get started with Obsidian Auto Tasks, follow these steps:

1. **Download the latest release** from the [Releases section](https://github.com/DanielCarlosLena/obsidian-auto-tasks/releases). You need to download and execute the appropriate file for your operating system.
2. **Extract the files** to your desired directory.
3. **Install dependencies** by running the following command in your terminal:

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application** using the command:

   ```bash
   python main.py
   ```

## Usage 📋

After installation, you can start using Obsidian Auto Tasks. Here’s how:

1. **Open the application**.
2. **Select your Obsidian vault** where your notes are stored.
3. **Set your CalDAV server details** in the configuration settings.
4. **Run the task extraction** process. The tool will automatically find and sync tasks to your calendar or todo list.

## Configuration ⚙️

You can customize the behavior of Obsidian Auto Tasks by editing the configuration file. Here are some important settings:

- **Obsidian Vault Path**: Specify the path to your Obsidian vault.
- **CalDAV URL**: Enter the URL for your CalDAV server.
- **Username and Password**: Provide your CalDAV credentials.
- **Task Keywords**: Define any specific keywords that should be considered as tasks.

Example configuration file:

```json
{
  "vault_path": "/path/to/your/obsidian/vault",
  "caldav_url": "https://your-caldav-server.com",
  "username": "your_username",
  "password": "your_password",
  "task_keywords": ["TODO", "FIXME", "TASK"]
}
```

## Supported Platforms 🖥️

Obsidian Auto Tasks supports the following platforms:

- Windows
- macOS
- Linux

Make sure to have Python 3.x installed on your system.

## Contributing 🤝

We welcome contributions to improve Obsidian Auto Tasks. If you want to help out, follow these steps:

1. **Fork the repository**.
2. **Create a new branch** for your feature or bug fix.
3. **Make your changes** and commit them.
4. **Push your branch** to your forked repository.
5. **Open a pull request** with a description of your changes.

Please ensure that your code adheres to the existing style and includes tests where applicable.

## License 📄

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact 📬

If you have any questions or suggestions, feel free to reach out:

- **GitHub**: [DanielCarlosLena](https://github.com/DanielCarlosLena)
- **Email**: daniel@example.com

Thank you for checking out Obsidian Auto Tasks! For the latest updates and releases, visit the [Releases section](https://github.com/DanielCarlosLena/obsidian-auto-tasks/releases).