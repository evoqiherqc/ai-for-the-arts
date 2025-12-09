# AI for the Arts and Humanities: A Critical Portfolio
**Author:** [ID]

## Project Overview
This portfolio is a record of my attempt to make sense of some fairly basic and central coding and machine learning ideas, whilst using AI as an assistant. I reflect on what went well and what went badly, and the impact of using Microsoft Copilot.

The goal wasn't just to make code that "works," but to understand *why* it works and, more importantly, where it fails.

## Portfolio Structure
The work is organized into three core components:

### 1. Foundational Skills (`coding_exercises.ipynb`)
This is where I started. The goal was to prove I could actually read code, not just copy-paste it.
* I tried to move away from technical computer science terms where I couldl, and move towards analogies and familiar themes to improve my understanding and memory of new ideas
* It covers Python fundamentals (Variables, Loops, Functions) and multimedia processing (images/audio)

### 2. Critical Machine Learning (`Machine-Learning-by-Example-from-Start-to-End.ipynb`)
This was more of a deep dive that included more reflection on impacts and ideas. I took standard ML workflows (Housing Prices & MNIST Digits) and critiqued them and tried to understaand them by involving my own thoughts and ideas.
* I used the Caledonian MacBrayne ferry crisis to explain Omitted Variable Bias (showing how can AI miss context).
* I argued that AI potentially  "sanitises" culture by grouping art by Label rather than Vibe, for example by neglecting the nuance different artworks.
* It documents my specific struggles with Tensorflow Playground, discussing my failures and successes.

### 3. Conceptual Design (`LLM_Design_Proposal.ipynb`)
*Note: This section is the final capstone (Part 4).*
A proposal for the **"Socratic Sparring Partner."** Instead of an AI that answers questions (which risks causing cognitive atrophy), this is a design for an AI specifically programmed to challenge the user, acting as a Devil's Advocate to improve critical thinking.z

---

## Critical Reflection on AI Assistance
I used AI tools (Microsoft/Github Copilot) throughout this project, a coding partner/teacher, as a formatting assistant and note maker (I could give a big messy free flow of thoughts and ideas at each stage of reflection and it could organise my thoughts). Using AI was a bit of double edged sword; sometimes it improved my unuderstanding and saved me time; other times it made errors, confused me, and ended up wasting time.

### The Pros
* **Code Explanation:** It was excellent at breaking down code. I could highlight a specific chunk that confused me, and it would explain line-by-line what was happening. It helped me understand *how* the code worked rather than just providing a solution, acting almost like a tutor.
* **Structuring Thoughts:** It acted as a very efficient secretary. I could dump a messy stream of consciousness—especially for the Machine Learning reflections—and it would tidy those notes into bullet points or coherent themes without losing my original points. This allowed me to focus on the ideas rather than the formatting.
* **Metaphor Extension:** It was good at "playing along" with my analogies. When I suggested comparing data diversity to an **"Immune System,"** it didn't reject the idea. Instead, it helped me map that metaphor to the technical concepts of *Domain Shift* and *Generalization*, which helped solidify my understanding.

### The Cons
* **Gaslighting:** The most frustrating part was when the AI hallucinated that code was working when it wasn't. When I flagged an error, it would often insist the code was correct and suggest the problem was my laptop settings or software. After wasting time chasing these ghosts, I’d usually find out the error was just a simple syntax typo the AI had missed.
* **Context Blindness:** The AI constantly forgot who the audience was. It defaulted to "Computer Science" efficiency, trying to make every line of code as short as possible. I had to constantly fight it to keep my verbose, descriptive variable names (like `archive_box` instead of `x`) so that a Historian could actually read and understand the work.
* **The "Yes Man":** It struggled to be a critic. If I suggested a bad idea, it would often prioritize being "helpful" over being "right," generating code for a flawed approach rather than warning me it wouldn't work. It reinforced that I couldn't autopilot; without human oversight, it would have happily led the project off a cliff.

### Workarounds & Takeaways
* I found that if I accused the AI of being wrong, it often got defensive or stubborn. It worked much better if I explained *why* I thought it was wrong and asked it some reflective questions; same as a human. If it got stuck in a loop, I learned to force a "break." I would change the topic entirely - asking it about the Arsenal game, the health benefits of fermented foods, or the origins of Halloween. When I returned to the code or the conversation after this "reset," it was often more responsive and open to new ideas - again probably the same as a human.
* When the AI blamed my laptop settings or gave me a solution I didn't trust, I stopped arguing with that specific chat. Instead, I would open 2 or 3 separate chats, ask them the same question, and ask them to "rank solutions by likelihood." It is energy inefficient and takes longer upfront, but it prevented me from rabbit-holing down a wrong path.
* Using speech-to-text I would speak aloud my thoughts freely and flowingly and make notes to myself and the AI would transcribe and then format my ideas into groups. This was excellent for creativity, but I noticed a flaw in how the AI listens. It tends to weight every idea equally. I might speak 2 sentences about a minor side-thought and 10 sentences about a central idea, and the AI would treat them as equally valid. I learned I had to be very explicit about which points were the core and which were spin-offs, otherwise it wouldn't prioritise.
* The AI had a default "positivity bias" that was genuinely annoying. It would often compliment a flawed idea just to be nice. I found that I had to explicitly tell it to be "harsh," "pernickety," or to "play Devil's Advocate." Once I gave it encouragement to be critical, the feedback became much more useful.
* Finally, a warning for future practice: AI is a massive distraction risk. When working with a human, the back-and-forth is natural. With AI, the slight delay in generating a reply - or the frustration of having to argue with it - often broke my flow. I found myself checking my phone or losing concentration during these micro-pauses. In the future, I will be more cautious about using it during deep-focus blocks, as the wee distractions add up to a lot of time wasted.