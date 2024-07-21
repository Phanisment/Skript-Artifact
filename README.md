# Skript Artifact

> [!CAUTION]
> This project is just in development.

### Project Icon
![Skript-Artifact](https://i.imgur.com/4HjhL4g.png)

Dependency:
- [Skript](https://github.com/SkriptLang/Skript)
- [Skbee](https://github.com/ShaneBeee/SkBee)
- [Skript-Reflect](https://github.com/SkriptLang/skript-reflect)
- [MythicMobs](https://mythiccraft.io/index.php)

Feature:
- Same as MythicCrucible or MMOItems but smaller version and its Free :D

## Documentation
> [!NOTE]
> Not implement for now. Just idea the project.

### Skill Activator:
Left Click:
- `left_click` or  `left`
- `left_click_block`
- `left_click_air`

Right Click:
- `right_click` or `right`
- `right_click_block`
- `right_click_air`

Use Item:

Others:
- `sneak` or `shift`
- `consume`
- `damaged`
- `pickup`
- `attack`
- `shoot`
- `drop`
- `use`

### Example
```json
{
  "items":{
    "<id>":{
      "displayname":"...",
      "model": 1
      "attributes":{
        ...
      },
      "ability":{
        ...
      }
    }
  }
}
```


# Plans on project
- [ ] Item abilities activator
- [ ] Armor abilities activator
- [ ] File configuration items
- [ ] Make own NBT using NMS(For reduce dependency of plugin)
- [ ] Automatic updating of data from items to match those in the configuration file
- [ ] Modifying damage or attributes skill on configuration item