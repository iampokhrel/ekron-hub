# Ekron Hub

Welcome to Ekron Hub! This repository serves as a central hub for multiple projects related to the fictional world of Ekron, each organized in its own directory with its own documentation and resources. This includes projects like calendar, dictionary, and many more, and will be the digital foundation for the project.

## Table of Contents
- [Overview](#overview)
- [About Ekron](#about-ekron)
- [Projects](#projects)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview
This repository contains a collection of projects developed to build the digital foundations of Ekron — a fictional client nation in East Asia. This project will use creativity, engineering, and programming, to build the projects and develop the foundation of the fictional nation. Although each project is self-contained with its own setup instructions, dependencies, and documentation, there might be connections between different projects. For example, the first project, `extended_datetime`, is the basis for all the date and time related logic within the entire repository. Each project will contain a directory named dependencies, which will house the custom dependencies for the project, thereby allowing full independence of each project, while retaining the interconnectivity between the projects.

## About Ekron
Ekron (placeholder name, might change) is a fictional world, where Mesopotemians moved to East Asia sometimes in the 2nd Century BC. The worldbuilding project focuses on the way the culture, language, religion, beliefs, and worldview of these people might change in a new place. Developed by a client, who commissioned the author to develop the digital foundation of the project, including calendar, dictionary, keyboard, typing systems, etc.
- [Wiki of the Project incoming soon]

## Projects
Below is a list of projects included in this repository. Each project has its own subdirectory with a dedicated README.md file for detailed instructions. Projects will be uploaded to GitHub (with explicit permission from the client) as they are completed. Many existing projects serve as custom dependencies for newer projects. If the functionality of these dependencies does not meet the requirements of new projects, they will be updated to newer versions. Additionally, existing projects may receive version updates or patches as the repository evolves.

- **extended_datetime**: A lightweight Python module designed for advanced date-time arithmetic, historical calendrical accuracy, and creative software development. It extends Python’s built-in `datetime` module to support BC years, Julian Day conversions, and fixed-offset timezone management, making it ideal for precise and flexible time computations.  
  - Directory: `./extended_datetime`  
  - Read more on the project in [project README](./extended_datetime/README.md).

## Getting Started
To get started with any project, navigate to its directory and follow the instructions in its respective `README.md` file. Below are general prerequisites for working with this repository:

### Prerequisites
- General Tools: Python 3.11+
- A code editor like [VS Code](https://code.visualstudio.com/) or similar.

### Cloning the Repository
1. Clone the repository:
   ```bash
   git clone https://github.com/iampokhrel/ekron-hub.git
   ```
2. Navigate to the repository:
   ```bash
   cd ekron-hub
   ```
3. Explore the project directories to find the one you want to work on.

## Contributing
We welcome contributions to any of the projects! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit them (`git commit -m 'Add your feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a Pull Request with a clear description of your changes.

Please ensure your contributions align with the project's coding standards and include relevant documentation updates.

## License
This repository is licensed under the [Apache 2.0 License](LICENSE). Each project may have its own license; please check the respective project directory for details.

## Contact
For questions or suggestions, feel free to open an issue or contact Abhishek Pokhrel at 📧 [abhishekpokhrel@proton.me](mailto:abhishekpokhrel@proton.me).