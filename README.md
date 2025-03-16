# CustomerSupportAgentsCrew

# Multi-Agent Customer Support Automation

This repository demonstrates a multi-agent system built with CrewAI to automate customer support tasks. The project sets up two specialized agents that work together to address customer inquiries:

- **Senior Support Representative:**  
  Plans and drafts a detailed, friendly, and accurate response to a customer's support inquiry.

- **Support Quality Assurance Specialist:**  
  Reviews the drafted response for completeness, accuracy, and adherence to quality standards.

## Key Features

- **Role Playing & Focus:**  
  Each agent has a defined role, goal, and backstory to get into character and deliver focused responses.

- **Cooperation & Delegation:**  
  Agents work together—while the Support QA agent reviews the response, the Support agent may delegate tasks if necessary.

- **Tools & Memory:**  
  The system integrates external tools (e.g., a document scraper) and enables memory to retain context across tasks.

## How It Works

1. **Task Assignment:**  
   Two tasks are defined: one to generate a response (using a scraping tool) and another to review it.

2. **Crew Execution:**  
   The crew executes tasks sequentially, using the agents’ roles and the enabled memory to produce a final, well-supported answer.

3. **Output:**  
   The final result is rendered in Markdown format.

## Requirements

- Python 3.10–3.12
- CrewAI, CrewAI Tools, and LangChain Community packages

## License
This repository is licensed under the MIT License.

## Attribution
This code is based on the example provided in the DeepLearning.AI "Multi AI Agent Systems with crewAI" course. 
Original source: https://learn.deeplearning.ai/courses/multi-ai-agent-systems-with-crewai
Special thanks to DeepLearning.AI for their educational materials.
