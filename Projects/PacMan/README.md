﻿<h1 align="center">
	PacMan
</h1>

<p align="center">
	<a href="https://github.com/ZacharyPatten/dotnet-console-games" alt="GitHub repo"><img alt="flat" src="https://raw.githubusercontent.com/ZacharyPatten/dotnet-console-games/main/.github/resources/github-repo-black.svg"></a>
	<a href="https://docs.microsoft.com/en-us/dotnet/csharp/" alt="GitHub repo"><img alt="Language C#" src="https://raw.githubusercontent.com/ZacharyPatten/dotnet-console-games/main/.github/resources/language-csharp.svg"></a>
	<a href="https://discord.gg/4XbQbwF" alt="Discord"><img src="https://raw.githubusercontent.com/ZacharyPatten/dotnet-console-games/main/.github/resources/discord-badge.svg" title="Go To Discord Server" alt="Discord"/></a>
	<a href="https://github.com/ZacharyPatten/dotnet-console-games/blob/master/LICENSE" alt="license"><img src="https://raw.githubusercontent.com/ZacharyPatten/dotnet-console-games/main/.github/resources/license-MIT-green.svg" /></a>
</p>

**[Source Code](Program.cs)**

PacMan is a game where you eat dots. Eat as many dots as you can while avoiding the Ghosts. If the ghosts catch you, you die.

```
    ╔═══════════════════╦═══════════════════╗
    ║ · · · · · · · · · ║ · · · · · · · · · ║
    ║ · ╔═╗ · ╔═════╗ · ║ · ╔═════╗ · ╔═╗ · ║
    ║ + ╚═╝ · ╚═════╝ · ╨ · ╚═════╝ · ╚═╝ + ║
    ║ · · · · · · · · · · · · · · · · · · · ║
    ║ · ═══ · ╥ · ══════╦══════ · ╥ · ═══ · ║
    ║ · · · · ║ · · · · ║ · · · · ║ · · · · ║
    ╚═════╗ · ╠══════   ╨   ══════╣ · ╔═════╝
          ║ · ║                   ║ · ║
    ══════╝ · ╨   ╔════---════╗   ╨ · ╚══════
            ·     ║ █ █   █ █ ║     ·        
    ══════╗ · ╥   ║           ║   ╥ · ╔══════
          ║ · ║   ╚═══════════╝   ║ · ║
          ║ · ║       READY       ║ · ║
    ╔═════╝ · ╨   ══════╦══════   ╨ · ╚═════╗
    ║ · · · · · · · · · ║ · · · · · · · · · ║
    ║ · ══╗ · ═══════ · ╨ · ═══════ · ╔══ · ║
    ║ + · ║ · · · · · · █ · · · · · · ║ · + ║
    ╠══ · ╨ · ╥ · ══════╦══════ · ╥ · ╨ · ══╣
    ║ · · · · ║ · · · · ║ · · · · ║ · · · · ║
    ║ · ══════╩══════ · ╨ · ══════╩══════ · ║
    ║ · · · · · · · · · · · · · · · · · · · ║
    ╚═══════════════════════════════════════╝
```

## Input

The **arrow keys (↑, ↓, ←, →)** are used to move. The **escape** key may be used to close the game at any time. If you **resize** the console widow the game will be closed.

## Dependencies

Don't forget these dependencies if you copy the code:

- [Towel](https://github.com/ZacharyPatten/Towel) nuget package _(referenced in [PacMan.csproj](PacMan.csproj))_

<p align="center">
	You can play this game in your browser:
	<br />
	<a href="https://zacharypatten.github.io/dotnet-console-games/PacMan" alt="Play Now">
		<sub><img height="40"src="https://raw.githubusercontent.com/ZacharyPatten/dotnet-console-games/main/.github/resources/play-badge.svg" title="Play Now" alt="Play Now"/></sub>
	</a>
	<br />
	<sup>Hosted On GitHub Pages</sup>
</p>
