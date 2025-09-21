# Self-Healing-Automation
It demonstrates how automated test scripts can adapt to UI changes without breaking the regression cycle. The goal of this project is to inspire automation engineers to explore AI-powered techniques and integrate them into their workflows, making tests more resilient, intelligent, and maintainable.
# What is automation self-healing?

Self-healing UI automation means your tests still find and operate on the right elements even after the UI shifts (renamed classes, moved buttons, minor layout changes), so regressions fail only when behavior breaks not just selectors.

# Practical solution

I will demonstrate this POC on a one-page registration website + Playwright tests wired to the self-healing helper. It includes a “Simulate UI change” button that removes test IDs, renames ids/names, and reshuffles the DOM—so you can prove the tests still pass.

