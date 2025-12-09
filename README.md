# AI for the Arts and Humanities: A Critical Portfolio
**Author:** [GUID]

## Project Overview
This portfolio is a record of my attempt to make sense of some fairly basic and central coding and machine learning ideas, whilst using AI as an assistant. I reflect on what went well and what went badly, and the impact of using Microsoft Copilot. T

The goal wasn't just to make code that "works," but to understand *why* it works and, more importantly, where it fails.

## Portfolio Structure
The work is organized into three core components, designed to be read in sequence:

### 1. Foundational Skills (`coding_exercises.ipynb`)
This is where I started. The goal was to prove I could actually read code, not just copy-paste it.
* I tried to move away from abstract computer science terms and instead move towards analogies and familiar themes to improve my understanding and memory of new ideas
* It covers Python fundamentals (Variables, Loops, Functions) and multimedia processing (images/audio)

### 2. Critical Machine Learning (`Machine-Learning-by-Example-from-Start-to-End.ipynb`)
This is the deep dive. I took standard ML workflows (Housing Prices & MNIST Digits) and critiqued them using real-world analogies.
* **The "Ferry Crisis":** I used the Caledonian MacBrayne ferry crisis to explain **Omitted Variable Bias** (showing how AI misses critical infrastructure context).
* **The "Dalí Paradox":** I argued that AI "sanitizes" culture by grouping art by Label rather than Vibe, erasing the nuance of the avant-garde.
* **The Experiments:** It documents my specific struggles with **Tensorflow Playground**, detailing the failures (brute force) and the eventual success (switching activation functions).

### 3. Conceptual Design (`LLM_Design_Proposal.ipynb`)
*Note: This section is the final capstone (Part 4).*
A proposal for the **"Socratic Sparring Partner."** Instead of an AI that answers questions (which risks causing cognitive atrophy), this is a design for an AI specifically programmed to challenge the user, acting as a Devil's Advocate to improve critical thinking.

---

## Critical Reflection on AI Assistance
I used AI tools (like Copilot and LLMs) throughout this project, not just to write code, but as a "dialogue partner" to bounce ideas off. It was a double-edged sword: sometimes a brilliant translator, other times a complete liability.

### The Pros
* My biggest hurdle was bridging the gap between my abstract Humanities ideas and rigid Python logic. The AI was great here. I could feed it a messy "brain dump" of non-linear thoughts, and it would translate that into structured code. It removed the barrier of syntax (brackets and indentation), allowing me to focus on the actual logic of the argument.
* It was an excellent sounding board for metaphors. For example, I came up with the idea of comparing data diversity to an **"Immune System"** - arguing that if a system is only exposed to one input, it becomes fragile. The AI didn't create that idea, but it immediately understood it and helped me map it to the technical concepts of *Domain Shift* and *Generalization*. It provided the technical scaffolding to support my creative spark.
* It acted as a ruthless editor. It helped organize my stream-of-consciousness notes on social implications (like the CalMac Ferries or Sanitization) into coherent themes without deleting my specific voice or examples.

### The Cons
* The most frustrating part was when the AI hallucinated that code was working when it wasn't. When I flagged an error, it would often "gaslight" me - insisting the code was correct and telling me to check my laptop settings or reinstall software. After wasting hours chasing these ghosts, I’d usually find out the error was just a simple typo the AI had missed. It reminded me that AI cares about *plausibility*, not truth.
* The AI constantly forgot who the audience was. It defaulted to "Computer Science" best practices, trying to make every line of code as short and efficient as possible. But my goal was *education*, not speed. I had to constantly fight it to keep my verbose variable names (like `archive_box` instead of `x`) so that a Historian could actually read and understand the work.
* It struggled to be a critic. If I suggested a bad idea, it would often prioritize being "helpful" over being "right," generating code for a flawed approach rather than warning me it wouldn't work. It reinforced that I couldn't autopilot; without human oversight, it would have happily led the project off a cliff.

### Workarounds & Takeaways
To mitigate these limitations, I found a few strategies that helped keep the tool useful.

* I found that if I accused the AI of being wrong, it often got defensive or stubborn. It worked much better if I explained *why* I thought it was wrong and asked it some reflective questions; same as a human. If it got stuck in a loop, I learned to force a "break." I would change the topic entirely - asking it about the Arsenal game, the health benefits of fermented foods, or the origins of Halloween. When I returned to the code or the conversation after this "reset," it was often more responsive and open to new ideas - again probably the same as a human.
* When the AI blamed my laptop settings or gave me a solution I didn't trust, I stopped arguing with that specific chat. Instead, I would open 2 or 3 separate chats, ask them the same question, and ask them to "rank solutions by likelihood." It is energy inefficient and takes longer upfront, but it acts as a necessary "peer review" for the machine, preventing me from rabbit-holing down a wrong path.
* Using speech-to-text for "Brain Dumps" was excellent for creativity, but I noticed a flaw in how the AI listens. It tends to weight every idea equally. I might speak 2 sentences about a minor side-thought and 10 sentences about a central idea, and the AI would treat them as equally valid. I learned I had to be very explicit about which points were the "Core" and which were "Fluff," otherwise it wouldn't prioritise.
* The AI had a default "positivity bias" that was genuinely annoying. It would often compliment a flawed idea just to be helpful. I found that I had to explicitly tell it to be "harsh," "persnickety," or to "play Devil's Advocate." Once I gave it permission to be critical, the feedback became much more useful.
* Finally, a warning for future practice: AI is a massive distraction risk. When working with a human, the back-and-forth is natural. With AI, the slight delay in generating a reply - or the frustration of having to argue with it - often broke my flow. I found myself checking my phone or losing concentration during these micro-pauses. In the future, I will be more cautious about using it during deep-focus blocks, as the wee distractions add up to a lot of time wasted.