# Welcome to My Masters Degree Projects Repository!

Hello and welcome to my repository! Here, you will find a collection of projects I have completed as part of my Masters degree. These projects represent the culmination of my academic journey, showcasing the skills and knowledge I have acquired throughout my studies.

Each project in this repository demonstrates my ability to tackle complex challenges and deliver innovative solutions. If you have any questions, suggestions, or feedback, please don't hesitate to reach out. I am always open to discussions and eager to collaborate with like-minded individuals who share an interest in the subjects covered by my projects.

Thank you for visiting my repository, and I hope you enjoy exploring my journey so far!

## [OptiShelf: MAximizing Sales with Smart Shelf Space Allocation](https://github.com/TheLohia/MSBA-NUS/blob/main/Operations%20Research%20and%20Analytics/Shelf_Space_Allocation_Problem.pdf)

### Motivation

With the advent of e-commerce and the rise in the efficiency of supply chains, the value of physical space in brick-and-mortar shops has increased. Driven by studies showing that the relative placement of various products on store shelves can impact the store's revenue, we attempt to formulate a model to optimize the allocation of physical shelf space to products to maximise the sale of products, while constrained by merchandising agreements, store policies and other real-world factors that influence the customer's decision to purchase a product, such as the presence of substitute and complimentary goods. This problem is otherwise known as the Shelf Space Allocation Problem (SSAP) which attempts to capture the effect of product placement on purchases and optimize for the same. 

### Outcome

We succeeded in formulating one version the SSAP problem, using simplifying assumptions. Despite the simplifying assumptions, are initial formulation was an NP-Hard problem and hence we decided to break the SSAP problem into two components. The first component solved the problem of allocating different products to different cabinets without looking. The problem of allocating apprpriate shelf pace was delegated to the second component. In this manner, we were able to arrive at a near-optimal solutions using a toy dataset and the Gurobi optimizer. 

While our solution overlooks several industry condtions, including an ever changing inventory and demands, we were able to develop a baseline to iterate and improve upon. The output from the Gurobi solver showed that the proposed solution is convergent, and can be used to maximize for potential/expected revenue. In the future scope of work, we suggest using heuristics to simplify search for the optimal solution while also using real data to eliminate the simplifying assumptions that were made in the first iteration of the solution. 
