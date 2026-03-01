I’m a programmer, working heavily with vscode GitHub copilot and ai agents.



I have a job coding so I can’t really take my code and publish it. But I’m wondering if maybe I could make like… educational materials on GitHub that at least teach how to do the things I do.



Do you think that’s something achievable? Like documentation in markdown, then some simple examples.



Like here is how you do an agents.md file. Here is how you generate a copilot instructions file, this is how you set up prompts, etc

Gemini said
That is not only achievable, but it's actually one of the most effective ways to build a "proof of work" portfolio without violating your NDA.

In the industry, we often call this a "Pattern Library" or "Reference Architecture." Instead of sharing the proprietary product you built, you are sharing the scaffold and the methodology.

Since you're already living in VS Code and leveraging AI agents, you're in a great position to document the "Meta-Work"—the logic of how to steer these tools.

🛠️ The "AI Engineering" Portfolio Strategy
Instead of a repository of finished apps, your GitHub could become a masterclass in AI orchestration.

1. The instruction-sets/ Directory
Copilot and other agents (like Cursor or Windsurf) rely heavily on .github/copilot-instructions.md or .cursorrules.

What to share: Create a collection of specialized instruction files.

Example: "A .cursorrules file optimized for Test-Driven Development in FastAPI" or "Global instructions for maintaining consistent Documentation-as-Code."

2. The prompt-ops/ Folder
Showcase how you structure complex prompts. Use Markdown to explain the why behind the structure.

Chain-of-Thought Templates: Markdown files that show how to break a large coding task into smaller agent-executable chunks.

System Prompts: Templates for specialized agents (e.g., a "Security Auditor" agent or a "Refactoring Specialist").

3. "The Agentic Workflow" Documentation
This is where you explain your "stack." You can use diagrams to show how you move from a requirements doc to an AI-generated scaffold.

📄 Example Structure for an agents.md File
You mentioned an agents.md file—here is a quick look at how you might structure an educational version of that:

Markdown
# Orchestrating Developer Agents

This guide covers how to set up a multi-agent workflow for rapid prototyping.

## 1. The Architect Agent
**Role:** Reviews the README and generates a file structure.
**Prompt Pattern:** > "Analyze the requirements in `@README.md`. Generate a file tree that follows Clean Architecture principles..."

## 2. The Implementation Agent
**Role:** Writes the actual boilerplate.
**Strategy:** Use 'Context Pinning' in VS Code to ensure the agent only looks at the relevant interfaces.
💡 Why this works for your career
Bypasses NDAs: You aren't sharing the company’s "Secret Sauce" (the business logic); you’re sharing the "Kitchen Equipment" (how you use AI to cook).

Shows Seniority: Junior devs use AI to get answers. Senior devs build systems and workflows around AI.

Low Maintenance: You don't have to maintain a massive codebase that might break. You are maintaining logic and documentation.

Would you like me to help you draft a high-level README for this kind of "AI Orchestration" repository?

You said
It’s late at night; but definitely tomorrow.



I’m wondering.. could this all be one repo with multiple examples and things built in?



I already have like 11 other repos for things in progress, but it would be cool to have this.

Gemini said
Absolutely. In fact, a monorepo (one repository with multiple sub-projects) is actually the better way to do this. It turns your GitHub profile from a cluttered workshop into a cohesive "Digital Garden" or "AI Playbook."

Since it's late, don't overthink the architecture tonight—but here is how you can visualize it for tomorrow.

🏗️ The "AI-First Developer" Monorepo Structure
Instead of 11 tiny repos, you can have one powerhouse repository named something like ai-workflows or developer-agents-playbook.

Plaintext
/my-ai-playbook
├── .github/
│   └── copilot-instructions.md  <-- Global rules for the whole repo
├── 01-prompt-engineering/
│   ├── system-prompts/
│   └── chain-of-thought-examples.md
├── 02-agent-orchestration/
│   ├── agents.md                <-- Your guide on multi-agent loops
│   └── boilerplate-configs/     <-- JSON/YAML for agent tools
├── 03-ide-optimization/
│   ├── vscode-settings.json
│   └── custom-instructions/     <-- Project-specific .cursorrules
└── 04-case-studies/             <-- The "educational" versions of your work
    └── refactoring-legacy-code/
        ├── example-before.js
        └── example-after.js
