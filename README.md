# Benndot's HG-Engine Edits

## About HG-Engine
 HG-Engine is a community-made upgrade to the battle engine in Pokemon HeartGold. It gives the DS an updated roster of Pokemon, abilities, moves and more to bring the 2010 DS game in line with the features of more recent releases in the series. 

It also offers a massive amount of customizability, allowing users to tweak just about every facet of gameplay to their liking. 

## My Edits (Overview)

Beyond all the base features that HG-Engine provides out of the box, I have made changes to the following aspects of the game.

-Pokemon Base Stats (The distribution of stats that species of pokemon has, determining it's battle style and difficulty of use)

-Wild Encounters (which wild pokemon can be encountered and where)

-Level up learnsets (The selection of moves that a species of Pokemon learns and when they learn them)

-Evolutionary methods (How different species of Pokemon evolve and into which species they evolve when they do.)

-Pokemart inventories (Which items are available for purchase in the pokemarts that are spread throughout the game's world and at what point in the player's progress do they become available.)

-Other Pokemon data attributes (Various changes to species size and weights, and also a few changes to species' available abilities)

-Various battle move statistical rebalances 

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

In my version of the game, just about every native evolutionary line in the Pokedex of the first 2 generations can be encountered in the wild. A few select extras from other regions/generations have also been added where I thought appropriate. I really didn't go overboard with it, however.

I tried to thoughtfully spread Pokemon throughout the world. Lots of bugs and grass types in Ilex Forest, More rugged kinds of Pokemon in mountainous areas. I'm pretty happy with how consistent and organized I kept it. There's a nice variety of options wherever you go. More rare 1-2% encounters and a greater variety of Pokemon per route in general due to the density of making all main dex Pokemon availabe. 

While this information is reliably true for ground encounters, I was a bit more haphazard early on when writing in water encounters. It's possible that there are non-native Pokemon species in certain areas that I missed in editing. It shouldn't be much, if anything, however. 

### Non-native Species Added to Johto

-Carbink
-Stunky 
-Mawile
-Sableye
-Surskit
-Wingull
-Relicanth
-Snover
-Togedemaru (via Pikachu evolution)
-Drampa (via Dunsparse evolution)
-Drifloon
-Spoink

## Level Up Learnsets (My changes)

I've gone through and edited many Pokemon. A large number of the Pokemon species intended to be present in the game have received extensive updates to their learnsets. However, many still haven't been touched and need to be overhauled (as of October 2024). Few to no Pokemon in the game should possess any moves that aren't currently implemented in HG-engine. 

### The Pokemon that I have reworked heavily (Incomplete list): 

-Pikachu (including Togedemaru)
-Octillery 
-Sunkern
-Sunflora
-Noctowl
-Ledian
-Granbull
-Bellsprout
-Surskit
-Masquerain
-Tauros
-Miltank
-Diglett
-Swinub
-Sneasel
-Ninetails 
-Arcanine
-Qwilfish
-Stuntank
-Bellsprout
-Oddish
-Pelipper
-Psyduck
-Dewgong
-Grumpig
-Drifloon
-Mawile
-Sableye
-Eevee line 

*Pokemon in the same evolutionary line mentioned separately have diverging movesets from one another

## Evolutions and evolution methods (My changes)

I intend to add a few extra evolution options to existing Pokemon for the fun of it. Ones that make sense in my head, due to similarities between apparently unrelated Pokemon. 

I also intend to change some evolution methods and requirements. 

These changes have been made (partially) in a previous project. They need to be transferred over, expanded upon and completed. 

### Evolutionary Line Changes

Ekans: Branching evolutions to Arbok and Seviper. (implemented)

Geodude: Branching evolutions to Graveler and Carkol (implemented)

Dunsparse: Special condition evoluton into Drampa (implemented)

Cubone: Branching evolution with Marowak and Kangaskhan (implemented, mostly)

Eeveelutions: Umbreon and Espeon were changed. The former now needs to be given a Dusk Stone, while the latter now needs to be given a Dawn Stone. (I'd like to add time of day requirements, but they don't exist in the engine's default methods so that won't be done for the time being.)

Gengar: Haunter evolves via Dusk Stone. 

Pikachu: Added a 'metal coat' induced evolution into a reworked version of Togedemaru

Trade Evolutions: Most have been converted to stone or held item evolutions. The ones that were previous held item trades are now more or less all held item trades.

### Special Evoluton Conditions Additional Level Requirement (Implemented, mostly!!)

I think all evo methods should have some minimum level condition. 

Since there is none by default for friendship, stone, move knowledge, and party requirement evolutions by default, I have added them in myself. For friendship, I kept it low to 10 for the sake of baby Pokemon. I may create a separate category for them at some point. For the vast majority of the rest I've added a minimum level of 20. 

I'd like to create a higher tier version of each category with a higher level requirement (probably level 35) to cover the handful of Pokemon for which level 20 is too early to reasonably be fully evolved. 

## Pokemart stock & value changes 

-Added heart scales to normal pokemart inventories (For easy move tutor usage)
-Added items that I use for evolutionary purposes to department store inventories. (twisted spoons, charcoal, dragon scale, metal coat)
-Revives, Ethers and elixirs are much cheaper
-Full Heals are slightly cheaper

### Party Requirements (Partially implemented)

There are several more evolution requirements that involve having the right Pokemon in your party upon level up. 

Along with the classic example of Mantine & Remoraid, now added to the list is Koffing (Koffing), Diglett (Diglett), Magnemite (Magnemite), Cubone (Kangaskhan), Slowpoke (Shellder).

In the future, I'd like to figure out how to make more than 1 Pokemon requirements as an evo method (ex: Requiring 2 magnemites in party in order to evolve)

## Where to find my edits 

All the files I've edited and tweaked exist inside of this repository and can be referenced for further details. In this section I'll be giving you the exact paths and files needed in order to find the information. 

(Encounters) For which Pokemon can be encountered where: armips/data/encounters.s 

(Base Stats, Abilities, Sizes) For changes that I've made to Pokemon's base stats, size data and abilities: armips/data/mondata.s

(Learnsets) For changes that I've made to the lists of moves that each Pokemon can learn as they level up: armips/data/levelupdata.s

(Evolution Data) For changes that I've made to Pokemon's evolutions and how they evolve: armips/data/evodata.s

(Evolution Methods) For changes that I've made to how the methods used to evolve a Pokemon work: src/individual/GetMonEvolutionInternal.c

(Move Data) For changes that I've made to the stats and details of the battle moves themselves: armips/data/moves.s

(Mart Inventories) For changes to what is carried in PokeMarts and department stores: armips/asm/custom/mart_items.s+

(Item Data) For changes to the price of items and what they do: data/itemdata/itemdata.c

## TODO

-Work on more species learnsets that I haven't fully constructed
-Create new usable Evo Methods 
-Edit more HG Engine encounter data (Mostly done, some caves could use tweaking. Surfing is only slightly edited, kanto is pretty much entirely unedited)
-Custom trainer editing?

## Ideas

-Amp ability jigglypuff line? 


## Base HG-Engine Features:
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

*A more comprehensive list of features + a roadmap can be found by visiting the [hg-engine wiki](https://github.com/BluRosie/hg-engine/wiki).  

## Disclaimer
 This repository and its assets are a [community endeavor](CREDITS.md).  By its nature, using it and subsequently profiting off of it is profiting on the backs of all of our work, all of which is intended to be used to further hobbies and for everyone to have fun.  You have my blessing to use code and assets from this repository as you please as long as there is *no money involved*, including optional donations through whichever platform to play your hack.  The creations that stem from this repository must be freely accessible and not hidden at all behind any paywall, including those that prompt the player to pay optionally (Ko-Fi's style comes to mind here). 

# Credits
* [**Bubble (Base Mega Code)**][TEMPLATE]
* [**Skeli (FR template)**][CFRU]
* [**PokeDiamond decompilation projects (nitrogfx, msgenc)**][diamond]
* [**Mikelan98, Nomura (ARM9 Expansion Subroutine )**][ARM9]
* Rafael Vuijk (ndstool)

Contributors: Aero, BluRose, Brioche, Charliexox, DavveDP, Dog-Broad, Drayano, Koekenpann, kumakuma1, lhearachel, maxchristy, Mixone, mozzydippers, PandaPanda-Panda, TixoRebel, TurtleIsaac, YGlitzer

[AdAstra](https://github.com/AdAstra-LD/) - `debugsyscall` implementation

Adcroc1 - helping significantly with sprite formatting

BagBoy - dex entries

Barro - swav2swar

Bubble791 - strong basis for where this came from

Chritchy - sprite translation errors bug fix

Dr. Seuss, Zeak6464 - [Pokémon cries from gen 8](https://www.pokecommunity.com/showthread.php?t=432636)

FroggestSpirit - [SDATTool](https://github.com/froggestspirit/SDATTool)

HamsterSkull, wolfang62, nintendoplz, Kyle-Dove, 2and2makes5, PokeGirl4Ever, Fernandojl, Silver-Skie, TyranitarDark, Getsuei-H, Milomilotic11, Kyt66, kdiamo11, ChocoSrawloid, StyleDude, Gallanty, Gizamimi-Pichu, Kid1513, princess-phoenix, Ezerart, DarkusShadow, Anarlaurendil, Lasse00, Boonzeet on deviantart - Overworlds

KazoWAR - BTX-Editor (which is pngtobtx0)

Kingcom - [armips](https://github.com/Kingcom/armips)

MaMe and maple - a lot of mega sprites touched up

Mikelan98 - initial graphics compilation, BDHCAM routine

RH-Hideout Team - cries from gen 9

Shy - platinum Battle BG Insertion tutorial

Smogon Sprite Project, TraviS, LennyBitao, MyMarshlands, DarkusShadow, CarmaNekko, kiriaura, Gnomowladny, Krune, n-kin, JaegerLucciano23, joshr691, Jefelin, MultiDiegoDani, onigin_pixelart, Prodigal96, zerudez, leparagon, arinoelle, diegotoon20, gardow, greyenna, conyjams, kingofthe-x-roads, RayquazaFlygon, metalflygon08 on DeviantArt, and MaMe, maple, Layell, SelenaFF, Sopita Yorita, zlolxd - Pokémon Sprites

WesleyFG and [The Sounds Resource](https://www.sounds-resource.com/3ds/pokemonsunmoon/) - [Pokémon cries from gens 5 through 7](https://www.pokecommunity.com/showthread.php?t=390701)

XLuma - helping get this buildable initially

Game Freak - amazing Pokémon games from way back when

[MONEXPAND]: https://github.com/BluRosie/hgss-monexpansion
[CFRU]: https://github.com/Skeli789/Complete-Fire-Red-Upgrade
[G5T]: https://github.com/CodenamePU/Gen5Tools
[ARM9]: https://pokehacking.com/tutorials/ramexpansion/
[diamond]:https://github.com/pret/pokediamond
[TEMPLATE]: https://github.com/Bubble791/Pokemon-Heart-Gold-Engine
[LUNOS]: https://www.pokecommunity.com/showthread.php?t=432351
