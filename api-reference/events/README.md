# Events

## Base KubeJS Events

| **Folder**          | **Method**                              | **Cancellable** |
| ------------------- | --------------------------------------- | --------------- |
| `/startup_scripts/` | `StartupEvents.init`                    | ❌               |
| `/startup_scripts/` | `StartupEvents.postInit`                | ❌               |
| `/startup_scripts/` | `StartupEvents.registry`                | ❌               |
|                     | - fluid                                 |                 |
|                     | - block                                 |                 |
|                     | - item                                  |                 |
|                     | - enchantment                           |                 |
|                     | - mob effects                           |                 |
|                     | - sound event                           |                 |
|                     | - block entity type                     |                 |
|                     | - potion                                |                 |
|                     | - particle type                         |                 |
|                     | - painting variant                      |                 |
|                     | - custom stat                           |                 |
|                     | - point of interest type                |                 |
|                     | - villager type                         |                 |
|                     | - villager profession                   |                 |
|                     |                                         |                 |
| `/client_scripts/`  | `ClientEvents.highPriorityAssets`       | ❌               |
| `/client_scripts/`  | `ClientEvents.init`                     | ❌               |
| `/client_scripts/`  | `ClientEvents.loggedIn`                 | ❌               |
| `/client_scripts/`  | `ClientEvents.loggedOut`                | ❌               |
| `/client_scripts/`  | `ClientEvents.tick`                     | ❌               |
| `/client_scripts/`  | `ClientEvents.painterUpdated`           | ❌               |
| `/client_scripts/`  | `ClientEvents.leftDebugInfo`            | ❌               |
| `/client_scripts/`  | `ClientEvents.rightDebugInfo`           | ❌               |
| `/client_scripts/`  | `ClientEvents.paintScreen`              | ❌               |
|                     |                                         |                 |
| `/server_scripts/`  | `ServerEvents.lowPriorityData`          | ❌               |
| `/server_scripts/`  | `ServerEvents.highPriorityData`         | ❌               |
| `/server_scripts/`  | `ServerEvents.loaded`                   | ❌               |
| `/server_scripts/`  | `ServerEvents.unloaded`                 | ❌               |
| `/server_scripts/`  | `ServerEvents.tick`                     | ❌               |
| `/server_scripts/`  | `ServerEvents.tags`                     | ❌               |
| `/server_scripts/`  | `ServerEvents.commandRegistry`          | ❌               |
| `/server_scripts/`  | `ServerEvents.command`                  | ✅               |
| `/server_scripts/`  | `ServerEvents.customCommand`            | ✅               |
| `/server_scripts/`  | `ServerEvents.recipes`                  | ❌               |
| `/server_scripts/`  | `ServerEvents.afterRecipes`             | ❌               |
| `/server_scripts/`  | `ServerEvents.specialRecipeSerializers` | ❌               |
| `/server_scripts/`  | `ServerEvents.compostableRecipes`       | ❌               |
| `/server_scripts/`  | `ServerEvents.recipeTypeRegistry`       | ❌               |
| `/server_scripts/`  | `ServerEvents.genericLootTables`        | ❌               |
| `/server_scripts/`  | `ServerEvents.blockLootTables`          | ❌               |
| `/server_scripts/`  | `ServerEvents.entityLootTables`         | ❌               |
| `/server_scripts/`  | `ServerEvents.giftLootTables`           | ❌               |
| `/server_scripts/`  | `ServerEvents.fishingLootTables`        | ❌               |
| `/server_scripts/`  | `ServerEvents.chestLootTables`          | ❌               |
|                     |                                         |                 |
| `/server_scripts/`  | `LevelEvents.loaded`                    | ❌               |
| `/server_scripts/`  | `LevelEvents.unloaded`                  | ❌               |
| `/server_scripts/`  | `LevelEvents.tick`                      | ❌               |
| `/server_scripts/`  | `LevelEvents.beforeExplosion`           | ✅               |
| `/server_scripts/`  | `LevelEvents.afterExplosion`            | ❌               |
|                     |                                         |                 |
| `/startup_scripts/` | `WorldgenEvents.add`                    | ❌               |
| `/startup_scripts/` | `WorldgenEvents.remove`                 | ❌               |
|                     |                                         |                 |
| `/client_scripts/`  | `NetworkEvents.fromServer`              | ✅               |
| `/server_scripts/`  | `NetworkEvents.fromClient`              | ✅               |
|                     |                                         |                 |
| `/startup_scripts/` | `ItemEvents.modification`               | ❌               |
| `/startup_scripts/` | `ItemEvents.toolTierRegistry`           | ❌               |
| `/startup_scripts/` | `ItemEvents.armorTierRegistry`          | ❌               |
| `/server_scripts/`  | `ItemEvents.rightClicked`               | ✅               |
| `/server_scripts/`  | `ItemEvents.canPickUp`                  | ✅               |
| `/server_scripts/`  | `ItemEvents.pickedUp`                   | ❌               |
| `/server_scripts/`  | `ItemEvents.dropped`                    | ✅               |
| `/server_scripts/`  | `ItemEvents.entityInteracted`           | ✅               |
| `/server_scripts/`  | `ItemEvents.crafted`                    | ❌               |
| `/server_scripts/`  | `ItemEvents.smelted`                    | ❌               |
| `/server_scripts/`  | `ItemEvents.foodEaten`                  | ✅               |
| `/client_scripts/`  | `ItemEvents.tooltip`                    | ❌               |
| `/startup_scripts/` | `ItemEvents.modelProperties`            | ❌               |
| `/client_scripts/`  | `ItemEvents.clientRightClicked`         | ❌               |
| `/client_scripts/`  | `ItemEvents.clientLeftClicked`          | ❌               |
| `/server_scripts/`  | `ItemEvents.firstRightClicked`          | ❌               |
| `/server_scripts/`  | `ItemEvents.firstLeftClicked`           | ❌               |
|                     |                                         |                 |
| `/startup_scripts/` | `BlockEvents.modification`              | ❌               |
| `/server_scripts/`  | `BlockEvents.rightClicked`              | ✅               |
| `/server_scripts/`  | `BlockEvents.leftClicked`               | ✅               |
| `/server_scripts/`  | `BlockEvents.placed`                    | ✅               |
| `/server_scripts/`  | `BlockEvents.broken`                    | ✅               |
| `/server_scripts/`  | `BlockEvents.detectorChanged`           | ❌               |
| `/server_scripts/`  | `BlockEvents.detectorPowered`           | ❌               |
| `/server_scripts/`  | `BlockEvents.detectorUnpowered`         | ❌               |
| `/server_scripts/`  | `BlockEvents.farmlandTrampled`          | ❌               |
|                     |                                         |                 |
| `/server_scripts/`  | `EntityEvents.death`                    | ✅               |
| `/server_scripts/`  | `EntityEvents.hurt`                     | ✅               |
| `/server_scripts/`  | `EntityEvents.checkSpawn`               | ✅               |
| `/server_scripts/`  | `EntityEvents.spawned`                  | ✅               |
|                     |                                         |                 |
| `/server_scripts/`  | `PlayerEvents.loggedIn`                 | ❌               |
| `/server_scripts/`  | `PlayerEvents.loggedOut`                | ❌               |
| `/server_scripts/`  | `PlayerEvents.respawned`                | ❌               |
| `/server_scripts/`  | `PlayerEvents.tick`                     | ❌               |
| `/server_scripts/`  | `PlayerEvents.chat`                     | ✅               |
| `/server_scripts/`  | `PlayerEvents.decorateChat`             | ❌               |
| `/server_scripts/`  | `PlayerEvents.advancement`              | ✅               |
| `/server_scripts/`  | `PlayerEvents.inventoryOpened`          | ❌               |
| `/server_scripts/`  | `PlayerEvents.inventoryClosed`          | ❌               |
| `/server_scripts/`  | `PlayerEvents.inventoryChanged`         | ❌               |
| `/server_scripts/`  | `PlayerEvents.chestOpened`              | ❌               |
| `/server_scripts/`  | `PlayerEvents.chestClosed`              | ❌               |

.book .book-body .page-wrapper .page-inner {
  max-width: 90%;
}