# credentially-bi-tech-assignment

A reference is requested for a specific candidate to verify their reliability with third parties. Once a reference is requested, it goes through the stages of **"submitted"** and then **"reviewed."** It is important to receive and review the reference as soon as possible to speed up the hiring process.  

In the repository, you will find a pre-prepared semantic model along with sources describing references, the job positions for which they were requested, and some other data related to job positions.  

### Task  

1. **Fork the provided repository to your own account.** Please complete the assignment within this forked repository.
2. **Load and analyze the data** that will be used to build this report. What issues do you see with the data, and how can they be addressed?  
3. **Build a simple dashboard** based on the prepared semantic model and some calculations that may be useful to you. Highlight the key metrics that you would emphasize for the client as the most significant in the context of references. Feel free to modify the semantic model/calculations for your purposes.  
4. **When you are finished, please send us the link to your forked repository** with the changes you made, including your dashboard. If you have any questions, please don't hesitate to ask.



### Main Data Issues  

1. Inconsistent Time Stamps - Some negative, some 
2. Inconsistent completed/reviewed dates, resulting in negative duration.
3. A lot of Null Values
4. Columns that had values, even tho they shouldn't have.
5. Test Data Present (could be removed, but due to the limited data)

### Video Walkthrough

Please find on the email I sent with the repo link a video link walkthrough of my explanation and reasoning why I did certain decisions.

### Conclusion

This has been very fullfilling task, and I tried to make something visually appealing and highly valuable, in a short ammount of time. 

In total I spent about: 
    1 hour analysing the data and understnading the main issues 
    2.5 hours coming up with the design, KPIs I wanted to represent, DAX Queries behind the measures

I am excited to further explain certain decisions I took when building this dashboard, and I believe this dashboard it self can be built upon to leverage other sources of data and creating new pages. 

I built the global view dashboard, but further pages could look a bit further into specific job roles, to analyise the time it takes for each job role and if there is any correlation between the job roles and the duration.

As it was a Global dashboard, I decided to only keep a time range filter, as this was more approriate. Due to the low volume of data, filtering on something more specific on the global view would make the visualization not as insighful.
