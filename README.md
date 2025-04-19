  <!-- Add your banner image here -->
![DevFlow Banner](https://files.catbox.moe/8y56pm.png)
# **DevFlow: Software Development Assistant** [UNDER DEVELOPMENT]  
DUE TO THE NATURE AND HIGH POTENTIAL OF THE PROJECT, THE CODEBASE IS PRIVATE. IF YOU WISH TO REVIEW IT, PLEASE SET UP A VIRTUAL MEETING.  
**Project Under Development for 1.5 months**

[Connect with me](https://www.linkedin.com/in/umarocks)
 
**DevFlow** is an all-in-one software development assistant designed to streamline the software lifecycle process. It integrates tools for **UML generation**, **unit test generation**, **code environments**, and **documentation management**, all within a secure, built-in Linux system.



## Features

### 📄 SRS Document Generation

DevFlow introduces a powerful document generation assistant that enables seamless creation of **Software Requirements Specification (SRS)** documents using natural language prompts and context-aware understanding.

#### 🚀 Current Capabilities
Use the `@DOCGEN` command in the chatbot to generate a complete SRS document with just a single line of input.  
For example:


[https://github.com/user-attachments/assets/d57e0dae-1de2-48be-8593-4311735bcc93](https://files.catbox.moe/eyxp6m.png)



- ✅ Automatically organizes standard SRS sections:  
  *Introduction, Functional Requirements, System Architecture, Non-Functional Requirements*, etc.
- ✅ Smart breakdown of modules and features based on the given prompt.
- ✅ Edits and additions can be made section-wise within the app.
- ✅ Download the generated document as **PDF**, **DOCX**, or **Markdown**.

#### 🔭 Long-Term Vision
The goal is to evolve DevFlow’s document generation system into a **fully autonomous development documentation assistant**.

> 💡 Imagine this:  
> During a client meeting, an in-app **Meeting Transcriber** listens to the discussion, captures core technical requirements, goals, constraints, and user flows — then auto-generates a polished SRS draft without the team writing a single line.

This intelligent pipeline will eventually support other technical documents too:
- ✅ Project Reports  
- ✅ Design Documents  
- ✅ API Docs  
- ✅ Test Plans  

#### 🎯 Why It Matters
- 🕒 Saves hours of writing and formatting
- 📄 Maintains consistent documentation quality
- 🤝 Bridges communication between clients and devs
- 📂 Reduces back-and-forth in Agile cycles

---



### UML Generation
- **UML Generation** is simplified using custom commands like `@SEQUENCE` `@ACTIVITY` `@CLASS` etc  based on your SRS document or chat inputs.
- The generated UML code and diagrams are displayed and can be downloaded for further use.

![UML Generation](https://files.catbox.moe/7wmdas.jpg)  <!-- Add UML generation image here -->
![Example Of Generated Sequence Diagram](https://files.catbox.moe/b98ki3.svg)
### Unit Test Generation
DevFlow supports automated unit test generation and testing directly in the app. The section consists of four components:
1. **Chatbot Area**: Use the `@gitclone` command to clone repositories and virtually mount them to your workspace. `@TESTGENERATE` to generate test case for the file that is opened in the in app code ide, or `@TESTALL` to generate test files for each file in the virtual file system.
2. **File System**: A client-side file system that can be mounted to a individualized **secure Linux VM**, allowing you to work directly on your codebase. These VM can be shared between multiple people, teams and groups if needed.
3. **Terminal**: Interact with your VM via a custom terminal section, much like AWS EC2 webterminal but optimized for developer needs.
4. **IDE**: Code, test, and run your software directly in the app without switching tabs or environments.

![Unit Test](https://files.catbox.moe/w23iog.png)  <!-- Add Unit Test Generation image here -->

### Documentation Management (RAG)
- **Document RAG (Retreival-Augmented-Generation)**: Store your **SRS** and other code documentation for easy retrieval and management.You can ask questions such as asking for a specific method in the code base or asking  what that specific method is used for across the codebase.
- **Assist Developers**: Search and retrieve relevant coding documentation to increase productivity and ensure alignment with coding standards. Developers can directly  access the pdf opened in the tab and can navigate  the pdf if needed for further context.

![Documentation](https://files.catbox.moe/4kexn4.png)  <!-- Add Documentation Management image here -->

### Verify & Validate 
- **Code Validation**: Automatically run unit tests, generate reports, and score your software based on predefined coding guidelines.
- **Score & Metrics**: The validation section will provide a score for your software quality, highlighting potential improvements and ensuring high code standards.

![Verify & Validate](https://files.catbox.moe/xxxd04.png)  <!-- Add Verify and Validate image here -->

## Technologies Used
- **Frontend**: React, Tailwind CSS
- **Backend**: FastAPI
- **Linux Environment**: Alpine Linux VM for secure, isolated coding and testing environments
- **Chatbot Integration**: Custom commands like `@SEQUENCE`, `@TESTGENERATE`, and `@gitclone` for seamless interaction.

## Installation
To run **DevFlow** locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/umarocks/DevFlow.git
   ```

2. Navigate into the project directory:
   ```bash
   cd DevFlow
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

