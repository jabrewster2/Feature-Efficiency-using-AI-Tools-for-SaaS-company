# Feature-Efficiency-using-AI-Tools-for-SaaS-company
# Executive Summary
A software as a service company wanted to know if the implementation of AI development tools at the start of Q2 for their engineers has increased performance while keeping the same level of quality code. Using Python, Pandas, and PowerBI, I pulled feature development lengths, incident frequency, feature release frequency, and AI usage cases to create a dashboard to track efficiency for non-technical stakeholders. After pulling together the information I concluded the following.
1. Post-AI incidents per 100 deployments are down by 16.67%
2. Entry and Senior level roles save ~5 hours of development time per feature.
3. Features released per month has gone up but incidents per month have increased proportionally.

# Business Problem
Features release frequency has gone up but so has the number of incidents and time spent to fix those incidents. Clients have loved the new features the SaaS company has provided them but they have noticed that the service is down more frequently. What can we gather from company information about the introduction of AI development tools and its effect on the employees' productivity and the user's experience using the product?

# Methodology
1. Use Pandas to clean data and prepare it for SQL and PowerBI analysis.
2. Use SQL to create tables and get a basic understanding of correlation and causation of incidents and features.
3. Make a dashboard in PowerBI to visualize changes post-AI and give suggestions based on the information.

# Skills
Python: Pandas
SQL: Aggregate Functions, Joins, Table Creation, Case Expressions
PowerBI:  writing functions, ETL, calculated columns, data visualization, data modeling

# Results and Business Recommendation
This analysis showed us that engineers using AI development tools have an incident rate that is 16.67% lower that not using AI. The developers also cut down their time developing by 11.35% on average allowing them to start the next project earlier. While this is good news for efficiency the negative to this new implementation has been the downtime. The number of incidents on average is the same for Q2-Q4 the time spent fixing incidents in Q3 was almost the same time as Q1 and Q2 combined. 
<img width="1561" height="895" alt="image" src="https://github.com/user-attachments/assets/c8a826bd-817c-4fd3-9488-213d09de32fd" />
<img width="528" height="529" alt="image" src="https://github.com/user-attachments/assets/251a4f91-2369-4ade-8d7d-8c8efdf5cd5d" />


Because of this massive shift of downtime users might be forced to use a different product so I recommend the adjustments.
1. Train the engineers in better AI practices such as a manual code review.
2. Dedicate resources to 3rd party code review within the company.
3. Work in small reasonable steps.
4. Decide if the cost of using AI is more profitable than before AI.

# Next Steps
1. Get feedback from users about new features and outages.
2. Put engineers through AI training
3. Review finances and make sure AI tools are worth the cost.
