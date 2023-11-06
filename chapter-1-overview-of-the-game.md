# Chapter 1: Overview of the game

The first question you may have as a reader is, _why would I start going through this book_? That's an excellent question to ask, and we'll dive into it right now.

The primary vision of "Beware of Dragons" is to **empower readers to embark on a fun journey in game development by creating a MUD (Multi-User Dungeon) game server from scratch.**

**What is a multi-user dungeon?**

A MUD game is an online text-based multiplayer game. It allows multiple players to interact and play within a virtual world. They were the predecessors of given MMORPGs, and some are still operating from the 90s, such as [Achaea, Dreams of Divine Lands](https://www.achaea.com).

**Usual features in MUD games**

1. Players interact with the game through a text-based interface. With a given set of commands, players can navigate on the map, speak to NPCs, put on equipment, or attack a monster. The server processes these commands and provides textual responses, updating the game state accordingly.
2. MUDs often foster solid online communities, with players forming alliances. The communication aspect is central, as players can chat, form groups, and engage in role-playing interactions.
3. MUDs often emphasize role-playing and character customization. Players can create and control characters with unique attributes, abilities, and personalities.

Overall, MUD game servers provide a unique and immersive multiplayer gaming experience through text-based interaction and user-driven content. While they may lack the graphical richness of modern 3D MMORPGs, they offer a rich and creative environment where players can engage in storytelling, exploration, and social interaction.

**What's the focus of this book?**

This project-driven book will lead readers through the intricacies of software development, emphasizing practical, real-world experience.

It is an open-source project, offering a comprehensive look into its codebase, server setup, insights into its architecture and design, and game mechanics for those interested in diving deeper into game development.

**What's different about this guide?**

With step-by-step guidance, readers will design, implement, and maintain a fully functional MUD game server. Along the way, they will gain valuable insights into distributed systems, programming, world-building, and creative storytelling. This journey is an opportunity to create an original project while gaining experience in game and web development. Ultimately, it aims to inspire readers to explore the world of software engineering by engaging in a tangible, hands-on project, setting the stage for future software development endeavors.

The book aspires to focus mainly on first principles. That means that as we focus on specific parts of the system, we'll go over at a high level how we should go about reasoning about the problem and coming up with solutions. As we talk about approaches, we won't be tied up to specific technologies at first but rather the general software tools that might be useful to get around a given issue. Doing so, if someone wishes to use, say, Typescript, Python, .NET, or Rust, for instance, to approach developing their game server, they should still be able to follow along.

For the book's sake, readers who want to dive more deeply will be redirected to design artifacts, going to lengths into all the details. This approach ensures that everyone can quickly grasp the book's essence (especially if you're in a hurry).&#x20;

**A quick word on the game**

Set in the enigmatic realm of the Nexus, players step into the shoes of a fallen warrior resurrected by the deity Revelar to exact revenge. The world of Beware of Dragons is filled with breathtaking landscapes, formidable foes, and intriguing characters.

The game's core mechanics revolve around tactical and challenging combat. Beware of Dragons is rooted in the genre of Souls-like games, where precision, timing, and strategy are paramount. A unique time-limited decision-making system keeps players on their toes, requiring quick choices in the face of danger. Elixirs, equipment, techniques, and special abilities define the depth of combat possibilities.

A central element of the game is mastering the mystical Codex of Draconic Ascendancy, a book of ancient dragon knowledge. Players choose their path as a Dragonling Summoner, Dragon Knight, or Dragon Shifter, each with unique strengths and abilities. As they delve deeper into the Codex, they unlock god-like powers, making them formidable forces in the Nexus.