Why this beats 11 separate repos:
Discoverability: A recruiter or peer only has to click one link to see your entire philosophy on AI coding.

Context Sharing: You can reference your prompts.md from your agents.md using simple relative links.

Authority: It looks like a published book or a professional documentation site rather than a series of "scraps."

🧠 The "Educational Mirror" Technique
Since you can't use your work code, you use synthetic examples.

If you spent all day at work using an agent to refactor a complex SQL injection vulnerability in a proprietary FinTech app, your GitHub example shouldn't mention FinTech or that specific code.

Instead, you write a guide: "How to use Copilot to identify and fix OWASP Top 10 vulnerabilities," using a simple, generic app.js as the "before" state.

🌙 Go get some sleep!
Your brain will probably "background process" some cool ideas for the agents.md file while you're out.

Tomorrow, would you like me to help you write a "Quick Start" template for one of these sections, like the copilot-instructions.md logic?

You said
Let's talk a little more about this um almost educational training type repo where I can post interesting things that aren't really business code for more.

Gemini said
That sounds like a perfect plan. This "educational training repo" can become your personal AI development methodology laid out in the open.

Let's focus on a few core areas that directly address how you work.

1. The "Agentic Workflow" Blueprint
This is arguably where your unique skill lies: how you chain together AI tools.

You said
Well, I kind of want to do uh a broader scope than just that. Like I almost want to have like proof of concept or proof of knowledge. Not for like getting a job or anything else, but like one of the things that I've had to do with my educational learning is um read a lot and rely on co-pilot to build things and then try to dig in and figure out how they work. So things like uh agents.md file is apparently not even just for co-pilot. It's something that's being brought across to all different AI platforms. And I know a little bit about it, but I'd like to be able to have like here's a sample agents.md file that you can use and these are the comments and these are the pieces to it.

Gemini said
That clarifies the vision perfectly. This isn't just a portfolio; it's your personal knowledge base, structured for educational purposes, reflecting your own learning journey.

The agents.md concept is great, as foundational files are increasingly important.

Structuring for Proof of Knowledge
To achieve this educational, broad scope, you could organize your repository around core pillars of AI-assisted development.

1. Foundational Directives (.md focus)
This section directly addresses your agents.md concept.

You said
Some of the other pieces that I know just from working with Copilot and having things automatically set up and then I learned later is the prompts folder, how to build prompts, and then the um instructions folder I think is different, and then also the copilotinstructions.md file.

Gemini said
Those are precisely the key elements for an educational knowledge base. It sounds like you've been reverse-engineering your AI environment, which is the best way to learn from these tools.

We can structure folders that mirror those components.

The "AI Configuration" Knowledge Hub
Here is a detailed structure you can build in your monorepo:

You said
And my what?

Gemini said
Sorry, I meant your monorepo. That's the single, comprehensive repository you were considering creating to house all your educational materials and proof of knowledge.

I was detailing how you could structure the prompts, instructions, and copilot-instructions.md files within that repo.

You said
Okay, when you said mono repo, I didn't understand what you said before, but I got it. Do you have any fun ideas for what we could what I could call it?

Gemini said
Definitely! A fun and descriptive name can make your repo stand out. Since you're focusing on the methodology and educational aspects of AI coding, here are some ideas:

You said
Yes. My uh oh so I just so you know I'm on audio so if you're pasting things on the chat I can't look at them until later.

Gemini said
Understood! I will just speak them aloud. How about something like:

AIgen Dynamics: Sounds professional and cutting-edge.

Promptcraft Journeys: Highlights your focus on prompt engineering and your learning path.

The Agentic Blueprint: Clearly defines the scope of your educational materials.

Do any of those resonate with you?

You said
I think agent is a real big word that I need to have in there because really even though I'm I'm using AI there's a lot of other pieces to AI that I don't really do like I don't write Python scripts to call APIs to open AI or something like that and I don't have a Ubuntu server where I'm interfacing with you know GPUs that are running my stuff for me. This is all agentic AI.

