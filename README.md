# Self-Healing-Automation
It demonstrates how automated test scripts can adapt to UI changes without breaking the regression cycle. The goal of this project is to inspire automation engineers to explore AI-powered techniques and integrate them into their workflows, making tests more resilient, intelligent, and maintainable.
# What is automation self-healing?

Self-healing UI automation means your tests still find and operate on the right elements even after the UI shifts (renamed classes, moved buttons, minor layout changes), so regressions fail only when behavior breaks not just selectors.

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



