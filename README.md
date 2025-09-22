# Self Healing Automation

This repo is a proof of concept that shows how UI automation can adapt to changes without breaking the regression cycle.
•	Tiered rules → Stable locators first (data-testid, roles, labels, placeholders).
•	Local fuzzy matching → String similarity to recover from small text changes.
•	 AI Semantic Healing → Uses OpenAI embeddings to find the closest element by meaning when all rules fail.
•	 Heal logs → Every heal is logged (logs/heals/*.jsonl), with a CLI to review and update selectors.
•	Demo site → A one-page registration form + “Simulate UI change” button that removes IDs, renames attributes, and moves DOM nodes — so you can see healing in action.
# Why these matters
In real projects, small UI shifts (renamed buttons, new wrappers, updated placeholders) often cause test scripts to break, leading to wasted time fixing selectors.
This PoC shows how we can make automation resilient, and how AI can play a direct role in test maintenance.
Key Features
•	One-page demo app: Registration form with toggleable DOM mutations.
•	Playwright tests: Demonstrates both stable and broken UI scenarios.
•	Self-healing library: Encapsulates tiers + similarity + AI fallback.
•	AI integration: Optional — set OPENAI_API_KEY to unlock semantic healing.
The goal is to inspire automation engineers to integrate AI into their testing workflows and move toward truly intelligent regression testing.


# Practical solution

I will demonstrate this POC on a one-page registration website + Playwright tests wired to the self-healing helper. It includes a “Simulate UI change” button that removes test IDs, renames ids/names, and reshuffles the DOM—so you can prove the tests still pass.

# Technologies & Tools

# Playwrite
Playwright is an open-source automation framework created by Microsoft for cross-browser web testing and end-to-end automation of modern web applications. It supports modern rendering engines like Chromium, WebKit, and Firefox, allowing developers to use a single API to test across different browsers on various operating systems like Windows, Linux, and macOS. Playwright offers powerful features such as built-in test runners, assertions, parallelization, and tools like auto-waits and code generators to create reliable, fast, and scalable automated tests. 
# JavaScript
JavaScript (JS) is a high-level, interpreted programming language primarily known for its role in making web pages interactive. It allows developers to implement complex features on websites, such as:
Dynamic Content Updates: Changing parts of a webpage without requiring a full page reload.
Interactive Elements: Creating features like menus, forms with validation, and animated graphics.
Multimedia Control: Managing the playback of videos and audio.
User Interaction: Responding to user actions like clicks, hovers, and keyboard input.

# Vcode
Visual Studio Code, often referred to as VS Code, is a free, open-source, and cross-platform source code editor developed by Microsoft. It is a popular choice among developers for its lightweight nature, powerful features, and extensive customizability.



