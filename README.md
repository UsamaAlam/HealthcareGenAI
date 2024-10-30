
# Amazon Bedrock Agents Workshop: Building a 360° Patient View with a Data Lake

This workshop introduces the use of Amazon Bedrock agents integrated with a data lake to generate a comprehensive, 360° view of a patient. By utilizing synthetic FHIR records and VCF files, this end-to-end solution demonstrates how AI-powered agents can serve as medical assistants, providing customized responses based on user persona.

---

## Table of Contents
1. [Introduction to agents](#introduction)
2. [Workshop Objectives](#workshop-objectives)
3. [Persona-Based Interaction](#persona-based-interaction)
4. [Data Used in this Workshop](#data-used-in-this-workshop)
5. [Workshop Steps](#workshop-steps)
6. [Additional Exercises](#additional-exercises)

---

## Introduction

This workshop showcases how Amazon Bedrock agents can be integrated with a data lake to deliver personalized responses based on user personas. Two distinct personas—a professional doctor and an average person—are considered. Using the same underlying data, the Bedrock agent tailors responses according to the persona, enhancing the user experience and ensuring information is presented in an accessible, persona-specific way.

---

## Workshop Objectives

Through this hands-on experience, participants will:
- Understand how to create and configure Amazon Bedrock agents for persona-based interactions.
- Build an end-to-end AI-driven medical assistant using synthetic health data.
- Utilize a datalake architecture to store, manage, and query synthetic FHIR records and VCF files.

---

## Persona-Based Interaction

The Bedrock agent is designed to respond differently based on the user's persona:
- **Professional Doctor**: Responses include in-depth medical details and clinical terminology.
- **Average Person**: Responses are simplified, focusing on explanations and recommendations in layperson terms.

---

## Data Used in this Workshop

This workshop uses synthetic datasets to simulate real-world health data:
- **FHIR Records**: Synthetic FHIR (Fast Healthcare Interoperability Resources) records simulate patient clinical data.
- **VCF Files**: Synthetic VCF (Variant Call Format) files are used to include genetic information, enabling deeper insights into potential health risks.

---

## Workshop Steps
You can start the main workshop running **[health vare agent with function definition](healthcare-agent-with-function-definition .ipynb)**

1. **Set Up the Environment**: Instructions on setting up the necessary AWS resources and configurations.
2. **Create synthetic medical records**: Guide to creating a data lake and loading synthetic FHIR and VCF data.
3. **Configuring Amazon Bedrock Agent**: Instructions on configuring the Bedrock agent for personalized responses based on persona.
4. **Implementing Persona Logic**: Steps to apply conditional logic in the Bedrock agent for tailored responses.
5. **Testing and Evaluation**: Validating the agent’s response with both personas to ensure accuracy and relevance.

---

## Additional Exercises

Explore these extra exercises to deepen your understanding and enhance the solution further:

- **[Exercise 1: Introduction to custom agents](introduction-to-agents/README.md)**: Learn when and how to custom agentsa.
- **[Exercise 2: Prompt and session attributes](prompt-and-session-attributes/README.md)**: For greater control of session context, you can modify the SessionState object in your agent.
- **[Exercise 3: Advanced propomts and custom parsers](advanced-prompts-and-custom-parsers/README.md)**: Advanced propomts and custom parsers.

---

This **README.md** file provides an introductory framework for your workshop, with placeholders for links to specific notebooks for additional exercises as you build them out in your repository.