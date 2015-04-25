# Hearthstone-DB

A collection of all Hearthstone cards in a JSON format for all purposes.

Updated to GVG

[Download](https://www.dropbox.com/s/l6je7qjjqeogkiz/hs-images.zip) all images here.

## How to install

```
git clone git://github.com/pdyck/hearthstone-db.git
```

OR

```
bower install hearthstone-db
```

## JSON object structure

```
id: integer,
name: string,
description: string,
image_url: string,
hero: string
	- "druid"
	- "hunter"
	- "mage",
	- "paladin"
	- "priest"
	- "rogue"
	- "shaman"
	- "warlock"
	- "warrior",
category: string
	- "minion"
	- "spell"
	- "secret"
	- "weapon",
quality: string
	- "free"
	- "common"
	- "rare"
	- "epic"
	- "legendary",
race: string
	- "none"
	- "beast"
	- "demon"
	- "pirate"
	- "murloc"
	- "totem"
	- "mech",
set: string
	- "basic"
	- "expert"
	- "naxxramas"
	- "gvg",
mana: integer,
attack: integer,
health: integer,
collectible: boolean,
effect_list: array
	- effect: string
		- "battlecry"
		- "charge"
		- "deathrattle"
		- "divine_shield"
		- "enrage"
		- "secret"
		- "stealth"
		- "taunt"
		- "windfury"
	- extra: string
```

## Files

### all-cards.json

Contains all the cards used in Hearthstone(including promotional cards, tokens, hero powers etc.).

(Not up to date and won't be updated. Naxxramas heroes missing.)

### all-collectibles.json

Contains all the cards that would be shown in your collection.

## Have fun !
