A list of project ideas I might want to work on in the future. I keep finding that the ideas I have have either already been built 10 years ago or are currently being built by the thousands of AI startups around the world. As such, maybe half of these ideas are outdated, but I like keeping them around anyway. Consider it an exercise in [noticing ideas/opportunities](https://www.paulgraham.com/startupideas.html).

# Small Project Ideas
## Natural Language SQL
Build a system where users can ask questions in natural language and get SQL queries + visualizations. User asks query, agent generates SQL, executes it, returns results + chart.

## Personal Wiki (with Obsidian)
Sync email, whatsapp, social media. Give AI agents maximum context. Inspired by Andrej Karpathy's idea: <https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f>

## Agent Swarm statistical simulations
Prev won SDx hackathon by doing agent swam simulation on news headlines in relation to stock market behavior/reactions. Might be fun to explore this further. Also read: <https://arxiv.org/pdf/2509.13588>

## Robot tour guide
Prev won hackathon by building a [park ranger tour guide mini-robot](https://devpost.com/software/roboranger). Might be fun to explore a more advanced version of this that could can self-navigate to give you a flexibly, dynamic, end-to-end tour guide of places. I'd need an EE/MechE to help me tho. 

## Immersive Audio Book Generator
Accessibility of books for the blind and other disabled. But creating audio books takes $$$, you have to find, hire voice actors and then they need a lot of time to narrate an entire book, often needing multiple takes and stitching together takes.
And if your book isn’t popular? Forget it. Not enough demand to warrant making an audio book for it.
Solution: Using https://elevenlabs.io, our tool allows you to:
- Input a book
- "Manager" AI agent extracts:Characters and their personalities, Mood of each part of the book, Overall tone of the book for the narrator
- "Manager" assigns each character a voice that suits their personality, and can even assign music to each part of the book according to the scene's mood.
- Automatically generate a fully immersive audio book with the perfect narrator, perfect voices for each character, and even immersive music

## AutoDub/Sub
Use Text-to-Speech and Automatic Speech Recognition models to automatically sub and/or dub any anime/movie/TV show. 

## Camera Guide for Blind People:
A camera that can guide blind people. Reads books out loud for you, read any text, like in a museum. Identify any object. Gives instructions. When you open your fridge, you can say “hey, where’s my celsius?” and hold out your hand in front of the camera, and it will guide your hand towards it. Turn vision -> sound. Integrate with your laptop.

## Air guitar/Air piano/Air any instrument
ML Visual model that recognizes hand movement and gestures. Output sound based on hand movement.
If deployed on arduino, now you have a portable piano/guitar/anything the size of a power bank.
If deployed on desktop, visualize the instrument on the webcam and make a rythm game!

## LLM-based receipt scanner
Sees date, prices, items, can categorize by item. SQLite db of purchase history. Dashboard of purchases.

# Startup Ideas
## LLM-driven human experiments
There is a broader problem in trying to instill human cognitive biases into LLMs. If we can make LLMs think more like humans, with all their biases and diverse personalities and lived experiences, there is massive potential in being able to do social experiments and simulations without the massive cost and effort of getting actual humans in the study. Behavioral economics, industry focus study groups, social experiments, could all theoretically be done cheaper and faster if we could make LLMs actually think and behave like humans.  
More ambitious: imagine if we can make an AI version of everyone (maybe by fine-tuning over all their data?). Recommender systems basically try to model user preferences. But if I have an accurate AI copy of a user right in front of me, I could do my recsys experiments on them directly, making a scarily powerful recommender system. Though honestly, it's probably more realistic to just train some neural network to predict user clicks than using it to model the user's whole life experience and biases.  
Academic reading:
- https://en.wikipedia.org/wiki/Agent-based_model
- https://arxiv.org/pdf/2509.13588

## Piazza AI Agent
- Problem: I work as a tutor and a lot of questions on Piazza can honestly be answered via an AI agent
- No, not just simple questions that can be answered by reading the syllabus
- Say one of the questions is vague and a student is asking how to interpret it (happens a lot in programming assignments). An AI agent can see the answer key, see the question, and then give the correct interpretation of the question in Piazza. This is already what I do as a tutor, and I just really want to automate myself out of the loop.

## IoT end-to-end/full-stack analytics/ML for aquaculture
- The top shrimp exporters are India, Vietnam, Thailand, Indonesia, China. Other than China, shrimp farms are probably still quite traditional/primitive with minimal tech adoption. There might be some potential to build a tech startup that sells to these shrimp farms to help make their production more efficient.
- I have a friend who is a fisheries major in Indonesia. I might be able to ask him for insight into what kind of tech tools the fisheries industry needs and just build it for them.
- This used to exist: https://www.instagram.com/efishery/. But the company is collapsing and their CEO got imprisoned for fraud.

## IoT end-to-end/full-stack analytics/ML for Indo Factories (Making smart factories)
- ML for fault detection, predict when a machine is about to fail, computer vision for quality control, predict demand, detect safety concerns. Deploy ML everywhere on the factory floor
- Set up sensors to collect data. Dashboards to visualize. Deploy ML on edge devices.

## AI In-Person notetaker
- Most AI notetakers are for online meetings (like in Zoom)
- Opportunity to create a small device that listens and summarizes meetings. Could be an app on your phone
- Expansion ideas: classroom notetaking, phone calls, IRL conversations, being able to ask specific natural language questions about the meeting and get immediate answers.
- Nvm already exists and is overcrowded. https://www.bluedothq.com

## Fine-tuned AI Tutor (ChatGPT sucks)
- A personal, digital tutor for every individual student (https://www.youtube.com/watch?v=7vsCAM17O-M)
- Problem: AI tutors are a cool idea. But rn ChatGPT kinda sucks at teaching. When you ask it a question, it assumes some pre-requisite knowledge, chunks its explanations to sub-sections, over-summarizes. But true learning (like from a teacher) usually involves building foundational understanding. It requires clear chain of thought (instead of sub-sections), and in-depth explanations (no summarizing).
- Solution: an LLM specially trained to give those in-depth lectures to you.
- I suspect this area is overcrowded by now though.

## Myworkday for Indo
- Problem: applying to jobs in Indo sucks. Some of them have custom forms (which have bad performance), some you have to email, some don't even post online.
- Solution: myworkday but for Indo. Myworkday sucks too but at least it's standardized and the performance is good.

## Essay AI Checker
- Problem: cheating is rampant with AI. Especially writing essays.
- Solution: You know how google docs has a function where you can see writing history?
- Professors/teachers assign essays on our own platform. The platform is just a simple document editor but it tracks writing history, typing patterns, etc. and tells professors if it was written by AI or not.
  - Better than using AI checkers like GPTZero cuz some students writing styles could be similar to AI
  - "Couldn't students still ask ChatGPT to write it for them and then just copy-type it one by one?" Sure but it will detect if you're pausing and revising and stuff like a human. It'd require so much more effort to cheat the system that at that point just write the essay yourself bro.
  - Don't wanna trust our ML model? That's fine. You can see the writing history yourself as a video. To reduce overhead cost, only record when students are typing
  
## Sports court booking software
- Could be B2B (we provide the software for court owners) or B2C like Ebay for court booking (owners list on our site, customers book through our site). I assume this already exists and is a crowded market though.

## RateMyProfessor for Indonesia
- Apparently doesnt exist yet at all
- Could scale to making reddit for Indo unis
- This really only works if Indonesia becomes less culturally traditional. I hear profs are a lot more...arrogant there and could have power to ban/take it down/hold student grades hostage if their ratings are bad.

## Digitize how retailers buy produce from Indonesian farmers
- Vague idea. Idk how this industry works at all.
  
## Any other B2B
- Think about an industry that can be made more efficient with technology.
- Build the technology.
