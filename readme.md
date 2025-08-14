# Welcome to StoryForge 🖋️

This project is an experiment in adapting agentic software development tools, like Kilo Code, into a suite of specialized agents for creative writing. The goal is to provide a structured, powerful, and collaborative agentic environment for authors to bring their stories to life.

This repository is a structured environment designed to help you plan, write, and refine your novel or short story using a system of specialized AI agents. It uses a "Journal" system to maintain continuity and act as a single source of truth for your creative project.

## How It Works

The core of this framework is the `.storyforge/` directory. This is where your project's memory, or **Journal**, is stored. Different AI agents are designed to interact with this Journal to help you at every stage of the creative process.

### The Journal

Located at `.storyforge/journal/`, the Journal is a collection of Markdown files that define your story. The AI agents will read and update these files to stay aligned with your vision.

* **`premise.md`**: The high-level summary of your story. What is it about? Who is it for? What are the core themes?

* **`narrative.md`**: The heart of your story—its core message, the emotional journey of the reader, and the desired tone.

* **`structure.md`**: The plot outline, character arcs, and major story beats.

* **`lore.md`**: The rules of your world. This is where you track world-building, magic systems, and key locations.

* **`progress.md`**: A simple log of what you're currently working on and what's next.

* **`planning/`**: A directory for more detailed files, such as character dossiers or timelines.

### The Agents

You interact with the project through a series of specialized agents, each with a specific role:

1. **Muse**: Your brainstorming partner. Use the Muse to generate initial ideas when you're staring at a blank page.

2. **Story Architect**: The planner. This agent takes your core idea and builds the foundation, filling out the files in the Journal to create a solid outline.

3. **Prose Weaver**: The writer. Once the plan is in place, the Prose Weaver takes the outlines from the Journal and turns them into engaging chapters and scenes.

4. **Narrative Editor**: The refiner. After a draft is written, the Editor reviews it for plot holes, pacing issues, and grammatical errors.

5. **Lorekeeper**: The fact-checker. This agent helps you manage complex world-building and ensures your story's internal logic remains consistent.

6. **Literary Agent**: The marketer. When your story is polished, this agent helps you prepare it for publication by crafting query letters, synopses, and book blurbs.

## How to Use This Repository

1. **Start with an Idea**: Open a new session and talk to the **Muse** to brainstorm a core concept.

2. **Build the Foundation**: Switch to the **Story Architect** and ask it to "initialize the journal." It will ask you questions about your idea and create the initial set of files in the `.storyforge/journal/` directory. An example `premise.md` file is included in the repository to give you a starting point.

3. **Write Your Story**: With a plan in place, work with the **Prose Weaver** to write your manuscript chapter by chapter.

4. **Refine and Polish**: Once you have a draft, use the **Narrative Editor** to get feedback and improve your work.

5. **Get Ready to Publish**: Finally, consult the **Literary Agent** to prepare your submission materials.

This structured approach ensures that your story remains consistent and that you always have a clear path forward. Happy writing!
