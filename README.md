# Skript Artifact

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

System Code:
- Read file configuration and add nbt to item same as name of file and detect if item name is same, get data in configuration and activate not like data on item, so you cant make same item but deference data.

## Documentation

> [!NOTE]
> Not implement for now. Just idea the project.

### Skill Activator:

- `right_click`
- `left_click`
- `damaged`
- `consume`
- `pickup`
- `attack`
- `shoot`
- `shift`
- `drop`
- `use`

### Example:
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
