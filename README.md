# GoEat Engineer Recruitment Test
Quick test for engineers who would like to join GoEat awesome team.

Thank you for taking the time to do our technical test. It consists of two parts:
- Coding test.
- A few techical quetions.

In order to avoid bounced emails we would like you to submit your results by attached a relevant file ZIP into email named technical_interview-{yourname}-{role-applied-for} and send it to talent@goeat.me.

Please make this a single zip file containing:

1. A single markdown file with the answers to the technical questions.
2. One folder containing the technical test.

# Coding test

GoEat manages a lot of different dishes with different ingredients and cuisines. In order to make a better search UX, we structure different tags for each dish. For example, Pho will have Vietnam, rice tags. These tags have parent-children relationship. For example, Vietnam tag is the children of Southeast Asia tag, Southeast Asia tag is the children of Asia tag. 

From the parent tag, the user can find all the tagged dishes and its sub tags. I.e. Vietnam tagged Pho and Vietnamese bread, Southeast Asian tagged noodles, Asian tagged rice. The relationship between the above parental structure is from right to left following Asia > Southeast Asia > Vietnam. When the user types Asian, the result is rice, noodles, Vietnamese bread, noodles. Southeast Asia is noodles, bread, pho. And Vietnam is Vietnamese bread, pho. 

The task is implement an application that meets the above requirements. Use this file as data sample.

# Task requirements
Feel free to spend as much or as little time on the exercise as you like as long as the following requirements have been met.

- Your code should compile and run in one step.
- Feel free to use whatever frameworks / libraries / packages you like.
- Please avoid including artifacts from your local build (such as NuGet packages or the bin folder(s)) in your final ZIP file.

# Technical questions
Please answer the following questions in a markdown file called Answers to technical questions.md by Vietnamese or English. 

1. How would you track down a performance issue in production? Have you ever had to do this?
2. What do you think about how should we do to build a high thoughput system?"

