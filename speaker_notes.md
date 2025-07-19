Speaking Notes for "Leverage AI Tools to Accelerate Learning in Data Science"

Slide 1: Title Slide
"Good morning, everyone, and welcome. Thank you so much for being here. My name is Matt Hamilton, and today we're going to talk about how you can leverage AI tools to accelerate your learning in data science and, more importantly, how you can become a creator of this technology, not just a consumer.
Throughout this session, we're going to challenge the idea that all meaningful AI innovation happens in places like Silicon Valley. We're going to prove that it can, and is, happening right here.
Before we dive in, you'll see QR codes throughout the presentation. The first one will link you to all the resources, code samples, and links we'll discuss today, so feel free to scan it anytime."
[CLICK]

Slide 2: My Journey
"So, who am I? My journey has been a winding one through the tech world—from CompSci at university to big names like IBM and now co-founding my own venture, the ASIMOV Protocol.
But the most important part of my story for today's talk is that in 2020, during the pandemic, I moved to Barbados on the Welcome Stamp. For the last few years, I've been building global-scale blockchain and AI systems from right here on the island. My mornings might involve paddleboarding with my dogs, but my afternoons are spent building technology used around the world.
And of course, I've been fully embracing the culture—wukkin up, with my concrete waistline trying to keep up! This experience has shown me firsthand that world-class innovation is not tied to a physical location anymore."
[CLICK]

Slide 3: Today's Plan
"Here’s a quick look at our plan for the next two hours. We’ll start with some crucial Context about the global AI landscape. Then we’ll get concrete with Real Projects being built from Barbados. We’ll look at the AI Tools you can use right now, and then you’ll get your hands dirty with a live Prompting Challenge. After that, we’ll dive into a key concept called Context Engineering, round out your AI Toolkit, and finish by talking about Careers & Next Steps so you can leave here ready to build."
[CLICK]

Slide 4: From Sugar Cane to Source Code
"Barbados has a long history of exporting valuable goods to the world: sugar cane, world-class tourism, and of course, our incredible culture. But the question we need to ask is: what else can we export?
The answer is intelligence. AI is the great equalizer. In the past, to compete globally, you needed steel mills, factories, massive industrial infrastructure. Now? All you really need is a laptop and an internet connection. You can build tools that the entire world uses, from right here."
[CLICK]

Slide 5: The Context (Kate Kallot)
"To set the stage, I want to share something that deeply inspired me. This is Kate Kallot, the CEO of an African AI company called Amini, which is actually working with GovTech right here in Barbados.
At the AI For Good Summit just last week, she laid out the problem and the opportunity perfectly. She pointed out that the vast majority of AI's power—the data centers, the computing—is concentrated in just a couple of countries. She argues that the risk of the Global South, including the Caribbean, being left behind isn't an accident. It's happening by design.I’ve had similar conversations with Dennis Augustine, in which he describes it as a kind of “digital colonialism”. 

But here’s where her message gets powerful. She says this isn't a story of weakness. It's a story of our hidden superpower, what she calls Constraint-Driven Creativity. When you don't have unlimited resources, you're forced to be more creative, more efficient, and to solve real, urgent problems.
As she says, and as you see on the screen, 'The AI revolution is not being written in Silicon Valley... it's coming from Manila, from Bridgetown, from Nairobi.' This is our moment."
[CLICK]

Slide 6: The AI Revolution
"Let's make that concrete. Less than 1% of the world's data centers are in Africa, and as of now, there are no large-scale commercial data centers in Barbados.

This is a constraint. But as Kate Kallot argues, that constraint forces innovation. It forces us to build smarter, more efficient systems.
And critically, our local context creates better AI. The unique problems we face here—in tourism, in climate, in logistics—are opportunities to build unique solutions that no one in a San Francisco high-rise would even think of."
[CLICK]

Slide 7: The Great Shift
"This is what I call The Great Shift. Then: you needed massive capital and physical infrastructure like steel mills and factories. Now: you need a laptop, access to a Large Language Model, and most importantly, curiosity.

Global competition has been fundamentally democratized. The barrier to entry has never been lower."
[CLICK]

