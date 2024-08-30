# UE5 Template Project for Horizon Game Server

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Welcome to the UE5 Template Project for Horizon Game Server! This template provides a starting point for creating multiplayer games using Unreal Engine 5 (UE5) that integrate seamlessly with the Horizon Game Server. It includes pre-configured networking components, sample gameplay elements, and integration scripts to help you quickly build and deploy multiplayer experiences powered by Horizon.

## Features

- Pre-configured UE5 project structure optimized for Horizon integration
- Sample multiplayer game logic and components
- Horizon connection management blueprint
- Player synchronization templates
- Basic UI for server connection and game state
- Example of client-side prediction and server reconciliation
- Documentation and code comments for easy customization

## Prerequisites

Before you begin, ensure you have the following installed:

- Unreal Engine 5.2 or later
- Visual Studio 2019 or later (for C++ development)
- Horizon Game Server (latest version)
- Git (for version control)

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/your-organization/ue5-horizon-template.git
   ```

2. Right-click on the `.uproject` file and select "Generate Visual Studio project files" if you plan to use C++.

3. Open the project in Unreal Engine 5 by double-clicking the `.uproject` file.

4. If prompted, rebuild any necessary modules.

## Usage

1. Open the project in Unreal Engine 5.

2. Navigate to the `Content/Levels` folder and open the `MainMenu` level.

3. Press Play in the editor to test the basic connection to Horizon Game Server.

4. Explore the `Content/Blueprints` folder to find example gameplay elements and Horizon integration components.

5. Modify and extend the template to fit your game's requirements.

## Configuration

### Horizon Server Connection

1. Open the `BP_GameInstance` blueprint in `Content/Blueprints/Core`.
2. Locate the "Horizon Server Settings" section.
3. Update the server address and port to match your Horizon Game Server configuration.

### Customizing Player Characters

1. Navigate to `Content/Blueprints/Characters`.
2. Modify `BP_PlayerCharacter` to add or change player abilities and properties.
3. Update `BP_PlayerController` to handle input and game logic specific to your game.

## Troubleshooting

- **Compilation Errors**: Ensure you have the latest version of Unreal Engine 5 installed and that all project plugins are up to date.
- **Connection Issues**: Verify that your Horizon Game Server is running and that the connection settings in `BP_GameInstance` are correct.
- **Synchronization Problems**: Check the "Network Role" settings of your Actor blueprints and ensure proper replication is set up.

For more detailed troubleshooting, refer to the Horizon documentation or reach out to the community forums.

## Contributing

We welcome contributions to improve this template! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes with clear, descriptive messages.
4. Push your branch and submit a pull request.

Please read our [Contributing Guidelines](CONTRIBUTING.md) for more details.

## License

This UE5 Template Project for Horizon Game Server is released under the MIT License. See the [LICENSE](LICENSE) file for details.

---

For more information on Horizon Game Server and its capabilities, visit the [official Horizon documentation](https://docs.horizongameserver.com).

Happy game development!
