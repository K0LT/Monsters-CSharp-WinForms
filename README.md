# Monsters

A Windows Forms-based monster-raising game written in C#. Players collect, train, and evolve monsters while engaging in mini-games, battling bosses, and managing health, experience, and inventory.

## Features

- Player Monster Menu with real-time stats and switching
- Boss Battles with progressive difficulty
- Interactive Mini-Games for rewards and experience
- Leveling System with 3-stage monster evolution
- Item & Inventory System for health and stamina management
- Data Binding for responsive UI updates

## Technologies

- C# (.NET 9.0)
- Windows Forms (WinForms)
- Custom models and data structures
- JSON-based save/load system
- Embedded resources for graphics

## Project Structure

- **Monster.Core**: Domain models and shared data structures
- **Monster.Game**: Game logic, state management, and data services
- **Monster.UI**: Windows Forms presentation layer with navigation system

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/MonsterRaiser.git
   cd MonsterRaiser
   ```

2. Open the solution in Visual Studio and set "Monster.UI" as the startup project.

3. Build and run the application.