Slide 8: Workshop Goals
"So, what do I want you to leave with today? Four things:
1. To see yourselves as creators of AI, not just consumers.
2. To learn some real-world prompting skills you can apply immediately.
3. To embrace the mindset of building smarter, not just bigger.
4. And to feel empowered to solve local problems that have global relevance."
[CLICK]

Slide 9: Real Projects from Barbados
"Alright, that's the context. Now for the proof. Let's look at some real AI projects that have been built right here, proving that this isn't just a dream—it's already happening."
[CLICK]

Slides 10, 11, 12: WeOutside246.com & LLM Data Extraction
"First up, WeOutside246.
* The Problem: Anyone who lives here knows it—finding out what's happening is a mess. Events are scattered across dozens of Instagram stories, flyers, and captions written in Bajan dialect. It's chaotic.
* The Solution: An AI that automatically scrapes Instagram, understands the slang, and structures all that messy data into a clean, searchable event calendar.
* How it works: We use LLMs like those from OpenAI, combined with Python and a scraping tool called Apify. The system runs automatically on Google Cloud.
* As you can see from this extraction example, it takes a messy caption and turns it into structured JSON data—identifying artists, location, date, and event type with a confidence score. This is a perfect example of using AI to solve a uniquely local problem."
[CLICK TO NEXT SLIDE IN SECTION]

Slides 13 & 14: YuhHearDem & Knowledge Graph Visualization
"Next, YuhHearDem.
* The Problem: Parliamentary transcripts, the Hansards, are incredibly important for transparency, but they are thousands of pages long and completely unsearchable. How can a regular citizen keep up?
* The Solution: An AI pipeline that ingests these long documents and turns them into a structured, searchable knowledge graph.
* How it works: We use Google's Gemini model, LangChain for orchestration, and a MongoDB database. It segments topics, identifies who said what, and links everything together.
* Now, you can simply ask a question like, 'What has been discussed about innovation?' and get a direct answer with links to the source. This is about making civic engagement accessible. As you can see from the graph, it connects people, topics, and specific discussions in a way a simple document never could."
[CLICK TO NEXT SLIDE IN SECTION]

Slides 15 & 17: ASIMOV Protocol & Positron
"These local projects led to a global one: ASIMOV Protocol.
* The Problem: LLMs are brilliant but they hallucinate—they make things up—and they have no reliable memory.
* The Solution: We're building a system of knowledge graphs that provide verifiable, trusted memory for AI. It turns chaotic information into structured reasoning. It's a global team, with key development happening right here in Barbados.
This same technology powers a personal tool I built called Positron.
* The Problem: We all have notes, documents, and ideas scattered everywhere.
* The Solution: Positron acts as your 'second brain,' connecting all your personal knowledge. You can upload all your documents and then ask smart, cross-topic questions like, 'Who do I know in Barbados who works in AI?' and it will find the answer by reasoning across all your information."
[CLICK]

Slide 18: Core Patterns
"So what do all these projects have in common? Four core patterns:
1. Structured data is more powerful than clever prompts. Giving the AI clean, organized information is the secret to getting great results.
2. They all solve real, tangible problems. They're not just tech demos.
3. Local context provides an innovation edge. These ideas came from living here and seeing a need.
4. And finally, they prove that constraints drive creativity. Limited access to massive datasets forced us to be smarter about how we structure and use the data we have."
[CLICK]

Slides 19-22: Prompting Skills
"Let's get practical. The most basic way to interact with an AI is through prompting. But the key is to talk to AI like an engineer, not just a user.

A good prompt is specific, it tells the AI the format you want, it often uses examples, and you should plan to refine it iteratively. A pro tip: you can even ask the LLM to help you write a better prompt! For example, instead of just 'summarize this,' try 'Summarise this for a teenager from Barbados in 3 bullet points with 1 quote.'

You can see the evolution here. 'Explain machine learning' is a terrible prompt. 'Explain it to a 16-year-old in Barbados with a mango analogy' is much better. Adding constraints like 'Keep it under 150 words. Use bullets' makes it even stronger.

