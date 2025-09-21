# Self-Healing-Automation
This repo is proof of concept of how automation testing can be  self-healing Automation, which means automate script adapt to UI changes without breaking the  regression cycle

# What is automation self-healing?

Self-healing UI automation means your tests still find and operate on the right elements even after the UI shifts (renamed classes, moved buttons, minor layout changes), so regressions fail only when behavior breaks not just selectors.

# Practical solution

I will demonstrate this POC on a one-page registration website + Playwright tests wired to the self-healing helper. It includes a “Simulate UI change” button that removes test IDs, renames ids/names, and reshuffles the DOM—so you can prove the tests still pass.