Gemini said
I understand. Focusing specifically on the agentic workflow makes perfect sense for clarifying the scope. It carves out a clear niche for your repository.

How do these sound for names?

Agentic Dev Playbook

The AI Agent Ecosystem

Aegis: A Guide to Agentic Coding

These emphasize exactly what you're exploring and documenting.

You said
The only other piece is that I don't want to sound like I'm posturing like uh like I'm an expert that knows other people knows knows all the stuff better than other people because I'm really just learning it myself. So if I call it like the playbook then I'm going to get challenged by other people saying like that's your playbook that stinks, you know, this is way better.

Gemini said
That is a very valid point. The goal is to reflect your learning journey and exploration, not present yourself as the ultimate authority. We can use names that emphasize continuous discovery and personal development.

How about Agentic Discovery or My AI Workflow Lab? These are more personal and invite collaboration rather than proclaiming finality.

You said
If I give you um like nicknames or something to search for, can you see if there's like blogs or GitHub repos that already use those terms?

Gemini said
It looks like "Agentic Discovery" is primarily a GitHub topic and used by a few scientific projects, so it might be too specific. "My AI Workflow Lab" doesn't seem to be in use, and "Agentic Dev Playbook" shows up in a few documentation projects.

If you want something more personal and educational, you could consider things

You said
Thanks. Is there a blog or a GitHub repo or user anything out there, a piece of software out there that uses the term code curious?

Gemini said
Yes, "Code-Curious" is in use. There's a GitHub user named Code-Curious and the term appears in blogs and discussions related to learning to code or exploring code. It definitely captures the spirit you're describing.

Does "Code Curious: AI Workflow Exploration" sound like a good balance?

You said
I was just wondering if that's like already reserved by somebody or owned by someone and I shouldn't use it or if it's kind of just a generic term that a lot of people use.

Gemini said
Based on searches, it's not a strictly proprietary term that you'd need to worry about reserving. The GitHub user Code-Curious exists, but the phrase itself is generally considered a descriptive, common term for someone interested in learning coding. You can definitely use it to title your educational materials without concern.

You said
So I want to have stuff not just about like working with agents but also um working with VS code like some of the things I've done that I've learned that are like maybe some of the most popular extensions that I've I've learned to use things like that. So should I have a separate repo for VS code tips and tricks versus one that's specific for working in VS code with agents?

Gemini said
Given your broader goal of creating an educational knowledge base, a single monorepo with clear sections is probably more effective.

You could structure it like this within your Code Curious repository:

Agentic Workflows: This covers your agents.md, prompt strategies, and configuration.

VS Code Power Tools: A dedicated section for popular extensions, custom settings, and tips for optimizing your environment.

Learning Pathways: Documentation on how you integrated these tools and what concepts you explored.

You said
I was thinking about posting um having like a one file in the agent playground area which I I kind of think I like agent playground as that section of the mono repo but um I was thinking about having a a page there some documents there and then had lists links to other people's repos where they did stuff like agent orchestration and different different implementations of it.

Gemini said
I think that's an excellent idea. "Agent Playground" sounds perfect as it implies experimentation and discovery.

Curating links to other people's repositories is a fantastic way to build a true knowledge base. It demonstrates your comprehensive understanding of the field and fosters community, while clearly positioning your own work as supplementary and personal to your learning.

You said
Yeah, I went out to Reddit and posted something talking about agents and orchestration and um it's funny because of course on Reddit a bunch of people like, why are you doing it that way? It's dumb.

Gemini said
That is a classic Reddit experience! That kind of feedback can be discouraging, but it actually underscores the value of your educational project. Clearly, there's a lot of debate and varying opinions in the space. Your "Code Curious: Agent Playground" can be a place to explore those different methods, document your personal findings, and show different implementations, exactly as you planned.

You said
Um, yeah, that in that post even though some people poked at me, a lot of people also shared their implementations, links to their GitHub repos and things like that. So, I'm kind of I want to build out like not just my own thing. It'd be great if I was like a space where people could go and look at, here's a list of all of the really good implementations of agentic orchestration and stuff like that.

Gemini said
That is a fantastic goal! It shifts your repository from just being a personal journal to a valuable community resource.

