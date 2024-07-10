# Karna: A Compliance Checking Chatbot for Code Analysis

## **Table of Contents**
1. **Motivation**
2. **Introducing Karna**
3. **Data Background**
4. **Model Training**
5. **Model Inference**
6. **Model Testing**
7. **User Experience (UX)**
8. **Key Risks and Future Work**
9. **Meet the Team!**

## **Motivation**
The motivation behind Karna is to empower data scientists and software engineers by providing them with a robust tool that eliminates the need to consult legal experts for every privacy-related query within their code. Navigating the complexities of privacy legislation like GDPR, CCPA, HIPAA, and the Privacy Act of 1974 can be daunting and time-consuming. Traditionally, ensuring compliance requires frequent interactions with legal professionals, which can slow down development processes and increase costs. Karna addresses this challenge by offering an AI-driven solution that provides instant access to comprehensive legal insights and compliance checks. This allows developers to seamlessly integrate privacy considerations into their workflows, ensuring their code meets regulatory standards without the constant need for legal intervention. By streamlining the compliance process, Karna enables developers to focus more on innovation and less on legal complexities, ultimately accelerating the development of privacy-compliant software solutions.

## **Introducing Karna**
Karna is a cutting-edge GenAI solution tailored for data scientists and software engineers to ensure their code adheres to key privacy legislation, including GDPR, CCPA, HIPAA, and the Privacy Act of 1974. This innovative application features an intuitive chatbot, enabling users to ask detailed questions about the entirety of these legal documents. Additionally, Karna provides powerful tools to analyze and verify your code's compliance with specific laws, ensuring your projects meet all necessary regulatory standards. By leveraging Karna, you can streamline your compliance processes, reduce legal risks, and focus on building high-quality, privacy-compliant software.

## **Data Background**
To ensure Karna's effectiveness, we curated a comprehensive dataset comprising GDPR, CPA, and related legal texts. This dataset was meticulously preprocessed to facilitate accurate analysis and compliance checking.

## **Model Training**
Training Karna involved:
1. **Data Processing:** Preparing legal texts and code snippets for comparative analysis.
2. **Knowledge Extraction:** Extracting key compliance rules and regulations from legal documents.
3. **Model Development:** Building algorithms to interpret and match code against compliance standards.
4. **Validation:** Validating the model's accuracy and reliability in compliance checking scenarios.

Detailed methodologies and scripts for training Karna are available in the `training` directory.

## **Model Inference**
Karna's inference capabilities allow it to analyze new code submissions in real-time. Users receive immediate feedback on compliance status and actionable insights on necessary modifications.

## **Model Testing**
We rigorously tested Karna using metrics tailored to compliance checking, ensuring robust performance across various code samples and legal frameworks. Test results and evaluation scripts can be accessed in the `testing` directory.

## **User Experience (UX)**
Karna offers an intuitive user interface designed for data scientists and developers. It supports interactive sessions where users can query specific legal clauses or receive guidance on compliance issues related to GDPR, CPA, and other regulations. Setup instructions and UX documentation are provided in the `UX` directory.

## **Key Risks and Future Work**
While Karna represents a significant advancement, ongoing challenges include adapting to evolving legal standards and expanding its knowledge base to cover additional regulations. Future work will focus on:
- Enhancing real-time compliance checking capabilities.
- Integrating more legal frameworks and updates.
- Improving user feedback mechanisms based on interaction data.

## **Meet the Team!**
Our dedicated team of AI researchers, legal experts, and software engineers collaborated to develop Karna:
- **Aashai Avadhani:** Lead ML and AI Expert
- **Ankit Gubiligari:** Data Scientist
- **Nakul Vadlamudi:** Data Scientist
- **Tyler Sapsford:** Data Scientist

Contact details for our team members can be found in the `team` directory.

---

We believe Karna will revolutionize compliance checking in software development and data science, providing valuable support to data scientists and developers, and lightening the load for legal professionals as well as programmers. For detailed documentation and to start using Karna, please refer to the resources available in this repository.
