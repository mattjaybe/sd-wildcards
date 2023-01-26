# sd-wildcards
**A collection of wildcards for Stable Diffusion + Dynamic Prompts extension**

Using the power of ChatGPT, I've created a number of wildcards to be used in Stable Diffusion by way of the Dynamic Prompts extension found in the Automatic1111 fork.

You can create your own list of wildcards by telling ChatGPT this:

> Give me a list of all the different types of dresses for women. Make sure you list each one on its own line, alphabetical order, in lowercase, in singular form, and that there are no duplicates. Do not number each line.

*or*

> Give me a list of the top 50 well-known actors. Make sure you list each one on its own line, alphabetical order, in lowercase, in singular form, and that there are no duplicates. Do not number each line.

Example wildcards found in this collection that were created with ChatGPT:
- *dress*
- *lingerie*
- *fantasy*
- *scifi*
- *biome*
- *monster*
- *artist-scifi*
- *artist-horror*
- *scenario-romance*
- *scenario-fantasy*

## Information on Dynamic Prompts

Using Automatic1111's fork, you can install Dynamic Prompts from the Extensions tab (Available>Dynamic Prompts)

Install the Dynamic Prompts extension, then add all the wildcard text files found in this collection to this folder:

*\stable-diffusion-webui\extensions\sd-dynamic-prompts\wildcards*

Dynamic Prompts and how to use it can be found here: https://github.com/adieyal/sd-dynamic-prompts

If you're still unsure about what this does; basically it allows you to use wildcards to randomize keywords based on what is available inside the text file. An example prompt would be something like this:

a **`__adj-beauty__`** woman wearing a **`__dress__`** in **`__location__`**

The result would look something like this with each generation:

- a **beauteous** woman wearing a **minidress** in **Italy**
- a **stunning** woman wearing a **gown** in **France**
- a **lovely** woman wearing a **cocktail dress** in **Tokyo**

You can find even more wildcards to use at the link below, which include wildcards not found in this collection. Such as anime, danbooru tags, non-Western artists, etc.

https://rentry.org/sdgoldmine#wildcards

ChatGPT is free (for now) and you can sign up for it here: https://openai.com/blog/chatgpt/

There are Windows/Linux/macOS apps available here: https://prompts.chat/
