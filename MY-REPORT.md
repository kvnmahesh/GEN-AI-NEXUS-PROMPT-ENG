# Automating Requirement Analysis for Study Companion Bot (GEN AI NEXUS)

## 1-liner Description
Developing an automated Requirement Analysis process for the study companion bot, GEN AI NEXUS, using advanced Prompt Engineering techniques.

### Authors
- Kunapaneni Venkata Naga Mahesh
- Rajeev Pondala
- Sindhuja Lakkapally

### Academic Supervisor
- Dr. Fernando Koch

---

## Research Question
What is the most effective configuration of Prompt Engineering techniques to automate Requirement Analysis in the SDLC using GEN AI NEXUS?

---

## Arguments

### What is already known about this topic
- **Prompt Engineering Benefits:** Automates data gathering and synthesis during Requirement Analysis.
- **Challenges:** Automation must not hinder creative and critical thinking, crucial in early SDLC stages.
- **Balanced Approach:** Combining manual and automated techniques can improve quality.

### What this research is exploring
- Utilizing advanced Prompt Engineering techniques:
  - **Zero-Shot Prompting:** Generating requirements without prior examples.
  - **Few-Shot Prompting:** Providing a few examples to guide the bot.
  - **Prompt Templates:** Standardized prompts for consistency.
  - **Chain-of-Thought Prompting:** Enabling step-by-step reasoning.

- Building **GEN AI NEXUS** to assist students with personalized tutoring.
- Automating **Requirement Analysis** in the **SDLC** to save time and enhance accuracy.

### Implications for practice
- Simplifies Requirement Analysis for educational software.
- Accelerates early-stage software development processes.
- Provides insights into how automation impacts project efficiency.

---

## Research Method
- Developing a **GEN AI NEXUS prototype** using the **Prompt Engineering Lab**.
- Testing various prompting techniques:
  - Example: Using **Few-Shot Prompting** to generate requirements for a new tutoring feature.
- Evaluating the accuracy and relevance of generated requirements.
- Comparing manual vs. automated methods for efficiency.

---

## Experimental Setup

- **Automation Techniques:** Exploring Zero-Shot, Few-Shot, Prompt Templates, and Chain-of-Thought techniques.
- **Integration with GEN AI NEXUS:** Implementing a requirements generation module within the bot.

### Evaluation Metrics:
- **Accuracy:** How well the generated requirements align with stakeholder needs.
- **Response Time:** Efficiency in generating complete requirements.
- **Consistency:** Uniformity in the output structure across different prompts.

---

## Matching Models to Report Sections

To optimize the automated report generation for **GEN AI NEXUS**, we mapped specific AI models to different sections of the requirement analysis report:

| Report Section        | Recommended Models                               | Purpose                                                     |
|-----------------------|--------------------------------------------------|-------------------------------------------------------------|
| **Project Overview**   | Llama-3.2-3B-Instruct, Qwen2                    | For generating coherent summaries and maintaining structured text. |
| **Data & Methodologies**| Mistral-large, Gemma2                           | To provide detailed and precise descriptions of data handling and methodologies. |
| **Results & Evaluation**| Qwen2, Microsoft/phi-4                          | For delivering structured metric analysis and clear presentation of findings. |
| **Discussion & Future Work** | Gemma2, Llama-3.2-11B-Vision-Instruct    | To enhance reasoning and present well-rounded discussions and projections. |
| **Project Setup & Usage** | Codestral, Tinyllama                        | For producing structured documentation and step-by-step instructions. |
| **Appendices**          | Codestral, Qwen2                                | To generate code snippets and support extended textual explanations. |

---

## Results

| Model              | Prompt                                          | Response                                           | Time Taken |
|--------------------|-------------------------------------------------|---------------------------------------------------|------------|
| Llama-3.2:latest   | "Provide a brief explanation of Newton's Third Law." | "Newton's Third Law states that 'for every action, there is an equal and opposite reaction.'" | 6.758s     |
| Llama-3.2:latest   | "What are the benefits of active recall in studying?" | Compared active learning with passive reading, highlighting improved retention and engagement. | 26.544s    |
| Llama-3.2:latest   | "What are the requirements for a personalized tutoring chatbot?" | Generated features like Personalized Study Plans, Adaptive Learning Algorithm. | 11.416s    |

### Comparison:
- Short and straightforward prompts led to quicker responses.
- Detailed prompts with multi-step reasoning improved the quality of answers but increased response time.
- **Best Performance:** Combining **Chain-of-Thought** with **Automated Prompt Generation** yielded the highest accuracy.

### Impact on GEN AI NEXUS:
- The bot generated more detailed and relevant requirements.

### Example:
When asked to create requirements for a "Quiz Module," the bot produced structured outputs like:
- "The bot should generate quizzes based on the student's current topic."
- "Quizzes should adapt to the student’s learning pace."

---

## Further Research
- Integrate **GEN AI NEXUS** with additional **GenAI models**.
- Extend automation to **Solution Design** and **Development** phases of the **SDLC**.
- Explore **dynamic prompting** where the bot adjusts prompts based on previous interactions.

This study provides a strong foundation for integrating automated Requirement Analysis into AI-driven educational tools, optimizing project planning and execution workflows.
