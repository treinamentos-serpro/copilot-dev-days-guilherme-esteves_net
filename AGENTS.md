# AGENTS.md

## Mandatory development checklist

Run every applicable check from `SocOps/` before completing a change:

- [ ] Lint/format: `dotnet format --verify-no-changes`
- [ ] Build: `dotnet build`
- [ ] Test: `dotnet test`

## Project

Soc Ops is a .NET 10 Blazor WebAssembly social bingo workshop app.

- Entry point: [SocOps/Program.cs](SocOps/Program.cs)
- UI: [SocOps/Components](SocOps/Components)
- Logic: [SocOps/Services](SocOps/Services)
- Data: [SocOps/Data](SocOps/Data), [SocOps/Models](SocOps/Models)
- Styling: [SocOps/wwwroot/css/app.css](SocOps/wwwroot/css/app.css)

## Conventions

- Keep changes small and consistent with the existing Blazor structure.
- Prefer extending current game state and question flow over adding abstractions.
- Update a component and its related Razor CSS together.
- Keep prompts inclusive, low-stakes, and friendly.
- Avoid heavy dependencies and unrelated refactors.
- Run `dotnet run` from `SocOps/` to inspect behavior after UI or game-flow changes.

See [README.md](README.md) and [workshop/GUIDE.md](workshop/GUIDE.md) for project context and the workshop sequence.
