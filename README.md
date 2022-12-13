# SNHU-CS305
The focus of this assignment is to work alongside the client, Artemis Financial, to incorporate security measures into their existing application. As they handle financial data on an international level, there are certain governmental requirements in place that need to be adhered to.
Given the news in contemporary times, it is not difficult to see the necessity that is proper and adequate security. The damage done to a company can go far beyond any financial hit that takes place due to ransomeware attacks; their reputation is also tarnished, potentially leading to further loss of revenue from its stocks taking a dive. 
We implemented Maven static testing into the application. At first glance, this long list of vulnerabilities was very overwhelming. But as we progressed through the course, we learned that some of these could be due to false positives, which we could verify against OWASP’s database and filter out. But the report this generates offers vital insight into the potential exploitable areas of our code. These can then be manually reviewed and patched or refactored as needed. And, after any major revisions to the code, it is a good idea to rerun the Maven report, to make sure no new vulnerabilities were worked into it. Other helpful resources is, naturally, Google and Stackoverflow. These I had used in the past, but checking out OWASP’s vulnerability database was a new tool I discovered in taking this class, which will be incredibly useful for future assignments and projects.
Last, I feel that perhaps more important than showing potential employers what you know, is how you learned it, that process of figuring out new aspects of development. In this case, it would be incorporating Maven for static testing, and figuring out how to analysis its exploit report.
