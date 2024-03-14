---
PromptInfo:
 promptId: GenMagic1
 name: 🎲 Generate Magic Shop 🪙
 description: Generate a fantasy magic shop. 
 author: JoshP
 tags: fantasy, ttrpg
 version: 0.0.1
---

{{#if selection}}
Use this Information for flavoring the Prompt:
*Main Focus*
{{title}} ({{type}}:
{{#each sum}}
- {{this}}
{{/each}}
{{selection}}
*Less important things, but maybe helpful in Context*:
{{#each children}}
{{#if frontmatter.sum}}
{{this.basename}}:
{{#each frontmatter.sum}}
- {{this}}
{{/each}}
{{/if}}
{{/each}}
Use the above information JUST FOR CONTEXT. Come up with new Ideas inspired by the things above, but do not just iterate things from above
{{/if}}
### Prompt: Store Name
Prompt: Store Name and description of a small fantasy shop that sells magic items.

### Prompt: Store Keeper Name 
Prompt: Provide a description of the store owner and any employees here.

### Wares
Prompt: Create a table in Markdown here of four to eight random items that might be found in a fantasy shop that sells magic items. The items should come from the list of items in Dungeons and Dragons 5th Edition. Include three potions in the list that are common or uncommon. The other items should be mainly uncommon or rare with one very rare item. Include columns for: Item Name, Price, Rarity, Type (if requiring attunement, indicate so here), and a one-line description. Please format the item name as a link by formatting it like this [[item name]].