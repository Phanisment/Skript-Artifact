# Skript Artifact

> [!CAUTION]
> This project is just in development, use at your caution.

### Project Icon
![Skript-Artifact](https://media.discordapp.net/attachments/1034310454773817345/1264215422316843161/minecraft_title_1.jpg?ex=669d0fdc&is=669bbe5c&hm=ab77053bd0828d2b95a4c2c084af40ec93d3242ecb6881e6a47cb045691ce4ae&)

Dependency:
- [Skript](https://github.com/SkriptLang/Skript)
- [NBT Api](https://github.com/tr7zw/Item-NBT-API)
- [Skript-Reflect](https://github.com/SkriptLang/skript-reflect)
- [MythicMobs](https://mythiccraft.io/index.php)

Feature:
- Same as MythicCrucible, MMOItems but smaller version and its Free :D

## Documentation
### Not implement, just a draft.

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
