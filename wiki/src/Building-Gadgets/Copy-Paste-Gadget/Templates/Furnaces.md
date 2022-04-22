<!-- # Copy-Paste Gadget Templates // FURNACES -->
> Follow [this](https://github.com/Direwolf20-MC/BuildingGadgets/wiki/Template-Manager) tutorial to understand how to use the templates below.
<!-- VANILLA FURNACE - START -->
<details>
<summary>Vanilla Furnace</summary>
<p>

```json
{
  "version": "2.1.0",
  "mc_version": "1.16.5",
  "name": "Furnace",
  "author": "Kikiisyourfriend",
  "bounding_box": {
    "min_x": 0,
    "min_y": 0,
    "min_z": 0,
    "max_x": 2,
    "max_y": 2,
    "max_z": 2
  },
  "material_list": {
      "root_type": "buildinggadgets:entries",
    "root_entry": [
      {
          "item_type": "buildinggadgets:simple_item",
        "count": 1,
        "item": {
          "id": "minecraft:campfire"
        }
      },
      {
        "item_type": "buildinggadgets:simple_item",
        "count": 24,
        "item": {
          "id": "minecraft:cobblestone"
        }
      },
      {
          "item_type": "buildinggadgets:simple_item",
        "count": 1,
        "item": {
          "id": "minecraft:spruce_log"
        }
      }
    ]
  }
}
```

</p>
</details>
<!-- VANILLA FURNACE - END -->

<!-- REDSTONE FURNACE - START -->
<details>
<summary>Redstone Furnace</summary>
<p>

```json
{
  "version": "2.1.0",
  "mc_version": "1.16.5",
  "name": "Redstone Furnace",
  "author": "Kikiisyourfriend",
  "bounding_box": {
    "min_x": 0,
    "min_y": 0,
    "min_z": 0,
    "max_x": 4,
    "max_y": 4,
    "max_z": 4
  },
  "material_list": {
    "root_type": "buildinggadgets:entries",
    "root_entry": [
      {
        "item_type": "buildinggadgets:simple_item",
        "count": 9,
        "item": {
          "id": "kubejs:etherealslate_block"
        }
      },
      {
        "item_type": "buildinggadgets:simple_item",
        "count": 18,
        "item": {
          "id": "minecraft:furnace"
        }
      },
      {
        "item_type": "buildinggadgets:simple_item",
        "count": 36,
        "item": {
          "id": "minecraft:glass"
        }
      },
      {
        "item_type": "buildinggadgets:simple_item",
        "count": 62,
        "item": {
          "id": "thermal:machine_frame"
        }
      }
    ]
  }
}
```

</p>
</details>
<!-- REDSTONE FURNACE - END -->


<!-- IRON FURNACE - START -->
<details>
<summary>Iron Furnace</summary>
<p>

```json
{
  "version": "2.1.0",
  "mc_version": "1.16.5",
  "name": "Iron Furnace",
  "author": "SuperNate903",
  "bounding_box": {
    "min_x": 0,
    "min_y": 0,
    "min_z": 0,
    "max_x": 2,
    "max_y": 2,
    "max_z": 2
  },
  "material_list": {
    "root_type": "buildinggadgets:entries",
    "root_entry": [
      {
        "item_type": "buildinggadgets:simple_item",
        "count": 1,
        "item": {
          "id": "minecraft:furnace"
        }
      },
      {
        "item_type": "buildinggadgets:simple_item",
        "count": 1,
        "item": {
          "id": "minecraft:hopper"
        }
      },
      {
        "item_type": "buildinggadgets:simple_item",
        "count": 23,
        "item": {
          "id": "minecraft:iron_block"
        }
      },
      {
        "item_type": "buildinggadgets:simple_item",
        "count": 1,
        "item": {
          "id": "minecraft:redstone_block"
        }
      }
    ]
  }
}
```

</p>
</details>
<!-- IRON FURNACE - END -->

<!-- GOLD FURNACE - START -->
<details>
<summary>Gold Furnace</summary>
<p>

```json
{
  "version": "2.1.0",
  "mc_version": "1.16.5",
  "name": "Gold Furnace",
  "author": "SuperNate903",
  "bounding_box": {
    "min_x": 0,
    "min_y": 0,
    "min_z": 0,
    "max_x": 2,
    "max_y": 2,
    "max_z": 2
  },
  "material_list": {
    "root_type": "buildinggadgets:entries",
    "root_entry": [
      {
        "item_type": "buildinggadgets:simple_item",
        "count": 23,
        "item": {
          "id": "minecraft:gold_block"
        }
      },
      {
        "item_type": "buildinggadgets:simple_item",
        "count": 1,
        "item": {
          "id": "minecraft:hopper"
        }
      },
      {
        "item_type": "buildinggadgets:simple_item",
        "count": 1,
        "item": {
          "id": "ironfurnaces:iron_furnace"
        }
      },
      {
        "item_type": "buildinggadgets:simple_item",
        "count": 1,
        "item": {
          "id": "minecraft:redstone_block"
        }
      }
    ]
  }
}
```

</p>
</details>
<!-- GOLD FURNACE - END -->

<!-- DIAMOND FURNACE - START -->
<details>
<summary>Diamond Furnace</summary>
<p>

```json
{
  "version": "2.1.0",
  "mc_version": "1.16.5",
  "name": "Diamond Furnace",
  "author": "SuperNate903",
  "bounding_box": {
    "min_x": 0,
    "min_y": 0,
    "min_z": 0,
    "max_x": 2,
    "max_y": 2,
    "max_z": 2
  },
  "material_list": {
    "root_type": "buildinggadgets:entries",
    "root_entry": [
      {
        "item_type": "buildinggadgets:simple_item",
        "count": 23,
        "item": {
          "id": "minecraft:diamond_block"
        }
      },
      {
        "item_type": "buildinggadgets:simple_item",
        "count": 1,
        "item": {
          "id": "ironfurnaces:gold_furnace"
        }
      },
      {
        "item_type": "buildinggadgets:simple_item",
        "count": 1,
        "item": {
          "id": "minecraft:hopper"
        }
      },
      {
        "item_type": "buildinggadgets:simple_item",
        "count": 1,
        "item": {
          "id": "minecraft:redstone_block"
        }
      }
    ]
  }
}
```

</p>
</details>
<!-- DIAMOND FURNACE - END -->

<!-- EMERALD FURNACE - START -->
<details>
<summary>Emerald Furnace</summary>
<p>

```json
{
  "version": "2.1.0",
  "mc_version": "1.16.5",
  "name": "Emerald Furnace",
  "author": "SuperNate903",
  "bounding_box": {
    "min_x": 0,
    "min_y": 0,
    "min_z": 0,
    "max_x": 2,
    "max_y": 2,
    "max_z": 2
  },
  "material_list": {
    "root_type": "buildinggadgets:entries",
    "root_entry": [
      {
        "item_type": "buildinggadgets:simple_item",
        "count": 1,
        "item": {
          "id": "ironfurnaces:diamond_furnace"
        }
      },
      {
        "item_type": "buildinggadgets:simple_item",
        "count": 23,
        "item": {
          "id": "minecraft:emerald_block"
        }
      },
      {
        "item_type": "buildinggadgets:simple_item",
        "count": 1,
        "item": {
          "id": "minecraft:hopper"
        }
      },
      {
        "item_type": "buildinggadgets:simple_item",
        "count": 1,
        "item": {
          "id": "minecraft:redstone_block"
        }
      }
    ]
  }
}
```

</p>
</details>
<!-- EMERALD FURNACE - END -->