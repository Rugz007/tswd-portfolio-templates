| [home page](https://rugz007.github.io/tswd-portfolio-templates/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Wireframes / storyboards
> Using your sketches developed last week, further develop your story outline and relevant components visually through the use of wireframing / storyboards. Using your outline as a guide, include high-fidelity, individual draft data visualizations of the critical elements of your story you want to share with your reader. Note: you can build these elements out directly in Shorthand this week if you wish.  Reminder: this template is intended to help, but it doesn't substitute for reading through the full homework assignment!  The assignment page on Canvas includes many important details for completing Part II of the final project. 
From last time, I had changed my story to focus on tackling the satisfaction problem in the software industry. After some data visualizations, I found that addressing technical debt is the biggest contributor to the generation of frustation in the software industry. I will be focusing on that in this part.

My story is a pitch for a startup - Johnathan AI - which is a AI tool which reviews the code and identifies the technical debt in the code. The tool will also provide the developers with the suggestions to fix the technical debt. This will be used when the developers are reviewing their codes weekly, usually when individual contributions are merged to the main branch - a process facilitated by a
feature called Pull Request in the version control system.

The story outline is as follows and is a lot more simpler than the previous one:
1. Introduction
    - Introduce the startup Johnathan AI
    - Introduce the founder of the company
2. The problem
    - Are software engineers really satisfied?
    - What are the common frustations in the software industry?
    - What is technical debt?
    - Why does it exist? 
3. The solution
    - Introduce Johnathan AI
    - How does it work?
    - How does it help in reducing technical debt?
4. Conclusion
    - Call to action - please invest! :)

The data I have obtained from stackoverflow wasn't the most visualization friendly and hence had to invest a significant time figuring out how to generate the tables in Python and then import them into Tableau. I have attached a clean version of the notebook in the repository.
Notebook link: [https://github.com/Rugz007/tswd-portfolio-templates/blob/main/charts.ipynb](https://github.com/Rugz007/tswd-portfolio-templates/blob/main/charts.ipynb)


I have attached the short hand link for the storyboards below:

<script src="https://carnegiemellon.shorthandstories.com/johnathon-ai/embed.js"></script>


# User research 

## Target audience

The target audience for the product is software developers. 
The target audience for *this story* is potential investors and software developers who are looking for a solution to the technical debt problem.
The story is a pitch for the startup.

1. Software Engineer #1: 
    - **Demographics**: 28-year-old
    - **Experience**: 5 years in the software industry
    - **Role**: Senior Software Engineer
    - **Company**: Large tech company
    - **Motivation**: Interested in new tools that can improve efficiency
2. Software Engineer #2:
    - **Demographics**: 35-year-old
    - **Experience**: 10 years in the software industry
    - **Role**: Tech Lead
    - **Company**: Medium-sized tech company
    - **Motivation**: Looking for tools that can streamline the code review process
3. Software Engineer #3:
    - **Demographics**: 24-year-old
    - **Experience**: 2 years in the software industry
    - **Role**: Junior Software Engineer
    - **Company**: Startup
    - **Motivation**: Want to be a better developer and learn new things

## Interview script

Before I show the wireframes, I am going to ask a few questiosn to understand their satisfaction levels working in the industry and understanding how much time they spend on these code reviews? 

Then after the wireframes or the idea is pitched, I would want to understand are the assumptions which are derieved from the data feel correct and accurate to them personally and also understand what they feel about a product like this.

| Goal | Questions to Ask |
|------|------------------|
| Understand job satisfaction | Are you satisfied as a software engineer? |
| Measure time spent on code reviews | How much time do you spend in code reviews? |
| Assess product usefulness | Do you find this product useful? |
| Identify potential concerns | Are there any concerns which you have if you were using this product? |
| Determine willingness to pay | Would you be willing to pay for this product? |
| Did I miss anything? | Is there an important detail which should be in the pitch? |

## Interview findings
I interviewed three software engineers as "VCs" to gather feedback on the product idea and the pitch. Here are the key insights from the interviews:

| Questions               | Interview 1 | Interview 2 | Interview 3 |
|-------------------------|--------------------------------|-------------|-------------|
| Are you satisfied as a software engineer? | Generally satisfied but frustrated with technical debt | Satisfied but sees room for improvement | Dissatisfied due to constant firefighting |
| How much time do you spend in code reviews? | Around 5 hours per week | Approximately 3 hours per week | Nearly 10 hours per week |
| Do you find this product useful? | Yes, it would save time and reduce frustration | Yes, especially for identifying hidden issues | Yes, it would streamline the review process |
| Are there any concerns which you have if you were using this product? | Concerned about false positives | Worried about integration with existing tools | Concerned about the cost factor and hallucinations |
| Would you be willing to pay for this product? | Yes, if it proves to be effective | Yes, if it integrates well with our workflow | Yes, if it reduces review time significantly |
| Is there an important detail which should be in the pitch? | Emphasize time-saving benefits, concered about code being "suggested" to another company (IP theft) | Highlight integration capabilities, concerns about privacy regarding code | Focus on ease of use and quick setup |

I found it pretty interesting that all developers are generally satisfied with their jobs but are frustrated with the technical debt. This is a common theme across all the interviews. 
One of the surprising insights was that all developers were willing to pay for the product if it proves to be effective - which is a good sign for the startup.
They also mentioned that fully relying on the AI tool for code reviews might not be a good idea and they would like to have a human review the code as well and hence it should tightly integrate with the existing procedures and tools.



# Identified changes for Part III

| Research synthesis                       | Anticipated changes for Part III                                                |
|------------------------------------------|---------------------------------------------------------------------------------|
| Discuss cost savings                     | Emphasize how the product can reduce costs by minimizing time spent on code reviews and decreasing technical debt. |
| Address privacy concerns                 | Ensure that the pitch highlights the measures taken to protect code privacy and prevent intellectual property theft. |
| Highlight ease of use                    | Showcase the user-friendly interface and the simplicity of integrating the tool into existing workflows. |
| Tackle hallucination issues              | Explain the steps taken to minimize false positives and ensure the accuracy of the AI's suggestions. |
