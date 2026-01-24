# ucm-mc-docker

Deployable Docker-based Minecraft instance tailored towards UC Merced's Minecraft servers

## Information

This repository acts as as foundation for deploying the UC Merced Minecraft server. It leverages [Docker](<https://www.docker.com/>) via [itzg/docker-minecraft-server](<https://github.com/itzg/docker-minecraft-server>) to deploy on any machine with minimal setup. Performance has been optimized through [YouHaveTrouble's Optimization Guide](<https://github.com/YouHaveTrouble/minecraft-optimization>) and [Paper-chan's Minecraft Server Optimization Guide](<https://paper-chan.moe/paper-optimization/>), which attempt to align with sensible defaults while maintaining a Vanilla-styled experience. In addition, and an instance of MariaDB is also attached to allow for high-performance storage of database records

World generation utilizes [Terra](<https://modrinth.com/plugin/terra>) to provide customized world generation across all 3 dimensions while providing a Vanilla-styed experience. Community packs utilized are as follows:

- Overworld: [Overworld Pack](<https://github.com/PolyhedralDev/TerraOverworldConfig>)
- Nether: [Tartarus](<https://github.com/Jason-Ding19/Tartarus>)
- The End: [ReimagEND](<https://github.com/PolyhedralDev/ReimagEND>)

> [!NOTE]
> Minecraft Bedrock Edition clients can also join this server

Plugins utilized include:

- [LuckPerms](<https://luckperms.net/>)
- [CoreProtect](<https://modrinth.com/plugin/coreprotect>)
- [Geyser](<https://geysermc.org/>) and [Floodgate](<https://geysermc.org/wiki/floodgate/>)
- [ViaVersion](<https://modrinth.com/plugin/viaversion>)
- [Bolt](<https://modrinth.com/plugin/bolt>)
- [Terra](<https://modrinth.com/plugin/terra>)

## License

All Rights Reserved, 2025 - Present
