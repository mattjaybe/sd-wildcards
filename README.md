# sd-wildcards
**A collection of wildcards for Stable Diffusion + Dynamic Prompts extension**

Using ChatGPT, I've created a number of wildcards to be used in Stable Diffusion. Wildcards requires the Dynamic Prompts or Wildcards extension and works on Automatic1111, ComfyUI, Forge, SD.Next and more.

You can create your own list of wildcards by telling any AI service such as ChatGPT/Gemini/CoPilot/MetaAI this:

> Give me a list of all the different types of dresses for women. Make sure you list each one on its own line, alphabetical order, in lowercase, in singular form, and that there are no duplicates. Do not number each line.

*or*

> Give me a list of the top 50 well-known actors. Make sure you list each one on its own line, alphabetical order, in lowercase, in singular form, and that there are no duplicates. Do not number each line.

Copy and paste the result into a text file with the name of your own choosing (or add to current ones.)

Example wildcards found in this collection that were created with ChatGPT:

- [*dress*](https://raw.githubusercontent.com/mattjaybe/sd-wildcards/main/wildcards/dress.txt)
- [*nsfw-lingerie*](https://raw.githubusercontent.com/mattjaybe/sd-wildcards/main/wildcards/nsfw-lingerie.txt)
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

Install the Dynamic Prompts extension if you don't have it already, then clone this repo to this folder (scroll down to learn how to clone this repo):

`\stable-diffusion-webui\extensions\sd-dynamic-prompts`

Or you can download individual text files and put them in this folder (if you don't see a wildcards folder, create one):

`\stable-diffusion-webui\extensions\sd-dynamic-prompts\wildcards`

## Information on [Dynamic Prompts](https://github.com/adieyal/sd-dynamic-prompts)

Using Automatic1111's fork, you can install Dynamic Prompts from the Extensions tab (Available>Dynamic Prompts)

If you're still unsure about what this does; basically it allows you to use wildcards to randomize keywords based on what is available inside the text file. An example prompt would be something like this:

a **`__adj-beauty__`** woman wearing a **`__dress__`** in **`__location__`**

The result would look something like this with each generation:

- a **beauteous** woman wearing a **minidress** in **Italy**
- a **stunning** woman wearing a **gown** in **France**
- a **lovely** woman wearing a **cocktail dress** in **Tokyo**

### Resources

You can find even more wildcards to use at [CivitAI](https://civitai.com/models) (just filter for Wildcards)

AI services like ChatGPT, Gemini, CoPilot, and MetaAI are all free to use.

*Protip*: You can create a style with your favorite lines.  For example, I have a style called Camera Wildcards that injects this line to the prompt box: *`__camera__, __f-stop__, __iso-stop__, __focal-length__`*

### How To Clone This Repo

To clone a repo, you'll first need to have Git installed. If you're on Windows, [you can get it here](https://gitforwindows.org/).

Then, once Dynamic Prompts is installed, navigate to this folder using Windows Explorer:

`\stable-diffusion-webui\extensions\sd-dynamic-prompts`

In Windows Explorer's address bar at the top, type in `cmd`, and a command prompt will open.  Then put this in there:

`git clone https://github.com/mattjaybe/sd-wildcards.git`

It'll quickly download the wildcards folder into the proper place. You don't have to reboot Stable Diffusion or anything, it'll work as soon as you invoke a wildcard in your prompt.
