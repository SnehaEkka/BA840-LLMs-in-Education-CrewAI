# LLMs in Education: CrewAI as an AI Tutor  
#### "Evaluating how large language models can enhance personalized learning through contextual tutoring assistance, while exploring ethical implications and future considerations"

![](https://github.com/SnehaEkka/BA840-LLMs-in-Education-CrewAI/blob/main/ai-in-edu-banner.jpg)

## About  
Exploring the use of large language models (LLMs) as AI tutors by evaluating CrewAI’s ability to provide targeted, context-aware learning assistance across diverse subjects. The project also engages deeply with ethical considerations, unintended consequences, and regulatory frameworks shaping AI in education.

## Project Overview  
This project evaluates **CrewAI**, an agent-based tutoring system built on OpenAI’s language models, designed to provide personalized educational support via three specialized agents:

1. **Student Context Collector** – Gathers student background and learning preferences.  
2. **Subject Topic Specifier** – Determines the specific topic needing assistance.  
3. **Topic Helper** – Delivers targeted explanations tailored to student context.

The system was tested across multiple domains—accounting principles, current affairs, and environmental science—assessing clarity, depth, and relevance.

## Tech Stack & Tools  

| Tool/Library    | Role                          | Why Chosen                       |
|-----------------|-------------------------------|---------------------------------|
| Python          | Development and scripting     | Robust AI and NLP ecosystem      |
| CrewAI          | Agent orchestration           | Facilitates multi-agent workflows|
| OpenAI API      | Language model backend        | Cutting-edge NLP capabilities    |
| Jupyter Notebook| Analysis and documentation    | Interactive and reproducible     |

## Key Insights  
- **Best performance** on the accounting principles prompt — detailed, clear, real-world explanations.
- **Current affairs** prompt responses were relevant but less comprehensive in scope, indicating the need for supplemental context.
- **Environmental science** produced fact-based and detailed output, but occasionally lacked cross-topic integration.
- Multi-agent setup allowed for a more context-aware learning experience, but agent prompts need more domain tuning for complex topics.

## Discussion Summary: Ethical Implications and Future Perspectives  

The project goes beyond technical evaluation to engage with critical **ethical implications of AI in education**, aligning with two predominant schools of thought:

- **Ethics of AI (Intrinsic AI Ethics):**  
  Concerns focus on the technology itself—transparency, bias, fairness, privacy, and potential harms. AI models can perpetuate societal biases or produce inaccurate content, raising questions about responsible design and deployment. The environmental cost of training large models and data governance are also ethical priorities.

- **Ethical Use of AI (Human-Centered AI):**  
  This perspective emphasizes how educators and learners interact with AI tools—ensuring AI acts as an amplifier of human potential rather than a replacement. It entails fostering critical thinking, preventing overreliance, and maintaining the essential human elements of education like empathy and judgment.

The project recognizes several **unintended consequences** and challenges ahead:

- Potential for bias and misinformation in tutor outputs without rigorous oversight.  
- Risks of diminishing human instructor roles and weakening teacher–student relationships.  
- Accessibility issues due to digital divides and varying AI literacy among students and educators.  
- Privacy concerns linked to data collection during personalized tutoring interactions.

**Proposed regulations and frameworks** discussed include:  
- Transparent disclosure requirements around AI usage in classrooms.  
- Policies mandating AI ethics education for students and training for educators to handle AI responsibly.  
- Safeguards against bias, data misuse, and ensuring inclusivity.  
- Ongoing review of AI models for fairness, accuracy, and social impact.

These considerations highlight the need for a **balanced, human-centered approach** to integrating AI tutors like CrewAI, ensuring ethical deployment complements educational goals and societal values.

## How to Run  
1. Clone this repository.  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Set your OpenAI API key in environment variables.  
4. Open `LLMs_in_Education_CrewAI.ipynb` in Jupyter Notebook.  
5. Run sequentially to simulate AI tutoring across prompts.  
6. Customize prompt inputs to explore new educational scenarios.

## Future Directions  
- Expand subject coverage and complexity levels.  
- Develop adaptive, interactive dialogue agents for richer education.  
- Collect real-world feedback to refine tutoring quality and ethical safeguards.  
- Investigate deployment in classroom settings with transparency and ethics in mind.

## Coursework & Contributors 
- **Coursework:** Completed as part of **[Course Name/Code Here]**, with a focus on AI applications in education, natural language processing, and interactive learning systems.
- **Contributors:**  
  - Gunjan Sharma
  - Jasmine Gohil
  - Jenil Shah
  - Saachi Dholakia
  - Sneha Ekka

## Additional Resources  
- [Presentation Deck](https://www.canva.com/design/DAGGGeWhm3Q/3Bk2eS920vaDcU5u3ZAVwQ/view?utm_content=DAGGGeWhm3Q&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h433c6e3737) — Visual summary and ethical discussions  
- Jupyter Notebook `LLMs_in_Education_CrewAI.ipynb` for experimental code and analysis
