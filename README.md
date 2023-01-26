# sd-wildcards
**A collection of wildcards for Stable Diffusion + Dynamic Prompts extension**

Using the power of ChatGPT, I've created a number of wildcards to be used in Stable Diffusion by way of the Dynamic Prompts extension found in the Automatic1111 fork.

You can create your own list of wildcards by telling ChatGPT this:

> Give me a list of all the different types of dresses for women. Make sure you list each one on its own line, alphabetical order, in lowercase, in singular form, and that there are no duplicates. Do not number each line.

*or*

> Give me a list of the top 50 well-known actors. Make sure you list each one on its own line, alphabetical order, in lowercase, in singular form, and that there are no duplicates. Do not number each line.

Copy and paste the result into a text file with the name of your own choosing (or add to current ones.)

Example wildcards found in this collection that were created with ChatGPT:

- [*dress*](https://raw.githubusercontent.com/mattjaybe/sd-wildcards/main/wildcards/dress.txt)
- [*lingerie*](https://raw.githubusercontent.com/mattjaybe/sd-wildcards/main/wildcards/lingerie.txt)
- [*fantasy*](https://raw.githubusercontent.com/mattjaybe/sd-wildcards/main/wildcards/fantasy.txt)
- [*scifi*](https://raw.githubusercontent.com/mattjaybe/sd-wildcards/main/wildcards/scifi.txt)
- [*biome*](https://raw.githubusercontent.com/mattjaybe/sd-wildcards/main/wildcards/biome.txt)
- [*monster*](https://raw.githubusercontent.com/mattjaybe/sd-wildcards/main/wildcards/monster.txt)
- [*artist-scifi*](https://raw.githubusercontent.com/mattjaybe/sd-wildcards/main/wildcards/artist-scifi.txt)
- [*artist-horror*](https://raw.githubusercontent.com/mattjaybe/sd-wildcards/main/wildcards/artist-horror.txt)
- [*scenario-romance*](https://raw.githubusercontent.com/mattjaybe/sd-wildcards/main/wildcards/scenario-romance.txt)
- [*scenario-fantasy*](https://raw.githubusercontent.com/mattjaybe/sd-wildcards/main/wildcards/scenario-fantasy.txt)

![example](https://user-images.githubusercontent.com/110819465/214972021-6086eff9-fa7e-46db-8dcf-c07eaf345983.png)

## Installation

Install the Dynamic Prompts extension if you don't have it already, then clone this repo to this folder:

*\stable-diffusion-webui\extensions\sd-dynamic-prompts*

Or you can download individual text files and put them in this folder (if you don't see a wildcards folder, create one):

*\stable-diffusion-webui\extensions\sd-dynamic-prompts\wildcards*

## Information on [Dynamic Prompts](https://github.com/adieyal/sd-dynamic-prompts)

Using Automatic1111's fork, you can install Dynamic Prompts from the Extensions tab (Available>Dynamic Prompts)

If you're still unsure about what this does; basically it allows you to use wildcards to randomize keywords based on what is available inside the text file. An example prompt would be something like this:

a **`__adj-beauty__`** woman wearing a **`__dress__`** in **`__location__`**

The result would look something like this with each generation:

- a **beauteous** woman wearing a **minidress** in **Italy**
- a **stunning** woman wearing a **gown** in **France**
- a **lovely** woman wearing a **cocktail dress** in **Tokyo**

### Resources

You can find even more wildcards to use [at this link](https://rentry.org/sdgoldmine#wildcards), which include wildcards not found in this collection such as anime, danbooru tags, non-Western artists, etc.

ChatGPT is free (for now) and [you can sign up for it here](https://openai.com/blog/chatgpt/).

There are Windows/Linux/macOS apps available at [prompts.chat](https://prompts.chat/).

*Protip*: You can create a style with your favorite lines.  For example, I have a style called Camera Wildcards that injects this line to the prompt box: *`__camera__, __f-stop__, __iso-stop__, __focal-length__`*