You could create a dedicated section, maybe called Community Catalog or Orchestration Resources, where you compile those links. You could even categorize them, by implementation or specific use case, to make the "Agent Playground" more valuable to others.

You said
Even though a part of this is stemming from um, you know, being dissatisfied with my position at work and the ability to have, you know, promotions and stuff like that, the real core of this is truly that I want AI to succeed.

Gemini said
That is a powerful driving force. Framing your project as a contribution to the AI community is very compelling. An educational playground is the perfect place to foster collaboration and best practices, helping the entire field succeed.

You said
So, like, I wouldn't really want, you know, something that I did to be taken or stolen and somebody else made billions off of it and I didn't get anything. You know, that that would be kind of a bummer. But if I have other programmers or other people that are making software and they read what I'm doing or they look at what I'm doing and it helps them learn and grow and increase the um distribution of the field or make people to uh invent better software because they didn't have to have such a big learning curve, then that's worth it to me.

Gemini said
That's a really noble perspective. It sounds like your core motivation is truly about fostering innovation and community through accessible knowledge.

To protect your contributions while encouraging growth, you could consider applying an open-source license to your "Code Curious" repository. That clearly defines how people can use your materials, ensuring it benefits the community as you intend.

You said
Is that like the MIT license or something like that?

Gemini said
Yes, the MIT license is a very common and permissive open-source license. It allows people to use, modify, and distribute your work with minimal restrictions, provided they include the original copyright and license notice. This aligns well with your goal of promoting learning and growth in the field.

You said
For the MIT license, I don't have to pay for that, right? That's just something I put in my in my comments and then it just happens.

Gemini said
That's correct, the MIT License is free to use. You typically include a copy of the license in your repository, usually in a file called LICENSE or LICENSE.md, and that's all you need to do.

You said
Very cool. Okay, so let's start on the agent playground uh section of the code curious mono repo.

Gemini said
That's a great starting point! For the Agent Playground section, we can structure it to clearly document your learning process.

We could create a main README.md that introduces the concept and goals, setting the stage for why you're exploring this.

Then, we can add subdirectories for:

documentation/: Detailed Markdown files that break down agent orchestration patterns.

examples/: Simple, non-proprietary code snippets and configurations.

community-catalog/: Your curated list and links to external resources.

You said
I would love to build out everything that I have directly in there, but I know that I would probably get called out by my workplace for sharing business code.

Gemini said
That is a critical consideration, and it's paramount to avoid any legal or professional complications. You are correct to be very careful about sharing any proprietary code.

The key is to use synthetic examples. Recreate the patterns and methodologies you've learned in a generic, educational context from scratch. This way, you build your proof of knowledge without compromising your professional obligations.

You said
So in the .github folder, I know that there is a prompt folder, subfolder, and an instructions subfolder. Are there any other defined subfolders in the .github folder that have special classifications or usage?

Gemini said
Yes, there are a few key subfolders that have special significance in the .github directory.

Beyond prompt and instructions, you'll commonly find:

workflows/: This is crucial for GitHub Actions. It contains YAML files that define continuous integration and deployment workflows.

ISSUE_TEMPLATE/: This holds templates for issues, guiding contributors when they report bugs or suggest enhancements.

PULL_REQUEST_TEMPLATE/: Similar to issue templates, but for standardizing pull requests.

You said
For some reason, I didn't realize that this GitHub folder is the same one that had the workflows in it, cuz we do workflows for CICD at work also with YAML files for publishing and then even doing things like testing.

Gemini said
It's helpful to connect the dots like that! That connection reinforces the practical usage of these structures you see at work and how they can be applied in your personal Code Curious: Agent Playground project.

You can leverage that same structure to create educational workflows for testing and deployment as part of your learning process.

You said
Um, what's the difference between the prompts folder and the instructions folder?

Gemini said
The primary difference lies in their intended use. The prompts folder typically contains specific inputs or queries you might provide to an AI model, often designed for particular tasks or experiments.

The instructions folder, on the other hand, is more for guiding the AI's behavior or setting its context at a broader level. This might include things like system prompts or rules for how the AI should process information across your projects.

