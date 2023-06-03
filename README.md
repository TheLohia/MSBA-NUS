# Welcome to My Masters Degree Projects Repository!

Hello and welcome to my repository! Here, you will find a collection of projects I have completed as part of my Masters degree. These projects represent the culmination of my academic journey, showcasing the skills and knowledge I have acquired throughout my studies.

Each project in this repository demonstrates my ability to tackle complex challenges and deliver innovative solutions. If you have any questions, suggestions, or feedback, please don't hesitate to reach out. I am always open to discussions and eager to collaborate with like-minded individuals who share an interest in the subjects covered by my projects.

Thank you for visiting my repository, and I hope you enjoy exploring my journey so far!

## [OptiShelf: Maximizing Sales with Smart Shelf Space Allocation](https://github.com/TheLohia/MSBA-NUS/blob/main/Operations%20Research%20and%20Analytics/Shelf_Space_Allocation_Problem.pdf)

### Description

We tackle the Shelf Space Allocation Problem (SSAP) to optimize product placement on store shelves, maximizing sales while considering real-world constraints such as merchandising agreements, store policies, and customer purchasing behavior.

### Outcome

We successfully formulated a simplified version of the NP-Hard Shelf Space Allocation Problem (SSAP). To tackle its complexity, we divided the problem into two components. The first component allocated products to cabinets without considering shelf space, while the second component focused on allocating appropriate shelf space within each cabinet. Using a toy dataset and the Gurobi optimizer, we achieved near-optimal solutions.

Although our solution overlooks industry conditions like changing inventory and demands, it serves as a baseline for future improvements. The output from our solver showed convergence and the potential to maximize revenue. In future work, we recommend incorporating heuristics to simplify the search for optimal solutions and using real data to eliminate the simplifying assumptions made in our initial solution.

## [JobSafe: Fortifying Job Market Integrity](https://github.com/TheLohia/MSBA-NUS/blob/main/Foundations%20of%20Business%20Analytics/Fraudulent%20Job%20Detection%20using%20ML.pdf)

### Description
JobSafe utilizes machine learning to bolster job market integrity by automatically detecting and flagging fraudulent job postings, aiming to provide a secure platform for job seekers. 

### Outcome

We implemented the CRISP-DM framework to analyze and evaluate solutions for the fraudulent job detection problem within the business context. Using a cost-benefit matrix, we identified a profitable model and recommend implementing an additional layer of verification for detected fraudulent job postings to mitigate model risk.

During the model evaluation, we considered recall as a validation metric. Surprisingly, the model with the highest recall did not yield the highest profitability based on the cost-benefit matrix. The presence of an imbalanced dataset rendered traditional metrics less reliable for measuring profitability. The cost-benefit matrix emerged as a more intuitive and effective measure of model performance and its impact on the business.

Key takeaways include the importance of aligning model selection with profitability and the need to address imbalanced data challenges. By utilizing the cost-benefit matrix, we can make informed decisions and enhance the effectiveness of fraudulent job detection while mitigating risks for the business.
