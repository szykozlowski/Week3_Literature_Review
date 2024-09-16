# Szymon Kozlowski - Week 3 Literature Review on Natural Language Programming

## Overview

While using English as a programming language was less plausible just a few years ago, the recent rise of large language models has made natural language programming a reality.  In this literature review, I'll dive into the concept of natural language programming with the help of GPT-4.  I've come up with a list of specific questions I'll be exploring with GPT-4, and I'll include a curated list of its answers below.

## Primary Questions

1.) What are the advantages/disadvantages of natural language programming?

2.) Are there any natural languages that would be especially good or bad to program in?

3.) To what extent should new software engineers be interacting with large language models when learning how to program?  Could excessive interactions with these models stunt the growth of new software engineers?


## What are the advantages/disadvantages of natural language programming?

### Advantages

1.) Accessibility for Non-Programmers

* NLP makes programming more accessible to individuals who may not have formal training in traditional programming languages. It allows users to interact with systems using natural language commands, enabling a broader audience to automate tasks and solve problems.
  
2.) Improved Productivity

* For simple or straightforward tasks, users can generate code quickly using natural language instructions. This can be useful for rapid prototyping or when trying to sketch out functionality without worrying about the specifics of syntax or formal logic.

3.) Task-Specific Automation

* Many repetitive tasks, like file handling, scheduling, or simple data analysis, can be easily automated through natural language instructions. Non-technical users can automate their workflows without needing complex programming knowledge.

### Disadvantages

1.) Ambiguity and Vagueness

* Natural languages like English are inherently ambiguous, which can lead to confusion or misinterpretation by the system. A statement like “sort the list” might not specify in what order or how ties should be handled. The system may interpret vague instructions differently from what the user intended.

2.) Complexity in Handling Context

* Natural language programming systems must keep track of context throughout the conversation, which can be challenging. For example, referring to "it" or "this" in a sentence could be unclear to a system that doesn't fully understand the prior steps or objects being discussed.

3.) Performance and Scalability Issues

* For complex programs, natural language inputs can become cumbersome and inefficient. NLP systems may produce bloated or inefficient code because they prioritize understandability over optimization. As the scale of the program grows, natural language may not be the most efficient way to specify detailed logic and behavior.

4.) Handling Edge Cases and Error Management

* Natural language instructions tend to focus on the “happy path” or the expected outcome, often overlooking edge cases. For example, an instruction like “sort the list” might not consider what happens if the list is empty or contains non-comparable elements, leading to potential errors.

5.) Lack of Formal Structure

* Natural language often falls short when trying to express advanced programming concepts like recursion, concurrency, or memory management. These are easier to handle in formal languages where constructs like loops, conditionals, and data structures are explicitly defined.

### Follow-Up Question: Do you think that natural language programming will expand past the domain of non-technical users?

* Yes, it's quite possible that natural language programming (NLP) will expand beyond the domain of non-technical users and become increasingly relevant for technical users and professional developers. Here’s why and how that expansion might occur:

* For experienced developers, NLP can speed up the process of generating boilerplate code, setting up standard functionalities, and scaffolding new projects. This allows developers to focus more on complex problem-solving and less on routine coding tasks.

### It's apparent that natural language processing can be useful for smaller tasks.  How could it help with massive codebases with a vast context?

* NLP can improve the ability to search and retrieve relevant code snippets or documentation from large codebases. By using natural language queries, developers can locate specific functions, classes, or comments, and understand their context within the codebase.

* NLP can automatically generate documentation and comments for code, improving readability and maintainability. This includes generating docstrings for functions and classes, explaining their purpose, parameters, and usage.

* NLP tools can analyze large codebases and suggest refactorings to improve code structure, readability, and performance. This includes identifying code smells, redundant code, and opportunities for optimization.

## Are there any natural languages that would be especially good or bad to program in?

### Natural Languages That Might Be Especially Good for Programming:

1.) German

* German is known for being precise in its expression, often forming long compound words to convey exact meanings. This could help in reducing ambiguity when specifying tasks in a program.
Logical Structure: The language tends to follow strict rules, especially with word order and case, which could be beneficial for creating consistent and unambiguous instructions.

2.) Finnish

* Finnish has highly regular grammar and is considered very consistent in its use of cases and suffixes, which might lend itself well to systematic interpretation in programming.

3.) Mandarin Chinese

* Mandarin is a highly concise language, often expressing ideas with fewer words than other languages. This brevity could reduce verbosity in programming instructions.

### Natural Languages That Might Be Especially Bad for Programming:

1.) English

* English is filled with homonyms, polysemy (words with multiple meanings), and vague expressions, making it difficult for a system to resolve ambiguities reliably.
* English has many irregular verbs, inconsistent spelling, and a flexible word order, all of which could lead to confusion when translating into precise programming instructions.
* English relies heavily on context and pronouns, which are difficult for computers to track effectively. For example, “it” or “this” could refer to any number of objects or actions previously mentioned, creating ambiguity.

2.) Arabic

* Arabic has a rich morphological system with root-based word formation, which can result in multiple forms of a word depending on tense, mood, voice, etc. This complexity could make it harder to parse instructions reliably.

3.) French

* French uses complex verb conjugation systems with many tenses and moods, which could make parsing difficult for a natural language programming system. Misinterpretations of tense could lead to incorrect instructions.

