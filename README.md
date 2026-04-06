# Agentic AI using crewai

CrewAI (www.crewai.com) is a popular open-source agentic AI orchestration platform that I explored today. It enables users to create autonomous AI agents that focus on specific tasks and build workflows using these agents.

For example, one AI agent can be responsible for downloading data from a website, while another agent organizes the downloaded data into different categories. The workflow ensures that the data is organized only after the download process is completed.

# Components Architecture of CrewAI

## Agents
Agents are one of the smallest component of a Crew. To simply put, each agent in a crew has a specific role, goal and backstory. The agent can be assigned to a LLM to perform it's role. Agent in a crew is defined in a Crew Project Folder --> SRC/<project-name>/config/agents.yaml. In agents.yaml, you will be required to define each agent that forms a crew. A sample structure of agents.yaml file is the following. 

reporting_analyst:
  role: >
    Data Analyst and Report Writer for {topic}
  goal: >
    Analyze research findings and create a comprehensive, well-structured
    report that presents insights in a clear and engaging way
  backstory: >
    You are a skilled analyst with a background in data interpretation
    and technical writing. You have a talent for identifying patterns
    and extracting meaningful insights from research data, then
    communicating those insights effectively through well-crafted reports.
  llm: openai/gpt-4o-mini  # e.g. openai/gpt-4o, google/gemini-2.0-flash, anthropic/claude...

## Tasks



## Tools

## Crew

## Flows


