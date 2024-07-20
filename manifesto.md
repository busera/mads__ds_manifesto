# My Personal Data Science Manifesto

## Core Principles

1. Solve important problems that deliver real value
2. Maintain ethical integrity in all analyses and communications 
3. Embrace uncertainty and communicate it clearly
4. Strive for reproducibility and transparency
5. Continuously learn and improve skills

## Project Phases: Questions, Maxims, and Commitments

### 1. Problem Formulation

| Category | Item | Check |
|----------|------|-------|
| Essential Questions | Why is the analysis needed? |   |
| | How will the results be used? |   |
| | What is the specific target or purpose of the analysis? |   |
| | Is the project clearly described and solvable through data analysis? |   |
| | What kinds of data would be used? |   |
| | What are the potential societal impacts of this analysis? |   |
| | Are there any regulatory or compliance considerations? |   |
| | Who are the stakeholders affected by this analysis? |   |
| | What are the long-term implications of this project? |   |
| Key Maxims | The original formulation is rarely the correct formulation. |   |
| | Make sure that the problem you are solving is important. |   |
| | Challenge the initial business question for clarity and formulation. |   |
| | Consider the use scenario and expected value. |   |
| | Consider the problem from multiple perspectives (business, technical, ethical, societal). |   |
| | Align the project goals with broader organizational objectives. |   |
| | Anticipate potential misuses or unintended consequences of the analysis. |   |
| Ethical Commitments | Never over-hype what I am going to be able to produce. |   |
| | Ensure the project aligns with the organization's ethical guidelines and societal values. |   |
| | Commit to transparency about the project's purpose and potential impacts. |   |

### 2. Data Collection & Cleaning

| Category | Item | Check |
|----------|------|-------|
| Essential Questions | What is the meaning/description of the provided datasets / columns? |   |
| | How was the data sampled? |   |
| | Are there any potential biases in the data collection process? |   |
| | What are the data quality issues and how can they be addressed? |   |
| | Is the sample size sufficient for the analysis? |   |
| | Are there any privacy concerns with the data being collected? |   |
| | How can we ensure data security throughout the process? |   |
| | Are there any legal restrictions on data usage? |   |
| | How can we validate the data's authenticity and integrity? |   |
| Key Maxims | Label altered data. |   |
| | Be aware of (statistical) bias types during data collection and sampling. |   |
| | Only correct values when the data is understood and enough information is gathered. |   |
| | Consider creating metadata columns indicating imputed or altered values. |   |
| | Document the complete "journey" from raw data to the conclusion. |   |
| | Implement robust data governance practices. |   |
| | Consider the ethical implications of data collection methods. |   |
| | Prioritize data minimization and purpose limitation principles. |   |
| Ethical Commitments | Be aware of (statistical) bias types during data collection and sampling. |   |
| | Never alter results for personal gain. |   |
| | Respect individual privacy and obtain informed consent where applicable. |   |
| | Ensure compliance with data protection regulations (e.g., GDPR, CCPA). |   |
| | Implement strong data security measures to protect sensitive information. |   |

### 3. Analysis & Modeling

| Category | Item | Check |
|----------|------|-------|
| Essential Questions | What are some potential confounders? |   |
| | How can we detect and prevent overfitting? |   |
| | Are we considering all relevant variables? |   |
| | How robust is the model to different assumptions? |   |
| | What are the limitations of our analysis? |   |
| | How can we ensure fairness and avoid discrimination in our models? |   |
| | What are the environmental impacts of our computational processes? |   |
| | How can we make our analysis more interpretable and transparent? |   |
| | Are there any potential feedback loops that could amplify biases over time? |   |
| Key Maxims | Multiple comparisons means more opportunities for false positives. |   |
| | Correlation does NOT imply causation. |   |
| | A well-functioning ML algorithm will separate the signal from the noise. |   |
| | Tell a story about how each feature fits into the model. |   |
| | Don't fall for the false cause fallacy or narrative fallacy. |   |
| | Regularly assess and mitigate algorithmic bias. |   |
| | Consider the trade-offs between model complexity and interpretability. |   |
| | Implement version control and reproducibility practices for all analyses. |   |
| Ethical Commitments | Always verify how the data is used and how results will be interpreted. |   |
| | Never hunt or hack for "positive results". |   |
| | Avoid p-hacking and HARKing (Hypothesizing After Results are Known). |   |
| | Actively work to identify and mitigate unfair bias in models. |   |
| | Consider the environmental impact of computational resources and optimize for efficiency. |   |
| | Strive for model interpretability and transparency, especially in high-stakes decisions. |   |

