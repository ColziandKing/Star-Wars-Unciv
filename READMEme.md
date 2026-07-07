# Star-Wars-Unciv
A long time ago, in a galaxy far, far away. Coming to the Unciv galaxy, play as Mandalore, the Sith and much more.
In future updates, there maybe playable heroes as well. Made in Version 3.19.3

Shahristan literally means "city area" in Persian. It comes from the words shahr (city) and -stan (region or area). In historical Central Asian and Iranian urban planning, it refers to the main residential, commercial, and administrative area of a walled city.The Structure of an Historic Central Asian CityHistorical cities were usually divided into three distinct parts. Understanding this layout is like looking at a modern castle with a moat, a town square, and open-air markets.The Citadel (Kuhandiz): This is the high fortress at the heart or edge of the city. It was home to the governor or ruler and their royal guards.The Shahristan: This was the main walled town. It wrapped around the citadel. Inside, normal citizens lived and worked. It held government offices, bazaars, markets, and places of worship.The Suburbs (Rabad): This was the unwalled area outside the main city walls. It was used for farming, cemeteries, and caravanserais (roadside inns for travelers).Modern Locations Named ShahristanShahristan is also a geographical name for places in Central Asia:Shahristan, Tajikistan: A village and district (jamoat) in the Sughd region, located in the historical Ustrushana area.Shahristan District, Afghanistan: A district located in the mountainous Daykundi Province of central Afghanistan.To explore more about ancient city layouts, check out the ScienceDirect Historic Cities Overview. To learn about the Urdu and Hindi lexical meanings of the word, you can browse the Rekhta Dictionary Entry.If you'd like, let me know if you are researching:Historical urban planning in Central Asia?The geography and travel information for the Shahristan district in Afghanistan or Tajikistan?Or translations of other Persian city suffixes?

Rabad (Suburb): The outer settlement surrounding the city, often used for farming, storage, and travelers.

    {
        "name": "Humor",
        "era": "Modern era",
        "priorities": {
            "Neutral": 10,
            "Cultural": 0,
            "Diplomatic": 0,
            "Domination": 10,
            "Scientific": 0
        },
        "uniques": [
            "[+1 Happiness] per [2] population [in all cities]",
		  "Adopt [Comedic Journalism]",
                    "Get the leader title of [Actor/Actress [leaderName]]"
        ],
        "policies": [
            {
                "name": "Comedic Journalism",
                "uniques": [
                    "[+2 Happiness] from every [Broadcast Tower]"
                ],
                "row": 1,
                "column": 1
            },
            {
                "name": "Gelotology",
                "uniques": [
                    "[+1 Happiness] from every [Medical Lab]","[+1 Happiness] from every [Hospital]"
                ],
                "row": 1,
                "column": 3
            },
            {
                "name": "Kabarett",
                "uniques": [
                    "[+2 Culture, +1 Happiness] from every [Amphitheater]","[+2 Culture, +1 Happiness] from every [Theatre]"
                ],
                "row": 1,
                "column": 5
            },
            {
                "name": "Political Cartoon",
                "uniques": [
                    "[+1 Happiness] from all [Culture] buildings <when below [-10] [Happiness]>"
                ],
                "row": 2,
                "column": 1
            },
            {
                "name": "Political Satire",
                "uniques": [
                    "[+1 Happiness] per every [8] [Culture]"
                ],
                "row": 2,
                "column": 3
            },
            {
                "name": "Humor Complete",
                "uniques": [
                    "[+2 Happiness, +1 Culture] per [2] population [in all cities]"
                ]
            }
        ]
    },
	
