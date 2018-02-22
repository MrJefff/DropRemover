**DropRemover** allows you to remove world items from the map with no effect on server performance. You can remove all items on the map via the name of the item, via the category of the item or you can also remove every world item from the map if you wish. This is useful if you have some craft spammers and you want to remove the spammed items from your map without restarting the server.

**You need to have auth level to use these commands.**

## Commands
- **drops.remove** -- Removes ALL world items from the map.
- **drops.itemremove [item name]** -- Removes all items on the map that are named **[item name]**
- **drops.categoryremove [category]** -- Removes all items on the map that are in the specified category (to see the item categories press F1 in-game and click the "tools" section. Each tab at the top is an item category.

## Default language file
```json
{
  "Permission": "You don't have permission to use that command",
  "Removing": "Removing all dropped items on the map...",
  "Removed": "Removed {0} dropped items on the map",
  "CategoryRemove": "Removing all dropped items in the {0} category",
  "Category": " in the '{0}' category",
  "ItemRemove": "Removing all dropped {0}'s on the map",
  "ItemRemoved": "Removed {0}x {1} from the map",
  "NoDrops": "No drops found",
  "InvalidArgs": "Invalid arguments",
  "NoItem": "No item found with input '{0}'",
  "NoCategory": "No category found with input '{0}'"
}
```
