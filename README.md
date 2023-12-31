# AI_Clean_Email_Modeling
Clean and Green Email : Ranking and multi-classification Problem -AI solutions

python/Google Co-lab File: capstone_Final.ipynb


Title: AI-Driven Eco-Friendly Email Management for Enhanced Productivity in the Automotive Industry


Emails are the MOST important communication in any organizations or schools or industries. Influx of messages every day in millions to various users such as Doctors, Engineers, Managers and students can waste THEIR AND PUBLIC time if they are not prioritized or not ranked

Problem Statement

Creating clean and green email communication for professionals like managers, scientists, engineers, and doctors is important. Optimizing email visualization using smart AI algorithms can significantly enhance email communication's efficiency and environmental impact. Motivation for the Project: Clean and Green Singapore. https://www.cgs.gov.sg/. The requirements of this project were provided by David Woon, from Continental Automotive Singapore.

Proposed solution:

Data Collection and Labeling: • A significantly large and diverse dataset of emails from enron (Reference 1) is considered for training AI models. The dataset was modified based on the person, who suggested the project. The modification is provided in preparatory.ipynb • First, a dataset (smartcontinental.csv) of 9571 observations was obtained from an enormously large dataset. These emails are labelled according to specified categories (time_waste, reply, required_response). • Next, a dataset (email_details.csv) of 4521 observations was obtained to understand the body of the email and its contents are studied and summarized for insights.
Priority Ranking: • Develop a priority ranking algorithm that takes into account the labels assigned to each email (time_waste, reply, required_response) and any additional factors like sender importance or email urgency.
Recommendation System: • Implement a recommendation system that suggests actions based on the priority ranking. For example, if an email is classified as "required_response," the system could recommend replying promptly.
Natural Language Understanding (NLU): • To understand the content of emails, NLU techniques, such as sentiment analysis, entity recognition, and topic modelling is considered. This can provide insights into the email's content. By considering these points, we can ensure that the email response recommendation and classification system is robust, customizable, and capable of meeting the specific needs of different organizations and users.
Reference 1: The Enron Email Dataset | Kaggle

https://www.demandsage.com/how-many-emails-are-sent-per-day/

https://earthweb.com/how-many-emails-does-the-average-person-receive-per-day/#:~:text=billion%20by%202023.-,2.,by%20an%20average%20office%20worker

https://www.slicktext.com/blog/2019/06/survey-workplace-communication-statistics/#:~:text=Almost%20half%20(45.6%25)%20of,some%20emails%20in%20their%20inbox

https://www.digitalinformationworld.com/2023/01/people-spend-33-less-time-reading.html#:~:text=Back%20in%202018%2C%20studies%20showed,considered%20and%20taken%20into%20account

https://hbr.org/2019/01/how-to-spend-way-less-time-on-email-every-day#:~:text=The%20average%20professional%20spends%2028,120%20messages%20received%20per%20day

https://hbr.org/2019/01/how-to-spend-way-less-time-on-email-every-day#:~:text=The%20average%20professional%20spends%2028,120%20messages%20received%20per%20day
