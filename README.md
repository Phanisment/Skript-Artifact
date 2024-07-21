# Skript Artifact

> [!CAUTION]
> This project is just in development, use at your caution.

### Project Icon
![Skript-Artifact](https://i.imgur.com/4HjhL4g.png)

Dependency:
- [Skript](https://github.com/SkriptLang/Skript)
- [NBT Api](https://github.com/tr7zw/Item-NBT-API)
- [Skript-Reflect](https://github.com/SkriptLang/skript-reflect)
- [MythicMobs](https://mythiccraft.io/index.php)

Feature:
- Same as MythicCrucible, MMOItems but smaller version and its Free :D

## Documentation
> [!NOTE]
> Not implement for now. Just idea the project.

Skill Activator:
- `left_click` or  `left`
- `right_click` or `right`
- `sneak` or `shift`
- `damaged`
- `attack`
- `shoot`
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
[ ] Item abilities activator
[ ] Armor abilities activator
[ ] File configuration items
[ ] Make own NBT using NMS(For reduce dependency of plugin)
[ ] Automatic updating of data from items to match those in the configuration file
[ ] Modifying damage or attributes skill on configuration item