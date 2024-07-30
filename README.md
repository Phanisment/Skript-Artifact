# Skript Artifact
> [!CAUTION]
> This project is just in development.

<p>
  <img alt="Language" src="https://img.shields.io/badge/Language-Skript-orange?style=flat">
  <img alt="Version" src="https://img.shields.io/badge/Version-0.1--dev-light?style=flat">
</p>

Dependency:
- [Skript](https://github.com/SkriptLang/Skript)
- [Skbee](https://github.com/ShaneBeee/SkBee)
- [Skript-Yml](https://github.com/Sashie/skript-yaml)
- [Skript-Reflect](https://github.com/SkriptLang/skript-reflect)
- [MythicMobs](https://mythiccraft.io/index.php)

Feature:
- Same as MythicCrucible or MMOItems but smaller version and its Free :D

## Documentation

> [!NOTE]
> Not implement for now. Just idea the project.

### Skill Trigger:

|Value|Description|
|---|---|
|`right_click`|Like using Fishing Rod or other righ clicked items|
|`left_click`|When attack or hit air and block|
|`attack`|When player attack entity or player, like right_click but deference|
|`damaged`|When player get hit|
|`equip`|When player equip armor|
|`unequip`|When player unequip armor|
|`drop`|When Dropped item|
|`pickup`|When Pickup dropped item|
|`consume`|Like consume potion or Eat food|
|`shoot`|When player use bow|
|`use`|When use item, just lime consume or right click event|
|`shift`|When player is Sneaking|

<details open>
  <summary>Example File Configuration</summary>

```json
{
  "items": [
    {
      "permission": "example.wooden_bat",
      "type": "wooden_sword",
      "displayname": "Wooden Bat",
      "model": 1,
      "abilities": [
        {"id":"dash", "event":"right_click"}
      ]
    }
  ]
}
```

</details>

<details open>
<summary>Example Item Nbt</summary>

```
{
  display{
    Name:'{"text":"Wooden Bat","italic":false}'
  },
  CustomModelData:1,
  Abilities:[
    {id:"dash", event:"right_click"}
  ]
}
```

</details>

### Configuration
<details open>
  <summary>config.json</summary>

```
{
  "version": 0.1,
}
```

</details>



# Plans for Project
<details close>
  <summary>Plans</summary>

- [ ] Oraxen support
- [ ] Itemsadder support
- [ ] Item abilities activator
- [ ] Armor abilities activator
- [ ] File configuration items
- [ ] Change file configuration to YML without addon plugin
- [ ] Modifying damage or attributes skill on configuration item
- [ ] Make own Json system array list(For reduce dependency of plugins)
- [ ] Make own NBT system system using NMS(For reduce dependency of plugins)

</details>