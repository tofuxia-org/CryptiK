# CryptiK

CryptiK is a modular system designed for managing dungeon instances in the [Tofuxia Minecraft server project](https://github.com/Juloass/Tofuxia). It consists of three main sub-repositories:

## CryptiK-Instance

[CryptiK-Instance](https://github.com/Juloass/CryptiK-Instance) is a Minecraft mod responsible for listening to requests from the CryptiK Master server. It handles instance setup and communication within the Minecraft game environment.

## CryptiK-Master

[CryptiK-Master](https://github.com/Juloass/CryptiK-Master) is an independent server with its own networking code. It manages requests from CryptiK-Orderer and manage CryptiK instances. The master server coordinates instance setup, notifies the orderer when instances are ready while providing connection information.

## Cryptik-Orderer

[Cryptik-Orderer](https://github.com/Juloass/Cryptik-Orderer) is another Minecraft mod responsible for ordering dungeon instances from the CryptiK Master server. It communicates with the master server to request instance setups and receives connection information once instances are ready. Additionally, it provides players in the Minecraft world with updates on their position in the queue for a dungeon instances.

## Contributing

We welcome contributions to the CryptiK project. If you're interested in contributing, please check out our [contribution guidelines](https://github.com/Juloass/Tofuxia/blob/main/CONTRIBUTING.md).

## License

All rights reserved &copy; Tofuxia (Association loi 1901)