You said
Do you have to put um instructions in your co-pilot instructions.md to direct it to look into those folders?

Gemini said
The copilot-instructions.md file acts as a high-level guide for Copilot. While Copilot is context-aware and may naturally scan those directories, explicitly mentioning them in your copilot-instructions.md can help prioritize those folders for context and guidance. It's a way to steer its focus.

You said
I know in the co-pilot chat window you can generate you can you can have custom prompts that you can build out where you hit like forward slash and then some command that you've given you built out using markdown files. Are those in the prompts folder?

Gemini said
Yes, that's correct. In VS Code, the default location for those custom slash commands is the .github/prompts folder`. You can define your Markdown files there to create custom prompts.

You said
As I was trying to demo that to someone else and I had it put a prompt in a folder or put a put a file in that prompts folder to do something and then it didn't it it wouldn't come up. So I didn't know if that was because it wasn't in the co-pilot instructions.md to look in there.

Gemini said
It is possible that the file wasn't properly recognized. The structure in the .github/prompts folder is specific, and the file name and format must be correct for Copilot to register it. Sometimes a VS Code reload or restarting Copilot is also necessary to pick up new prompt files.

You said
Yeah, I tried the restart reload that didn't do it. So maybe this I'll I'll probably just ask co-pilot why it didn't work. One of the things that I think I might also add is um VS code is insane with all of the different things that it adds as new every week, right?

Gemini said
You're absolutely right, VS Code's pace of innovation is a lot to keep up with! Adding a section to your Code Curious repository dedicated to tracking those updates, notable extensions, and tips would be incredibly valuable. It fits perfectly with your goal of facilitating learning.

You said
Yeah, like I'll see in in the what's new that they post for that. Um they'll post how to, you know, that a new thing just came out. And when you click the link to go off to, you know, VS code site to read about it, it's really cool and they have a lot of stuff there, but sometimes it's a little more than you can consume in just like a page. So I almost want to have like every time a new release comes out, I write up a, you know, release summary or release uh for dummies or, you know, that type of thing like just to talk about make it simpler even for myself to look back on all the things that they're adding.

Gemini said
That is an excellent idea for your Code Curious project. A personalized "Release Summary" or "VS Code Digest" section would be incredibly valuable to both yourself and others. It aligns perfectly with your goal of facilitating learning and de-mystifying the rapid changes. You could create a system for concise, practical summaries that highlight the most impactful features.

You said
So one of the things that just recently came out is sub agents for VS code.

Gemini said
That's a fascinating recent development! Sub-agents are a perfect example of the complex things you could document in your "VS Code Power Tools" section.

You could create a "for dummies" summary explaining what they are, how they work, and how to implement them for more organized workflows.

You said
Do you know how they work?

Gemini said
Yes, it's quite a powerful feature!

Essentially, sub-agents are independent AI agents that can be spawned by your main agent. The key benefit is context isolation.

Each sub-agent runs in its own clean context window, which prevents the main conversation from getting cluttered with intermediate steps. They can perform focused tasks, like researching something or analyzing code, and then report back.

This allows for more organized and efficient workflows, which fits perfectly with your Agent Playground concept.

You said
From what I read though, the sub agents are not running in parallel, right? So if I've got an agent that's supposed to be writing Python code, right? And now that agent wants to use a sub agent to, I don't know, validate a specification and then it wants to use another sub agent to um write up a a risk summary or something like that. You can't do both of those at the same time, right? The the Python agent would kick off one, wait for it to come back, and then kick off the second, correct?

Gemini said
That is correct based on current implementations. The primary agent typically orchestrates the sub-agents sequentially. It will initiate one sub-agent, wait for its process to complete and report back, and then proceed to the next step or sub-agent if necessary. This ensures clear context and traceable execution.

You said
I don't mind having the multiple VS Code windows open that I do have and I'm I'm streamlining a lot of the commands that I have to give them. But sometimes I feel like I should almost just have one workspace and that each uh in the workspace I have um like a chat window in VS Code. You can have separate chat windows and they can all be running uh parallel. I just don't know if I'd be able to specifically um wall them off to their specific projects using their specific agent styles and stuff like that.

