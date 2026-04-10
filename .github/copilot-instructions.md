# FlaUI

UI automation library for Windows desktop applications. Wraps native UIA2 and UIA3 accessibility APIs into a clean .NET interface.

## Tech Stack
- .NET / C#
- NuGet packages: FlaUI.Core, FlaUI.UIA2, FlaUI.UIA3
- MSBuild

## Development
```bash
dotnet build
dotnet test
```

## Structure
- `FlaUI.Core` — Core automation abstractions
- `FlaUI.UIA2` / `FlaUI.UIA3` — UIA backend implementations

## Conventions
- Follow .NET naming conventions
- Write XML doc comments for public APIs
- Maintain backward compatibility
