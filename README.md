# GlobeGrafter
The map component on the full -chain is not just a map

## WINNER OF 🏆 Superhack 2023 Finalist
You can view project details and videos in ETHGLOBAL

https://ethglobal.com/showcase/globegrafter-wyfb5





Game trial link （ The goerli-optimism network needs to be configured in MetaMask）：https://rogue.cenozoic.xyz/


# Project Description
We utilize the GlobeGrafter module to generate game maps and have developed an example roguelike game. In this game, the map data generated by GlobeGrafter determines the information of elements such as walls, floors, and doors. Monsters are randomly spawned on the map, and the damage dealt during attacks is also randomly determined. This is a fully on-chain play-to-die game.

To enhance the gameplay experience, we have implemented zero-knowledge proofs so that players do not need to interact with the blockchain after every single action. Instead, players can interact with the blockchain and validate their proofs when they eventually die in the game. Upon game completion, a random hero NFT is minted. If the player's experience (exp) exceeds 5000, a rare goddess NFT is minted. These NFTs contain the final records of the game, including dungeon level, level, exp, damage, attack, and gold information. These NFTs are independent and can be utilized in other applications as well, making rare NFTs highly sought after.

In the game, players can move using directional keys and press the '>' key when on a 🌟 position to enter the next dungeon level. Each map is randomly generated, ensuring unique gameplay experiences for each session.

# Game Features 

The underlying rules for creating a full chain game We only define the basic data of the project. Make sure the data structure and calculation formulas are on the chain. Various types of products can be derived from the basic rules.
Permission-free extensibility makes it possible to create a variety of game types based on the underlying rules, including RPG games, SLG games, tower defense games, and more. Free battles and events can be held in different game genres, and we warmly welcome individual developers to participate in the expansion of the game genre.






# roguelike game contract

## NEO EVM testnet
```shell
GameAttrProof:
0x2dCD504C2c9ee31C079c4a2770c8bc6F71514445

ERC1967PROXY:
0x4905930dD16e6628BF34Fab96D15B25913fF60D0

HeroNFT:
0xA4D44dd5a4e6EC424704B894a65dD27b8261cd3B

ERC721MetaData:
0x8064d4BE039DE721001e7a498dC5C344789F6F87
```

## BNB testnet
```shell
GameAttrProof:
0x71Ac3c8bee6BA07c7A63d3df98C41c76260E92cE

ERC1967PROXY:
0x57A41532D5861504E8b1f7a25f1d98D5502EeA61

HeroNFT:
0xA4D44dd5a4e6EC424704B894a65dD27b8261cd3B

ERC721MetaData:
0x2dCD504C2c9ee31C079c4a2770c8bc6F71514445
```

## goerli-optimism
```shell
GameAttrProof:
0x627a72bbE16416Ae722BA05876C5cB2dcb0Dc6BB

ERC1967PROXY:
0x495a44Ec3Eb4945abb61c05e5F26A826Bc42CEDb

HeroNFT:
0x3cc3cEb0FA17aA630172ba0FC0F1cA8c5D6C508E

ERC721MetaData:
0xa896d76635b0552Fd60074E9AB44d323cA58178A
```


## Mode Sepolia
```shell
GameAttrProof:
0xb77BFC71EA0B1dF22E7F0410eCD5Dc463E7bAf66

ERC1967PROXY:
0x2FAE5D689B62b47AD3f84c144AB52304bcAbb3cb

HeroNFT:
0x35a7193f86d834F5277ee673F7D29c17C99332e7

ERC721MetaData:
0x038Dd0AEC11Db1fA5981B5F9B02DA3fa30Cb3880
```

## Base Goerli
```shell
GameAttrProof:
0xd56527fa25f8708a416f44DadEa8D96F945b6bd3

ERC1967PROXY:
0x2dCD504C2c9ee31C079c4a2770c8bc6F71514445

HeroNFT:
0x76257c16688e341dFDF8197A9F34546e200d1717

ERC721MetaData:
0xC410793eD374e33615ed5Ae783D0a795A0DfED9b
```

## Zora Goerli
```shell
GameAttrProof:
0x8064d4BE039DE721001e7a498dC5C344789F6F87

ERC1967PROXY:
0x2dCD504C2c9ee31C079c4a2770c8bc6F71514445

HeroNFT:
0x76257c16688e341dFDF8197A9F34546e200d1717

ERC721MetaData:
0x54273407780fB2382AEBCd7da7362Be8a75F86dC
```

# Map Contract

## Optimism Goerli
```shell

CONSTANT:
0x26E93649076Db1AcA99939318b6095eCE3905D14

MATHUTIL:
0x935602fd8D2cB4A547D9214d0FD4cb2B53709F4F

RNG:
0xB19108002A01aECC326F56d9DaF66C7d1b1d7BBc

SETUPMANAGER:
0x0d75325F532c1F7653217E2a1334aFaF060675Cb

ROOMMANAGER:
0x162cc7DE6eA7Cd4547c0CB5aDc7cdb35a0c8dBF9

MAPDRAWER:
0x3f1EE0df85726F7DEa1740BC517a63C96238B3ac

ROGUE:
0x79C21942b87f3417A3ca5D1C8797d8E911f19c55

```
## BNB testnet
```shell
0x76257c16688e341dFDF8197A9F34546e200d1717
```

## NEO EVM testnet
```shell
0xd56527fa25f8708a416f44DadEa8D96F945b6bd3
```

## Mode Sepolia
```shell
0xc4970699CD059ede4Ad1474b8daf5D37943ad8b8
```
## Base Goerli
```shell
0xcd6781E19334298909C5830B1148Ad867BBCb601
```
## Zora Goerli
```shell
0xd56527fa25f8708a416f44DadEa8D96F945b6bd3
```
### map generate
![generate](https://github.com/liushuheng163/GlobeGrafter/blob/main/img/IMG46.jpg?raw=true)

## Screenshots of some games：
![game](https://github.com/liushuheng163/GlobeGrafter/blob/main/img/71691566886_.pic.jpg?raw=true)

### BNB:
![BNB](https://github.com/liushuheng163/GlobeGrafter/blob/main/img/BNB.png?raw=true))

### NEO:
![NEO](https://github.com/liushuheng163/GlobeGrafter/blob/main/img/NEO.png?raw=true)

### Optimism:

![NFT](https://github.com/liushuheng163/GlobeGrafter/blob/main/img/41691566661_.pic.jpg?raw=true)

![OPENSEA](https://github.com/liushuheng163/GlobeGrafter/blob/main/img/61691566761_.pic.jpg?raw=true)

### Mode:
![OPENSEA](https://github.com/liushuheng163/GlobeGrafter/blob/main/img/Mode%20Sepolia.pic.jpg?raw=true)
![OPENSEA](https://github.com/liushuheng163/GlobeGrafter/blob/main/img/Mode%20Sepolia-1.pic.jpg?raw=true)

### Base
![base](https://github.com/liushuheng163/GlobeGrafter/blob/main/img/IMG1742.jpg?raw=true)
### Zora
![zora](https://github.com/liushuheng163/GlobeGrafter/blob/main/img/IMG1746.jpg?raw=true)
