JET/CF KNOWLEDGEBASE


1. WEATHER
2. PMC SPAWN CHANCE
3. INSURANCE RETURNS
4. FLEA MARKET PRICES
5. AI DIFFICULTY
6. DOGTAG OVERHAUL
7. BOT WAVE ALLOCATION
8. MAP LOOT
9. ACTIVATE INSURANCE IN 1.0.3
10. PMC WEIGHT

---

1. UPDATE WEATHER SETTINGS USING KOVAC WEATHER MOD & BETTER RNG MODS
	\server\db\weather\

2. PMC GAMEPLAY, 
	"spawnChance": 85,
	"usecChance": 50
	changed to 0
	\server\user\configs\gameplay.json
	** PROBABILITY RAISED BUT I CANT FIGURE OUT HOW MANY ACTUALLY SPAWNS 
	
3. INSURANCE RETURN SPEED
	min_return_hour: 24 to 5 
	\"server"\db\cacheBase\traders\5c0647fdd443bc2504c2d371\base.json
	 ** NOT CURRENTLY WORKING ON 1.0.3
	
4. FLEA MARKET PRICES 
	ragfairMultiplier: 1.5 to 15.5
	\server\user\configs\gameplay.json
	** JACKED UP THE PRICES
	
5. AI DIFFICULTY
	PUT BOT EXPERIENCE VALUE TO 1100
		
6. DOGTAG OVERHAUL
	names.json
	\server\db\bots\
				
7. MIN BOT ALLOCATION 
	\server\db\cacheBase
	"WAVE_COEF_LOW": 1.2, @ GLOBALS.JSON

8. MAP LOOT
	\server\user\configs\gameplay.json
		"locationloot": {
		"allowLootOverlay" : false,
		"bigmap": 1000,
		"develop": 30,
		"factory4_day": 100,
		"factory4_night": 100,
		"interchange": 2000,
		"laboratory": 1000,
		"rezervbase": 3000,
		"shoreline": 1000,
		"woods": 200,
		"hideout": 0,
		"lighthouse": 0,
		"privatearea": 0,
		"suburbs": 0,
		"tarkovstreets": 0,
		"terminal": 0,
		"town": 0
					
9. ACTIVATE INSURANCE IN 1.0.3
	/config/server.json
		LOOTPATCH = ENABLED
		
10. PMC WEIGHT CONTROL 
	\server\db\cacheBase\globals.json
	 "WalkOverweightLimits": {
                "x": 75,
                "y": 90,
                "z": 0
            },
            "BaseOverweightLimits": {
                "x": 75,
                "y": 90,
                "z": 0
            },
            "SprintOverweightLimits": {
                "x": 75,
                "y": 90,
                "z": 0
            },
            "WalkSpeedOverweightLimits": {
                "x": 75,
                "y": 90,
                "z": 0