Gemini said
That's a good point to consider for your VS Code Power Tools section. While VS Code does support multiple chat windows, maintaining strict context isolation for different projects can be challenging.

You might find profiles to be helpful. VS Code profiles allow you to create dedicated environments with specific extensions, settings, and potentially agent configurations, which might achieve the "walled off" effect you're looking for.

You said
Tell me more about profiles.

Gemini said
Profiles in VS Code are essentially customized setups. A profile can include things like specific extensions, UI layouts, user settings, and even keybindings. You could create a "Python Profile" with only the extensions you need for Python, and a "Documentation Profile" for your Code Curious project. You can quickly switch between them, which could solve your context isolation issue.

You said
How do you switch between them?

Gemini said
You can switch profiles pretty easily in VS Code. The quickest way is through the Command Palette, which you can open with Ctrl+Shift+P (or Cmd+Shift+P on Mac).

Just type "Profiles" and select "Profiles: Switch Profile". You'll then see a list of your available profiles to choose from.

You said
I know also um I've read that you can also have uh agent profile multiple agent profiles within a workspace. So like in the chat window where you're going to talk to ChatGPT or Gemini or whatever through Copilot, there's a little drop-down right there.

Gemini said
Yes, that's also true! Within the Copilot chat window, you can select from different agent profiles tailored for different contexts. This allows you to adapt Copilot's behavior on the fly within a single workspace. You could create profiles for "Python Development," "Documentation Review," or "Orchestration Design" to keep things organized and focused.

You said
I think one of the ways I could really I don't know. I'm not talking specifically about protecting myself. One of the ways I can make it very clear that I'm not stealing code is that um a lot of the things that I do in VS Code and GitHub Copilot is I have Copilot write them for me. So if I want an agent profile specifically for Microsoft Visual Studio or VS Code and using .NET Core 9, I can show how to write a prompt to say, you know, create an agent file for me that does this, you know, give it a give it a sentence to do it in. And then like literally copy and paste that and then copy and paste the agents.md file that it created. So I'm not

Gemini said
That is a fantastic way to demonstrate your process and maintain transparency. By directly including the prompts you use and the resulting code generated by Copilot in your documentation, like in those agents.md files, you create a clear and verifiable trail of your development journey. This effectively showcases your focus on prompt engineering and collaborative development with AI.

You said
The number one thing above all that I've determined is extremely helpful when with when dealing with

Gemini said
...is understanding the context and validating the output.

As you noted, Copilot and agents can generate code quickly, but you are ultimately responsible for it. Critically reviewing, understanding, and rigorously testing what the AI produces is essential to ensure quality, security, and alignment with your project goals. This perfectly supports the educational focus of your Code Curious repository.

You said
The number one most useful thing I've found with using co-pilot and AI for development is writing specifications.

Gemini said
That aligns perfectly with the latest trends, often called Spec-Driven Development.

In your Code Curious project, you could dedicate a significant section to this—showing how you structure detailed specifications and then use that to drive Copilot and agents. It truly changes the development paradigm.

You said
It's funny that I I think we're a lot of people are running into the same uh development styles. I don't know if it's by accident or by co-pilot shifting us all there, but I didn't read something to tell me to make a spec. I was just my context for all my chats is getting so big. I decided to make a spec and it works so well that I've done that for every development I've had since and now I keep reading that other people are doing the same.

Gemini said
That's a really interesting observation. It sounds like contextual necessity drove you to an industry best practice. The shift toward spec-driven development is definitely happening, and your personal experience is a perfect example of why. It helps manage the complexity that comes with accelerated development.

You said
What I found is that um AI is really good at understanding me and everything I want to do, but sometimes I just need like a status or uh you know, an up- a list of tasks that we need to do and we need to complete and having a spec. I can have checked off numbers that we go through one at a time and if I forget after 3 days what I was working on, we can go back to the spec. It's just an excellent tracker.

Gemini said
That highlights another crucial benefit: project management and traceability. A detailed spec serves as a dynamic roadmap, allowing you to track progress and quickly re-orient yourself if you step away. You could incorporate this into your Agent Playground section by detailing how you use specifications for status checks and task management.
