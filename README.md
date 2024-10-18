# Benndot's HG-Engine Edits

## About HG-Engine
 HG-Engine is a community-made upgrade to the battle engine in Pokemon HeartGold. It gives the DS an updated roster of Pokemon, abilities, moves and more to bring the 2010 DS game in line with the features of more recent releases in the series. 

It also offers a massive amount of customizability, allowing users to tweak just about every facet of gameplay to their liking. 

## My Edits

Beyond all the base features that HG-Engine provides out of the box, I have made changes to the following aspects of the game.

-Pokemon Base Stats (The distribution of stats that species of pokemon has, determining it's battle style and difficulty of use)
-Wild Encounters (which wild pokemon can be encountered and where)
-Level up learnsets (The selection of moves that a species of Pokemon learns and when they learn them)
-Evolutionary methods (How different species of Pokemon evolve and into which species they evolve when they do.)
-Pokemart inventories (Which items are available for purchase in the pokemarts that are spread throughout the game's world and at what point in the player's progress do they become available.)
-Other Pokemon data attributes (Various changes to species size and weights, and also a few changes to species' available abilities)

## Base Stats 

I have gone through and completely reworked just about Pokemon in the game, though Pokemon outside of the main obtainable roster have not been edited. 

The changes made aren't generally too dramatic. I've tailored these new stats to my general impression of the Pokemon species' biology and abilities. Unlike some other reworks, my goal here wasn't really to rework weak Pokemon to be competitively viable and increase parity. 

Some examples of trends in my stat tweak reasoning:

-Gimmick Pokemon are made less gimmicky. 
-Shelled / Exoskeleton-ed Pokemon have buffed defenses in many cases. 
-Blubbery Pokemon tend to be less physically defensive, though sometimes more specially defensive. 

In general I think I've made Pokemon on average a little bit tankier, and a little bit less hard hitting, though there are plenty of exceptions. 

It's by no means a hard science but I put a nice amount of thought into it and I think most of the results are balanced and interesting. 

## Encounters (My changes)

In my version of the game, just about every native evolutionary line in the Pokedex of the first 2 generations can be encountered in the wild. A few select extras have also been added where I thought appropriate. I really didn't go overboard with it, however.

I tried to thoughtfully spread Pokemon throughout the world. Lots of bugs and grass types in Ilex Forest, More rugged kinds of Pokemon in mountainous areas. I'm pretty happy with how consistent and organized I kept it. There's a nice variety of options wherever you go. More rare 1-2% encounters and a greater variety of Pokemon per route in general due to the density of making all main dex Pokemon availabe. 

## Level Up Learnsets 

I've gone through and edited many Pokemon. For the most part, I've only removed moves that have not been implemented (as of October 2024). A good handful have gotten a partial of full-on moveset rework though. 

The Pokemon that I have reworked: 
-Sunkern
-Sunflora
-Noctowl
-Ledian

## Evolutions and evolution methods (My changes, NOT YET IMPLEMENTED)

I intend to add a few extra evolution options to existing Pokemon for the fun of it. Ones that make sense in my head, due to similarities between apparently unrelated Pokemon. 

I also intend to change the evolution

These changes have been made (partially) in a previous project. They need to be transferred over, expanded upon and completed. 

Ekans: Branching evolutions to Arbok and Seviper. 

Geodude: Branching evolutions to Graveler and Carkol

Eevee: Simplified stone evolutions for Leafeon, Glaceon and Sylveon. 

Dunsparse: Special condition evoluton into Drampa

Cubone: Branching evolution with Marowak and Kangaskhan? 

### Disclaimer
 This repository and its assets are a [community endeavor](CREDITS.md).  By its nature, using it and subsequently profiting off of it is profiting on the backs of all of our work, all of which is intended to be used to further hobbies and for everyone to have fun.  You have my blessing to use code and assets from this repository as you please as long as there is *no money involved*, including optional donations through whichever platform to play your hack.  The creations that stem from this repository must be freely accessible and not hidden at all behind any paywall, including those that prompt the player to pay optionally (Ko-Fi's style comes to mind here).  The [Credits](CREDITS.md) should also be replicated in your hack's repository and/or the post to your hack--we all sit on the shoulders of giants here.

## Table of Contents
- [Features](#features)
- [Setup Instructions (Linux with apt)](#setup-instructions-linux-with-apt)
- [Setup Instructions (macOS)](#setup-instructions-macos)
- [Setup Instructions (Windows on WSL)](#setup-instructions-windows-on-wsl)
- [Setup Instructions (Windows on MSYS2)](#setup-instructions-windows-on-msys2)
- [Further Setup Instructions](#further-setup-instructions-all-platforms-continued-from-individual-sections)
- [Setup Instructions (Docker)](#setup-instructions-docker)
- [Build Instructions](#build-instructions-all-platforms-continued-from-further-setup-instructions)
- [Credits](#credits)


## Features:
* Dex Expansion (through Gen 6 almost entirely implemented)
* Ability Expansion (through Gen 6 almost entirely implemented)
* Move Expansion with future generation moves
* Item Expansion with future generation items
* Mega Evolutions + Primal Reversions
* Much More Customizable Trainers
* Fairy Type
* Hidden Abilities
* Updated Effects for Existing [Moves](https://github.com/users/BluRosie/projects/3) and [Abilities](https://github.com/users/BluRosie/projects/2)
* 30 PC Boxes

*A more comprehensive list of features + a roadmap can be found by visiting the [hg-engine wiki](https://github.com/BluRosie/hg-engine/wiki).  Please read this README and the Wiki thoroughly before asking questions.*

# Credits
* [**Bubble (Base Mega Code)**][TEMPLATE]
* [**Skeli (FR template)**][CFRU]
* [**PokeDiamond decompilation projects (nitrogfx, msgenc)**][diamond]
* [**Mikelan98, Nomura (ARM9 Expansion Subroutine )**][ARM9]
* Rafael Vuijk (ndstool)

[MONEXPAND]: https://github.com/BluRosie/hgss-monexpansion
[CFRU]: https://github.com/Skeli789/Complete-Fire-Red-Upgrade
[G5T]: https://github.com/CodenamePU/Gen5Tools
[ARM9]: https://pokehacking.com/tutorials/ramexpansion/
[diamond]:https://github.com/pret/pokediamond
[TEMPLATE]: https://github.com/Bubble791/Pokemon-Heart-Gold-Engine
[LUNOS]: https://www.pokecommunity.com/showthread.php?t=432351
