---
applyTo: "SocOps/**/*.{razor,cs,css}"
description: "Use when editing the Blazor app, game logic, or UI styling in this workshop project."
---

# Blazor workshop conventions

- Keep the app simple and workshop-friendly; prefer clear, direct component logic over abstraction-heavy patterns.
- Match the existing naming and structure used in the current Blazor components and services.
- When updating UI, keep the tone playful and user-friendly and preserve the social bingo experience.
- Validate changes with `dotnet build` from the project directory when the task affects compilation or runtime behavior.
- Prefer small, incremental changes that stay within the current architecture.
