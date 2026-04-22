---
layout: default
title: Proposal
---

# Proposal

**Outlook Phishing Detection Extension for Students**

**Jordan Rodriguez Computer Science**

**Background**

Phishing is one of the most commonly used forms of cybercrime, using fake emails and websites to deceive users into providing sensitive information like passwords, financial records, and personal information. These attacks are mainly done by impersonating someone the user trusts and convincing them to interact with malicious links or provide private information. Phishing is highly used today, with nearly 90% of organizations reporting facing phishing attacks (Alkhalil et al., 2021).

College students are particularly vulnerable to phishing attacks because of how frequently they receive emails regarding sensitive data like financial aid, student account verification, and student job opportunities. Attackers use fake accounts to imitate these emails, making students believe they are coming from credible sources. This makes it hard for students to identify which emails are phishing attacks, since they closely resemble official emails.

While there are already ways to prevent phishing attacks, like using a blacklist on known phishing links, these traditional methods cannot detect new threats (Tang & Mahmoud, 2021). To solve this, machine learning has emerged as a new approach to prevent phishing attacks by analyzing components of an email to ensure it is valid and not an imitation (Tang & Mahmoud, 2021). Machine learning can learn to find patterns in what makes an email legitimate or malicious, which is useful when facing an evolving threat like phishing (Alkhalil et al., 2021).

This project aims to develop an Outlook extension for students that uses machine learning to accurately detect and alert students to phishing scams in their email.

**Methodology**

First, data will be gathered from public phishing databases such as PhishTank and Kaggle. Then, the data will be preprocessed to collect key features such as sender addresses, link URLs, and suspicious keywords and phrases that may indicate phishing. Both phishing scams and legitimate emails will be collected to help identify the differences between the two.

Next, machine learning models using Naive Bayes classifiers will be trained using the data gathered from the databases to identify whether emails are legitimate or phishing scams. The models will be evaluated on metrics such as accuracy, precision, and recall.  
Finally, a prototype Outlook extension will be designed to analyze emails for phishing scams and give an explanation of why the email is a phishing attack. The extension will be built using JavaScript and the Outlook Add-in APIs. The extension will be tested by a sample of 10 students, who will try the prototype and provide feedback on accuracy and usability. The students will be emailed a digital Amazon gift card upon completion of testing. The extension will be tested and evaluated on its ability to correctly identify phishing attacks and how helpful its feedback is to the users.

**Anticipated Outcomes**

The expected outcome of this research is a functional prototype Outlook extension that helps students detect phishing emails. The prototype should accurately detect potential phishing threats and alert the user while providing a clear explanation for why the threat was flagged. Additionally, the project will contribute to a better understanding of how machine learning can be used to assess security threats, such as phishing. The project results are planned to be presented at the Showcase of Undergraduate Research Excellence at UCF.

**Significance**

- Develops a phishing detection tool that helps reduce the risk of users accidentally giving out private or personal information through email scams.
- Focuses on helping students, which additionally benefits universities by reducing the chances of security incidents and compromised student accounts.
- Provides insight into how phishing scams target students and demonstrates how machine learning can be applied to email security.

**References**

Alkhalil, Z., Hewage, C., Nawaf, L., & Khan, I. (2021). Phishing attacks: A recent comprehensive study and a new anatomy. _Frontiers in Computer Science_, _3_. <https://doi.org/10.3389/fcomp.2021.563060>

Tang, L., & Mahmoud, Q. H. (2021). A survey of machine learning-based solutions for phishing website detection. _Machine Learning and Knowledge Extraction_, _3_(3), 672-694. <https://doi.org/10.3390/make3030034>

**Timeline**

| **Dates**                             | **Tasks**                                                         |
| ------------------------------------- | ----------------------------------------------------------------- |
| January 1, 2027- January 20, 2027     | Identify common phishing scams, collect data, and preprocess data |
| January 21, 2027 - February 15, 2027  | Develop machine learning models and begin training models         |
| February 16, 2027 - February 28, 2027 | Evaluate performance and make improvements to models              |
| March 1, 2027 - March 15, 2027        | Design Outlook extension prototype                                |
| March 16, 2027 - March 25, 2027       | Test design and analyze results                                   |
| March 26, 2027 - May 5, 2027          | Finalize results and prepare final report                         |

**Budget**

| **Item**                     | **Units and Cost**                                     | **Total** |
| ---------------------------- | ------------------------------------------------------ | --------- |
| Google Cloud Virtual Machine | 1 instance, 75 hours,<br><br>\$2 per hour              | \$150     |
| Google Cloud Storage         | 50 Gigabytes, 5 Months<br><br>\$1 per month            | \$5       |
| Incentives for Participants  | \$10 Amazon gift card per participant, 10 participants | \$100     |
| **Total**                    |                                                        | **\$255** |
