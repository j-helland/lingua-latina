# The Third Triumvirate
This repo primarily supports the wiki for cool stuff that we find / do as we journey through learning Latin.
It is intended to be collaboratively built.

You can use the [Wiki](https://github.com/j-helland/lingua-latina/wiki) section of this repo to browse the pages quickly.
However, the preferred method for both viewing, editing, and adding pages is to clone the wiki and use [Obsidian](https://obsidian.md) as your primary viewer so that you can make full use of the graph view feature.

The reason I chose to host this wiki through github is so that we can easily resolve cases where multiple people edit the same page at once. 

## Contributing to the wiki
If you're in a pinch, you can just use Github's browser interface.
However please consider using Obsidian so you can check out its graph view feature.
It's pretty cool.

## Cloning the Wiki & Using Obsidian
#### First steps
- (_Optional_) Familiarize yourself with [Markdown syntax](https://www.markdownguide.org/cheat-sheet/) if you aren't already familiar with it. All wiki pages are written in Markdown, which is a very simple text formatting language. 
- (_Optional_) If you're inexperienced with git, I recommend installing the [Github Desktop client](https://desktop.github.com), as this will save you some headache in setting up your credentials to push to this repo. 
If you're an experienced git user already, feel free to go your own way.
- (_Optional_) Install the Obsidian-git plugin, which will make your life much easier by automating a bunch of git operations (branching, merging, etc.). 
  - In Obsidian, click the settings button <img width="22" alt="Screen Shot 2022-04-15 at 12 14 04 PM" src="https://user-images.githubusercontent.com/11012803/163594568-6f50b4a4-f2e0-4dea-b4de-0619a7006196.png">. Go to `Community plugins` and turn off `Safe mode`. Then click `Browse` under `Community plugins`, search for `Obsidian Git`, and click `Install`. 
  Make sure that you then click `Enable` once the installation is complete.
  (_NOTE: I haven't tried this on Windows, you might have to do some extra steps to install git first, idk._)

#### Environment setup
- **Clone the wiki**. Open a terminal and run `git clone https://github.com/j-helland/lingua-latina.wiki.git` in a directory of your choice.
  - Unfortunately, you have to use a terminal here. [Github Desktop still can't clone wikis](https://github.com/desktop/desktop/issues/3839) due to a 4-year-old bug that's still sitting in the backlog.
- You can now **link the cloned repo to Github Desktop** by clicking `Add -> Add Existing Repository... -> Choose...` and then browsing to the newly created directory from the previous step.
- (_Optional_)
- In Obsidian click the `Open another vault` button <img width="25" alt="Screen Shot 2022-04-15 at 12 10 45 PM" src="https://user-images.githubusercontent.com/11012803/163594216-2f0e27b5-eb53-4b2d-827a-5a347ed67f9c.png">. Browse to the repo directory.

#### Using Obsidian Git to push wiki contributions
- Open the Command palette and type `git`. 
You'll see a bunch of options pop up.
The one you want is `Obsidian Git: Create backup` which will automatically commit your changes with an automated commit message and attempt to push the changes. 
If the push step fails due to credential issues, don't worry. 
You can use Github Desktop to perform the push without the headache of creating a personal access token and shit.
  - NOTE: You can check the hotkey combo for the command palette by clicking `Settings` <img width="22" alt="Screen Shot 2022-04-15 at 12 14 04 PM" src="https://user-images.githubusercontent.com/11012803/163594568-6f50b4a4-f2e0-4dea-b4de-0619a7006196.png">, `Hotkeys`, and then searching for `Command palette`. 
