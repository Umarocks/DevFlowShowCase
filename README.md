# **DevFlow: Software Development Assistant** [UNDER DEVELOPMENT]  
( ***Due to the nature and high potential of the project, i am keeping the codebase private***)
 
**DevFlow** is an all-in-one software development assistant designed to streamline the software lifecycle process. It integrates tools for **UML generation**, **unit test generation**, **code environments**, and **documentation management**, all within a secure, built-in Linux system.

![DevFlow Banner](https://files.catbox.moe/8y56pm.png)  <!-- Add your banner image here -->

## Features

### UML Generation
- **UML Generation** is simplified using custom React commands like `@SEQUENCE`. Generate UML diagrams (including sequence diagrams) based on your SRS document or chat inputs.
- The generated UML code and diagrams are displayed and can be downloaded for further use.
- Built with **React**, **FastAPI**, and **Tailwind CSS** for a responsive, user-friendly interface.

![UML Generation](https://files.catbox.moe/d7css4.png)  <!-- Add UML generation image here -->
![Example Of Generated Sequence Diagram](https://files.catbox.moe/wnsgkb.jpg)
### Unit Test Generation
DevFlow supports automated unit test generation and testing directly in the app. The section consists of four components:
1. **Chatbot Area**: Use the `@gitclone` command to clone repositories and virtually mount them to your workspace.
2. **File System**: A client-side file system that can be mounted to a **secure Linux VM**, allowing you to work directly on your codebase.
3. **Terminal**: Interact with your VM via a custom terminal section, much like AWS EC2 instances but optimized for developer needs.
4. **IDE**: Code, test, and run your software directly in the app without switching tabs or environments.

![Unit Test](https://files.catbox.moe/w23iog.png)  <!-- Add Unit Test Generation image here -->

### Documentation Management (RAG)
- **Document RAG (Retreival-Augmented-Generation)**: Store your **SRS** and other coding documentation for easy retrieval and management.
- **Assist Developers**: Search and retrieve relevant coding documentation to increase productivity and ensure alignment with coding standards.

![Documentation](https://files.catbox.moe/4kexn4.png)  <!-- Add Documentation Management image here -->

### Verify & Validate (Under Development)
- **Code Validation**: Automatically run unit tests, generate reports, and score your software based on predefined coding guidelines.
- **Score & Metrics**: The validation section will provide a score for your software quality, highlighting potential improvements and ensuring high code standards.

![Verify & Validate](https://files.catbox.moe/xxxd04.png)  <!-- Add Verify and Validate image here -->

## Technologies Used
- **Frontend**: React, Tailwind CSS
- **Backend**: FastAPI
- **Linux Environment**: Alpine Linux VM for secure, isolated coding and testing environments
- **Chatbot Integration**: Custom commands like `@SEQUENCE`, `@UNITTESTGENERATE`, and `@gitclone` for seamless interaction.

## Installation
To run **DevFlow** locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/umarocks/LLM-Software-Engineering.git
   ```

2. Navigate into the project directory:
   ```bash
   cd LLM-Software-Engineering
   ```

3. Docker Compose:
   ```bash
   docker compose up --build
   ```
## License
This project is licensed under the **Proprietary License**. All rights are reserved.

All Rights Reserved

Copyright (c) [2025] UMAR ABDUL AZIZ

This software is proprietary and confidential. All rights are reserved by the author. No part of this software may be copied, used, modified, distributed, or otherwise utilized in any way for any purpose without the express written permission of the copyright holder.

You are not authorized to use, copy, modify, or distribute this software under any circumstances.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT ANY WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NON-INFRINGEMENT. IN NO EVENT SHALL THE AUTHOR OR COPYRIGHT HOLDER BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT, OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Contact
For any inquiries, you can reach out via email:

- **Email**: [umar.a.aziz2001@gmail.com](mailto:umar.a.aziz2001@gmail.com)