This final example shows a production-level prompt from the WeOutside project. You can see how it defines the task, gives specific keywords and location indicators to look for, and most importantly, demands the output in a clean JSON format. This is how you get reliable, repeatable results from an AI."
[CLICK TO NEXT SLIDE IN SECTION]

Slides 23-26: Prompting Challenge
"Okay, now it's your turn. We're going to do a live prompting challenge.
The task is to clean a messy dataset. You'll see mixed date formats, inconsistent phone numbers, location variations—all the stuff you find in the real world. Your goal is to write the single best prompt you can to get an AI to clean it all up perfectly.

Here are the rules: You have 30 minutes. You can make unlimited submissions. We'll be using Gemini 2.5 Pro to automatically score your prompt's output based on formatting, completeness, and accuracy. The best score wins!

Head over to bit.ly/bim-ai-workshop to get started. Let's see what you've got!"
[START 30-MINUTE TIMER, WALK AROUND AND ASSIST]

Slides 27-32: Context Engineering
"Great job on the challenge! Now let's level up from just prompting. Let's talk about Context Engineering.

Here’s the key idea: 'Prompting is what you say — context is what the model knows when you say it.'
Context Engineering is how we design, structure, and deliver the right information to the model at the right time. This is how we reduce hallucinations, handle long documents, and get truly personalized outputs.

Why does it matter? Because by default, LLMs have a messy 'knowledge soup' from their training data. They can't reason about information they haven't seen or can't access. If your context is messy or outdated, you get bad results. If it's clean, focused, and structured, you get great results.

Basic methods include pasting a doc into the prompt or using few-shot examples. But advanced tools like RAG (Retrieval-Augmented Generation) and Knowledge Graphs are where the real power is.
A new standard called the Model Context Protocol (MCP), built by the team at Anthropic, is emerging to handle this. Think of it as 'RAM for AI'—a structured, shared memory that makes AI inputs reliable and traceable. This is what enables powerful applications like learning agents and the civic transparency tools we saw earlier."

Interactive bit: ask audience about who can bake a cake. Ask how many grams of flour needed in a Black Forest gateaux? Then ask them how they’d find out. Then pass cookbook to them to look it up.

Talk about how this is how LLMs and RAG work (and what ASIMOV is doing in pulling encyclopaedic knowledge out of the “knowledge soup”.)

[CLICK TO NEXT SLIDE IN SECTION]

Slides 33-38: The AI Toolkit
"Let's quickly cover the essential tools in your AI toolkit—what's available to build with today.
* LLMs: You have options like ChatGPT, Claude, and Gemini. ChatGPT is fast and general. Claude is great for long documents and code. Gemini is multimodal, meaning it excels with tables and images. The tip is to pick the right tool for the right job.
* Coding Agents: Tools like Claude Code, Cursor, and Bolt are like AI pair programmers. They can write, debug, and explain code, dramatically speeding up your workflow.
* Embeddings & Search: This is how you make AI understand your specific content. It converts text into numbers (vectors) so the AI can find related concepts, not just keywords. This is the core of RAG.
* Knowledge Graphs: This is about adding memory and structure. By linking facts, concepts, and people, you allow the AI to reason about relationships and provide much better, more reliable answers."
[CLICK TO NEXT SLIDE IN SECTION]

Slides 39-41: Careers & Action & Final Takeaways
"So, how do you build your future with AI from here? It starts with building your portfolio.
* Get 3-5 real projects on GitHub. Solve a problem you care about.
* Blog what you learn. Teaching is the best way to learn, and it shows your expertise.
* Join online communities. The AI world is global and collaborative.
* And yes, you can work remotely from Bim for companies all over the world.
Let's wrap up with the final takeaways:
* Constraints are assets. They are your creative advantage.
* Local ideas can go global. The best solutions often start by solving a specific, local problem.
* You don't need permission from Silicon Valley to innovate.
* And most importantly, start building this week."
[CLICK]

Slide 42: Your Turn (Q&A)
"To bring it all back to Kate Kallot's powerful idea: 'The AI revolution is being written in Bridgetown.'
So the final question is for you. What will you build?
Thank you. I'd now like to open it up for questions, ideas, and discussion. Let's talk about what's next."
