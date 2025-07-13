# Wakari Python Agent
Python based Automation Agent that can execute Selenium test suites based on natural language guidance. 

#### Prerequisites

- Download the appropriate [Chrome WebDriver](https://googlechromelabs.github.io/chrome-for-testing/)
- Set the WebDriver path in environment variable
- Create `.env` file in root directory
- Set `OPENAI_API_KEY` (or Change the appropriate LLM API key) in `.env` file

#### How to Run
Orchestrator file will install all the relevant dependencies & execute predefined automation steps defined in cell #6
> The predifined steps is just a expample & Google may interrupt the execution via its anti automation mechanism

- Run `orchestrator-agent.ipynb`