### Follow-Up Question: How would an individual's mastery and understanding of the natural language being used for programming affect the output of the program?

* A deep understanding of the natural language allows individuals to use context more effectively. This helps in framing instructions that are better understood by the system, leading to higher-quality and more relevant code. For example, correctly specifying how a function should handle different edge cases or user inputs improves the robustness of the generated code.

* Mastery of domain-specific language and terminology can enhance the ability to generate code that is appropriate for a particular field (e.g., finance, healthcare). Using the correct terminology and context-specific language ensures that the generated code aligns with industry standards and practices.

## To what extent should new software engineers be interacting with large language models when learning how to program?  Could excessive interactions with these models stunt the growth of new software engineers?

### Potential Risks of Over-Reliance on LLMs:

* Superficial Learning: Excessive dependence on LLMs for answers and code generation might lead to superficial learning. New engineers might not fully grasp underlying principles if they rely too heavily on automated solutions without understanding the "why" behind the code.
Reduced Problem-Solving Skills: Relying on LLMs to solve problems may prevent learners from developing strong problem-solving and debugging skills, which are crucial for becoming proficient software engineers.
Lack of Deep Engagement

* Minimal Hands-On Practice: If learners are constantly getting answers and solutions from LLMs, they might miss out on the valuable experience of wrestling with problems and experimenting with different approaches.
Decreased Critical Thinking: Over-reliance on LLMs could diminish critical thinking and analytical skills. Engineers might become accustomed to accepting the first suggestion provided by the model rather than critically evaluating and understanding different solutions.
Dependence on External Tools

* Tool Dependency: Heavy reliance on LLMs might create dependency, making it challenging for new engineers to work effectively without them. They might struggle with tasks where LLMs are not available or when working in environments where automated assistance is limited.
Potential for Misguidance

* Accuracy Issues: LLMs are not infallible and can sometimes provide incorrect or suboptimal solutions. New engineers might not have the experience to identify and correct these issues, leading to potential misunderstandings or poor coding practices.
Misconceptions: If not used carefully, LLMs might reinforce misconceptions or outdated practices, especially if the training data includes inaccurate information.
Best Practices for Integrating LLMs into Learning
Use as a Supplement, Not a Crutch

* Guided Learning: Use LLMs to supplement learning by providing additional explanations, examples, and feedback, but ensure that learners also engage deeply with the material through hands-on practice and independent problem-solving.
Encourage Active Engagement

* Problem-Solving Exercises: Encourage learners to work through problems and challenges on their own before seeking assistance from LLMs. This helps build resilience and problem-solving skills.
Review and Reflection: After receiving assistance from LLMs, learners should review and reflect on the solutions to understand the rationale and underlying concepts.
Focus on Fundamentals

* Conceptual Understanding: Emphasize the importance of understanding fundamental programming concepts and principles, rather than just seeking quick answers or code snippets.
Manual Coding Practice: Ensure that learners spend significant time coding manually and developing their own solutions, which helps reinforce their understanding and skills.

### Follow-Up Question: Do you think universities should warn students of the dangers of abusing large language models?

* Without proper guidance, students might become overly dependent on LLMs for generating code, solving problems, or completing assignments, which can hinder their development of essential problem-solving and critical thinking skills.**

* Over-reliance on LLMs can lead to gaps in fundamental skills, such as coding, debugging, and problem-solving. By highlighting these risks, universities can encourage a balanced approach to using LLMs as a supplement rather than a substitute for learning.


## References

Ferdiana, Ridi. (2024). The Impact of Artificial Intelligence on Programmer Productivity. 

L. A. Miller, "Natural language programming: Styles, strategies, and contrasts," in IBM Systems Journal, vol. 20, no. 2, pp. 184-215, 1981, doi: 10.1147/sj.202.0184.

Michael D. Ernst. Natural Language is a Programming Language: Applying Natural Language Processing to Software Development. In 2nd Summit on Advances in Programming Languages (SNAPL 2017). Leibniz International Proceedings in Informatics (LIPIcs), Volume 71, pp. 4:1-4:14, Schloss Dagstuhl – Leibniz-Zentrum für Informatik (2017)

Biermann, A., Ballard, B., and Sigmon, A. An Experimental Study of Natural Language Programming. International Journal of Man-Machine Studies, Vol. 18, pp. 71-87, 1983.

## Conclusion

While natural language programming certainly has its applications, its limitations are made clear through the discussion with GPT-4. Programming languages were designed with programming in mind, while natural languages were not.  This distinction is enough to show why coding will be done with programming languages rather than natural languages for the foreseeable future.

Moreover, this conversation has helped clarify why over-reliance on LLMs can harm new engineers. Typically, a software engineer’s cognitive process involves translating natural language descriptions of problems into executable code—a mental "compilation" process. This mental exercise sharpens their understanding of the programming language and problem-solving strategies. However, when engineers use LLMs extensively, this cognitive process is outsourced to the tool. The model performs the translation from natural language to code, effectively bypassing the engineer's own mental processing.

This shift can lead to several issues. Without mentally compiling the code, engineers miss out on critical learning experiences and developing problem-solving skills. The tool’s assistance might not always align with best practices or provide optimal solutions, and relying on it too much can lead to a superficial understanding of programming concepts. Thus, while LLMs can be incredibly useful as a supplement, new engineers must use them judiciously and continue to engage deeply with the underlying principles of programming to build a solid foundation.
