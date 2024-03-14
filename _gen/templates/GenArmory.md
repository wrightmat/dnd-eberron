---
PromptInfo:
 promptId: GenArmory
 name: 🎲 Generate Armory 🛡️
 description: Generate a fantasy store that sells armor. 
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
Prompt: Name and description of a store that sells armor in a fantasy town.

### Prompt: Store Owner Name 
Prompt: Provide a description of the store owner and any employees here.

### Wares
Prompt: Create a table in Markdown here of four to eight random armor items that might be found in a fantasy store that sells armor. The items should come from the list of items in Dungeons and Dragons 5th Edition, plus include at least one item from Kobold Press (KP) OGL (http://kpogl.wikidot.com/items). Include columns for: Item Name, Price, Rarity, Type (if requiring attunement, indicate so here), and a one-line description. Please format the item name as a link by formatting it like this [[item name]].