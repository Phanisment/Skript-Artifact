# Skript Artifact
<p>
	<img alt="Language" alight=center src="https://img.shields.io/badge/Language-Skript-orange?style=flat">
	<img alt="Version" src="https://img.shields.io/badge/Version-0.1--dev-light?style=flat">
</p>

> [!CAUTION]
> This project is just in development.

Dependency:
- [Skript](https://github.com/SkriptLang/Skript)
- [Skbee](https://github.com/ShaneBeee/SkBee)
- [Skript-Json](https://github.com/btk5h/skript-json)
- [Skript-Reflect](https://github.com/SkriptLang/skript-reflect)
- [MythicMobs](https://mythiccraft.io/index.php)

Feature:
- Same as MythicCrucible or MMOItems but smaller version and its Free :D

## Documentation

> [!NOTE]
> Not implement for now. Just idea the project.

### Skill Activator:

|Value                                             |Description                                       |
|--------------------------------------------------|--------------------------------------------------|
|`right_click`                                     |Like using Fishing Rod or other righ clicked items|
|`left_click`                                      |When attack or hit air and block                  |
|`damaged`                                         |When player get hit                               |
|`consume`                                         |Like consume potion or Eat food                   |
|`pickup`                                          |                                                  |
|`attack`                                          |                                                  |
|`shoot`                                           |                                                  |
|`shift`                                           |                                                  |
|`drop`                                            |                                                  |
|`use`                                             |                                                  |

<details open>
	<summary>Example Configuration</summary>

```json
{
  "items":[
    {
      "id": "wooden_katana",
      "displayname": "Wooden Katana",
      "material": "wooden_sword",
      "model": 1,
      "attributes": {
        "unbreakable": true
      },
      "ability": [
        {"skill":"dash", "type":"right_click", "cooldown": 60}
      ]
    },
    {
      "id": "iron_katana",
      "displayname": "Iron Katana",
      "material": "wooden_sword",
      "model": 2,
      "attributes": {
        "unbreakable": true
      },
      "ability": [
        {"skill":"dash", "type":"right_click", "cooldown": 40},
        {"skill":"slash", "type":"left_click", "cooldown": 2, "cooldown_warn":false}
      ]
    }
  ]
}
```

</details>

# Plans on project
- [ ] Oraxen support
- [ ] Itemsadder support
- [ ] Item abilities activator
- [ ] Armor abilities activator
- [ ] File configuration items
- [ ] Change file configuration to YML without addon plugin
- [ ] Modifying damage or attributes skill on configuration item
- [ ] Make own Json system array list(For reduce dependency of plugins)
- [ ] Make own NBT system system using NMS(For reduce dependency of plugins)