ss
[
  {
		"name": "Mandalore",
		"leaderName": "Din Djarin",
		"adjective": ["Mandalorian"],
		"startBias": ["Grassland"],
  	        "preferredVictoryType": "Diplomatic",

		"startIntroPart1": "Yo, Mando. So now, your gonna rule over all your people of Mandalore? Ever since you defeated Moff Gideon and won the darksaber, Bo Katan Kryze now wants you lead the new Mandalore.",
		"startIntroPart2": "Mando, I mean Din Djarin. Are you up for the battle to restore Mandalore?",

		"declaringWar": "I could bring you in warm or I could bring you in cold?",
		"attacked": "Dang Ferrick!",
		"defeated":  "I guess this is the way.",
		"introduction":  "Greetings! I am a Mandalorian, you can hire us for work.",
		"neutralHello": "I'm on a bounty.",
		"hateHello": "You have the guts to meet me?!",
		"tradeRequest": "Hey, I think we can agree on this",

	        "outerColor": [192,192,192],
		"innerColor": [0,0,0],

		"uniqueName": "This is the Way",
		"uniques": ["Units fight as though they were at full strength even when damaged", "Great General provides double combat bonus", "[Great General] is earned [60]% faster"],
		"cities": ["Sundari", "Keldabe", "Enceri", "Norg Bral", "Clan Wren", "Kryze", "Bralsin", "Shuror"],
	},    
    {
      "name": "Sith Empire"
      "leader name": "Darth Bane"
      "adjective": ["Sith"],
		"startBias": ["Grassland"],
  	        "preferredVictoryType": "Domination",

		"startIntroPart1": "",
		"startIntroPart2": "",

		"declaringWar": "",
		"attacked": "",
		"defeated":  "",
		"introduction":  "",
		"neutralHello": "",
		"hateHello": "",
		"tradeRequest": "",

	        "outerColor": [192,192,192],
		"innerColor": [0,0,0],

		"uniqueName": "",
		"uniques": ["[+2 Production] from every [Pasture]", "Cities are razed [3] times as fast", "Starts with [Animal Husbandry]", "\"Borrows\" city names from other civilizations in the game", "+30% Strength when fighting City-State units and cities", "[+2] Movement <for [Mounted] units>"],
		"cities": ["Moraband", "Korriban", "Malachor", "Ziost", "Tython", "Byllura", "Dressel", "Umbara"],
    },
   {
     "name": "The Rebellion",
     "leader name": "Mon Mothma",
	   "adjective": ["Rebel"],
		"startBias": ["Grassland"],
  	        "preferredVictoryType": "Diplomatic",

		"startIntroPart1": "",
		"startIntroPart2": "",

		"declaringWar": "",
		"attacked": "",
		"defeated":  "",
		"introduction":  "",
		"neutralHello": "",
		"hateHello": "",
		"tradeRequest": "",

	        "outerColor": [192,192,192],
		"innerColor": [0,0,0],

		"uniqueName": "",
		"uniques": ["[+60]% [Food] from City-States","[+60]% [Culture] from City-States","[+60]% [Faith] from City-States","Military Units gifted from City-States start with [+20] XP", "[+60]% Golden Age length", "[+1] Movement <for [All] units> <during a Golden Age>", "[+20]% Strength <for [All] units> <during a Golden Age>"],
		"cities": ["Alderaan", "Yavin 4", "Hoth", "Endor", "Dantooine", "Corellia", "Chrellis", "Brigia", "Orion IV", "Thila", "Golrath", "Arbra"],
   },
{
      "name": "Galactic Empire",
      "leader name": "Emperor Palpatine",
	    "adjective": ["Imperial"],
		"startBias": ["Grassland"],
  	        "preferredVictoryType": "Domination",

		"startIntroPart1": "",
		"startIntroPart2": "",

		"declaringWar": "",
		"attacked": "",
		"defeated":  "",
		"introduction":  "",
		"neutralHello": "",
		"hateHello": "",
		"tradeRequest": "",

	        "outerColor": [192,192,192],
		"innerColor": [0,0,0],

		"uniqueName": "",
		"uniques": ["[+2 Production] from every [Strategic resource]","Double quantity of [Horses] produced",
			"Double quantity of [Iron] produced","Double quantity of [Uranium] produced", "[+30]% Production when constructing [All] wonders [in all cities]"],
		"cities": ["Corusant", "Kamino", "Death Star I", "Mustafar", "Death Star II", "Starkiller", "Nevarro", "Naboo", "Kashyyyk"],
     },
   {
      "name": "Chiss Ascendancy",
      "leader name": "Supreme Admiral Mitth'raw'nuruodo",
	    "adjective": ["Chiss"],
		"startBias": ["Grassland"],
  	        "preferredVictoryType": "Cultural",

		"startIntroPart1": "",
		"startIntroPart2": "",

		"declaringWar": "",
		"attacked": "",
		"defeated":  "",
		"introduction":  "",
		"neutralHello": "",
		"hateHello": "",
		"tradeRequest": "",

	        "outerColor": [192,192,192],
		"innerColor": [0,0,0],

		"uniqueName": "Chiss Syndicure",
		"uniques": ["Can spend Gold to annex or puppet a City-State that has been your ally for [10] turns.", "[-60]% City-State Influence degradation", "City-State Influence recovers at twice the normal rate", "City-State territory always counts as friendly territory"],
		"cities": ["Csilla", "Avidich", "Rentor", "Sarvchi", "Urchiv-ki", "Ar'alani", "Khel Voldez", "Hess'irolia'nuruodo", "Dazh Ranos", "Lunatta", "Sev'rance Tann", "Ath'en'terro"],
   },
{
      "name": "Crimson Dawn",
      "leader name": "Darth Maul",
	    "adjective": ["Sith"],
		"startBias": ["Grassland"],
  	        "preferredVictoryType": "Domination",

		"startIntroPart1": "",
		"startIntroPart2": "",

		"declaringWar": "",
		"attacked": "",
		"defeated":  "",
		"introduction":  "",
		"neutralHello": "",
		"hateHello": "",
		"tradeRequest": "",

	        "outerColor": [192,192,192],
		"innerColor": [0,0,0],

		"uniqueName": "Shadow Collective",
		"uniques": ["[+30]% Strength <when fighting units from a Civilization with more Cities than you>", "Retain [50]% of the happiness from a luxury after the last copy has been traded away"],
		"cities": ["First Light", "Dathomir", "Vermillion", "Cantonica", "Savareen", "Vandor", "Jekara"],
     },
    {
      "name": "Pyke Syndicate",
      "leader name": "Lom Pyke & Marg Krim",
	    "adjective": ["Sith"],
		"startBias": ["Hill"],
  	        "preferredVictoryType": "Domination",

		"startIntroPart1": "",
		"startIntroPart2": "",

		"declaringWar": "",
		"attacked": "",
		"defeated":  "",
		"introduction":  "",
		"neutralHello": "",
		"hateHello": "",
		"tradeRequest": "",

	        "outerColor": [192,192,192],
		"innerColor": [0,0,0],

		"uniqueName": "Spice Control",
		"uniques": [""],
		"cities": ["Oba Diah", "Kessel", "Mon Gazza", "Troiken", "Spice Triangle", "Roon", "Ryloth", "Spice Cartel"],
    },
   {
      "name": "New Rule Formation",
      "leader name": "Tierdon Emita & Alisa Klarc",
	    "adjective": ["Tier's & Alis'es"],
		"startBias": ["Oasis"],
  	        "preferredVictoryType": "Scientific",

		"startIntroPart1": "",
		"startIntroPart2": "",

		"declaringWar": "",
		"attacked": "",
		"defeated":  "",
		"introduction":  "",
		"neutralHello": "",
		"hateHello": "",
		"tradeRequest": "",

	        "outerColor": [192,192,192],
		"innerColor": [0,0,0],

		"uniqueName": "Spice Control",
		"uniques": [""],
		"cities": ["Bagong Kapital", "Tatooine", "Exegol", "Dagobah", "Geonosis", "Salecumi", "Cloud City"],
   },
]
