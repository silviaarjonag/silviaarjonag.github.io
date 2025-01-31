---
layout: essay
type: essay
title: "Asking the Right Way: Smart vs. Bad Questions"
# All dates must be YYYY-MM-DD format!
date: 2025-01-30
published: true
labels:
  - Smart Questions
  - Computer Science
---
<img width="200px" 
     class="rounded float-start pe-4" 
     src="../img/askingquestion.png" >

## The Importance of Smart Questions in Software Engineering
As software engineers, good communication is one of the most important skills we must develop. Specifically, knowing how to ask questions in a way that increases the chances of receiving helpful answers is crucial. Eric Raymond's essay _How to Ask Questions the Smart Way_ outlines principles for asking questions that are clear, well-researched, and focused. This essay will take a look at both a smart question and a bad question from StackOverflow, showing how they reflect these principles and the different outcomes they generate.

## The Smart Question: Optimizing C++ Code
One example of a smart question can be found in this StackOverflow post: 

[Can I write while(auto p = get_optional<pair<any, T>>()) smarter in modern C++?]([https://github.com/silviaarjonag/tic-tac-toe](https://stackoverflow.com/questions/79401448/can-i-write-whileauto-p-getoptionalpair-any-smarter-in-modern-c))

In this question, the user asks whether the following C++ code can be written more effectively using modern C++ practices:

    while (const auto optionalIndexedValue = getNextValue()) 
    {
      const auto& [index, value] = *optionalIndexedValue;
      // use index and value
    }

The user is specifically asking if this code can be made "smarter." They are not seeking a general explanation of how auto or optional works but instead looking for improvements in how the code could be written.

## Why This is a Smart Question
**Clarity and Specificity:** The question is very specific, addressing one piece of code and asking for improvements. The user focuses on a particular part of the code rather than asking about broader topics.

**Context and Background:** The question is brief but clear. While the user doesn’t describe the exact problem they’re facing, the question is still easy to understand. The code snippet provides enough context for the community to respond effectively.

**Effort Displayed:** The user has clearly made an attempt to write the code themselves and is seeking improvements. By providing the code snippet, they show how they've already worked on the problem and are looking for advice on how to improve it.

**Focus:** The focus of the question is narrow, addressing only the refinement of a specific part of code. This helps responders give targeted advice.

This question is an great example of the "smart way" to ask a question because it is clear, focused, and demonstrates effort. As a result, the responses to this question are likely to be precise, actionable, and helpful.

## The Bad Question: Vague and Unfocused
To compare, let's consider a bad question that fails to follow the principles laid out in Eric Raymond's essay.

This question was produced by AI as an example.

[Why doesn’t my C++ code work?]

The user asks why their C++ code doesn’t work but provides no further information. There is no code snippet, no error message, and no explanation of what the code is intended to do.

## Why This is a Bad Question
**Vague and Non-Specific:** The question is too vague. The phrase "Why doesn’t my code work?" could refer to any issue in the code, but no context is provided. Without any details, it’s impossible for others to offer a useful answer.

**No Code or Context:** A key part of asking a smart question is including the relevant code and providing context. Even if there were code, the lack of explanation of what the user expects would still leave responders guessing.

**No Effort Displayed:** The question doesn’t demonstrate any effort on the user’s part to resolve the issue. It appears as though they haven’t attempted to investigate solutions before posting. Asking for help without demonstrating any prior research or effort reduces the chances of getting a helpful answer.

**Broad and Open-Ended:** The question is too broad. It's unlikely that anyone can provide a useful response.

## Conclusion: Why Smart Questions Matter
Asking questions the smart way benefits both the person asking and the community that responds. By being clear, specific, and providing context, a smart question helps others understand the problem and provide more useful advice. It also shows that the person asking the question is trying to solve the issue and has already made an effort to learn.

By following the principles outlined in Eric Raymond’s essay, software engineers can improve their communication skills as well as save time. In contrast, vague or unfocused questions waste time for both the asker and the responders.

In conclusion, taking the time to ask questions the smart way is a valuable skill that can improve a developer's learning and problem-solving experience.