### 4. Presentation & Deployment

| Category | Item | Check |
|----------|------|-------|
| Essential Questions | Is this a situation where we need an explainable model or does a "black box" model also work? |   |
| | How can we effectively communicate uncertainty in our results? |   |
| | What is the narrative we're building around our insights? |   |
| | How can we make our presentation visually appealing and easy to understand? |   |
| | What are the potential challenges in deploying this model? |   |
| | How can we ensure ongoing monitoring and maintenance of deployed models? |   |
| | What are the potential risks of model misuse or misinterpretation? |   |
| | How can we make our results accessible to diverse audiences? |   |
| | What is our plan for model updates and version control? |   |
| Key Maxims | Present uncertainty in terms of hypothetical concrete outcomes rather than statistical abstractions. |   |
| | Don't wait too long to communicate insights, but be careful with sharing premature results. |   |
| | Structure presentations using frameworks like SPSN and SUCCESs. |   |
| | Use visuals to reinforce key findings and make it easier to follow the storyline. |   |
| | Write clean, scalable code and align with engineers early on coding practices. |   |
| | Develop clear guidelines for model usage and interpretation. |   |
| | Implement robust monitoring systems for deployed models. |   |
| | Create user-friendly interfaces and documentation for non-technical stakeholders. |   |
| Ethical Commitments | Always convey the level of uncertainty warranted by my analysis, even if clients don't want to hear about it. |   |
| | Work closely with decision-makers to ensure insights are understood and actionable. |   |
| | Provide clear documentation on model limitations and appropriate use cases. |   |
| | Establish a feedback mechanism for users to report issues or concerns with deployed models. |   |
| | Commit to regular audits and updates of deployed models to ensure continued accuracy and fairness. |   |

## Skills Development Plan

1. Problem Formulation
   - Strengthen ability to conduct effective inquiries leading to good problem formulations
   - Develop a robust repertoire of problem types
   - Improve mapping of domain problems to data science problem types

2. Data Collection & Cleaning
   - Deepen understanding of common data problems leading to misleading results
   - Expand knowledge of potential data sources in application domain
   - Refine techniques for querying, assembling, and cleaning datasets

3. Analysis & Modeling  
   - Master techniques to avoid common modeling mistakes
   - Expand repertoire of models and validation methods
   - Improve ability to interpret results and their implications

4. Presentation & Deployment
   - Enhance storytelling and data visualization skills
   - Develop expertise in presenting to non-technical audiences
   - Improve collaboration with software engineers for model deployment

## Continuous Learning Approach

### Daily
- Follow key data science publications and blogs:
  - Towards Data Science (Medium)
  - Towards AI Team (Medium)

### Weekly
- Listen to data science podcasts:
  - Data Skeptic

### Monthly
- Complete relevant online courses and tutorials:
  - Kaggle courses
  - Coursera specializations
- Engage in hands-on coding practices:
  - DataCamp
  - Kaggle competitions

### Ongoing
- Apply learnings to real-world projects continuously
- Engage regularly with data science community for knowledge sharing
- Stay updated on new tools, best practices, and emerging technologies

By adhering to these principles, continuously developing my skills, and maintaining ethical standards, I commit to delivering high-quality, impactful data science work throughout my career. I will strive to solve important problems, communicate effectively, and always consider the ethical implications of my work.