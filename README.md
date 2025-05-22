![coding-agent](https://socialify.git.ci/AbhinavTheDev/coding-agent/image?description=1&font=Bitter&language=1&owner=1&pattern=Charlie+Brown&theme=Dark)

### ⭐ About  

- Open-source web app for your coding task.  
- Built with Next.js, CopilotKit.  
- Uses a coding assistant LangGraph agent for generating responses .  
- Simplifies developers task.  

| Demo Video                                                                                                       | Blog Post                                                                 |
|------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------|
| [![YouTube](https://i.ytimg.com/vi/OHNZUrz2o0g/hqdefault.jpg)](https://youtu.be/OHNZUrz2o0g?si=nUtjJcTg9O8lNr96) | [![Blog](https://media2.dev.to/dynamic/image/width=1000,height=420,fit=cover,gravity=auto,format=auto/https%3A%2F%2Fdev-to-uploads.s3.amazonaws.com%2Fuploads%2Farticles%2Fqznpo8tit1g36sn2ut6o.png)](https://dev.to/abhinav11234/ai-agents-the-future-of-intelligent-automation-4ge1) |


### :hammer_and_wrench: Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-black?logo=next.js" alt="Next.js" />
  <img src="https://img.shields.io/badge/CopilotKit-🪁-black" alt="CopilotKit" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/ShadCN--UI-7F56D9" alt="ShadCN UI" />
  <img src="https://img.shields.io/badge/LangGraph-purple" alt="LangGraph" />
  <img src="https://img.shields.io/badge/FastAPI-blue" alt="FastAPI" />
  <img src="https://img.shields.io/badge/LangChain-green" alt="langchain" />
</p>

## Star History

<a href="https://www.star-history.com/#abhinavthedev/coding-agent&Timeline">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=abhinavthedev/coding-agent&type=Timeline&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=abhinavthedev/coding-agent&type=Timeline" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=abhinavthedev/coding-agent&type=Timeline" />
 </picture>
</a>

### :outbox_tray: Set up

#### **Setting Up the Agent and UI**

##### **1. Get an API Key**
- Obtain a **GROQ_API_KEY**. 

##### **2. Clone the Repository**
- Clone the repository to your local machine:
   ```sh
   git clone https://github.com/AbhinavTheDev/coding-agent.git
   ```

##### **3. Set Up the Agent**
- Navigate to the agent directory:
   ```sh
   cd agent
   ```
- Install dependencies using Poetry:
   ```sh
   poetry install
   ```
- Create a `.env` file inside the `./agent` directory with your **GROQ_API_KEY**:
   ```
   GROQ_API_KEY=YOUR_API_KEY_HERE
   ```
- Run the agent demo:
   ```sh
   poetry run demo
   ```

##### **4. Set Up the UI**
- Navigate to the UI directory:
   ```sh
   cd ./ui
   ```
- Install dependencies using npm:
   ```sh
   npm i
   ```
- Create a `.env` file inside the `./ui` directory with your **GROQ_API_KEY**:
   ```
   GROQ_API_KEY=YOUR_API_KEY_HERE
   ```
- Run the Next.js project:
   ```sh
   npm run dev
   ```

#### **Troubleshooting**
1. Ensure no other local application is running on port **8000**.
2. In the file `/agent/rag_agent/demo.py`, change the address from `0.0.0.0` to `127.0.0.1` or `localhost` if needed.

### :mailbox: Contact
Hi, I'm Abhinav! 👋  
Connect with me on [LinkedIn](https://www.linkedin.com/in/abhinav-mittal-2a1b002a4/), [X](https://x.com/Abhinav11234) and check out my other projects on [GitHub](https://github.com/AbhinavTheDev).
