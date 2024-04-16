# Prompt Engineering for Recipe Concierge (GLaDOS)

This repo contains the prompt engineering for the recipe concierge conversational AI. 

Prompts are kept in the `prompt` folder. They are versioned. The prompts are made up of:
* `prompt-engineering.md` - the core prompts that govern the behaviour of the conversational AI.
* `guard-rails.md` - the set of rules that seek to prevent the LLM from engaging in unaligned behaviour.
* `tone-guide.md` - rules that guide the tone that the LLM takes. 

**Any** changes to the prompts should be recorded. This means that you should duplicate the latest version folder, and update the duplicate. Increment the version number each time you do this. 

When you make a new version, make sure you put in `update-notes.md` a summary of what you have updated. 

## TODO: metrics

In the future, we will also record metrics against each updated version. This means that we can avoid making regressions with our updates. 