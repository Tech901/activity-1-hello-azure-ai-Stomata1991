# Reflection -- Hello, Azure AI

Answer these questions after completing the activity (2-3 sentences each). Connect your answers to specific things you observed while coding and experimenting.

## 1. Service Surprises

Which of the three Azure AI services (OpenAI, Content Safety, Language) surprised you the most? Connect this to something specific you observed during your experiments -- a response you didn't expect, a behavior that seemed too easy or too hard, or a result that made you rethink how the service works.
Nothing about the services surprised since I did not understand at all what was going on with this assigment. The instructions were vague at best and seemed to rely on knowledge not yet covered. There was not even a reference to potential sources that could clarify the asks of the assignment.

## 2. Lazy Initialization

How would you explain the lazy initialization pattern to a colleague? Why is it used instead of creating clients at the top of the file?
This method delays calling a service until it needed in the code, thus preventing on initial overload in resource consumption as the program starts up. 

## 3. Content Safety in the Real World

A resident files this complaint: *"A man was assaulted at this intersection because the street light has been out for months."* This text describes real violence but is a legitimate safety concern. Should the system block it, flag it for human review, or pass it through? What factors would you weigh in making that decision?
This would probably need to be flagged for human review. The existence of legitimate issues within the complaint should be passed on for consideration since it is alleged the issue caused harm and likely needs prompt attention. As there are elements that would violate a content safety threshold of 0, it should not be passed along without human review. 
