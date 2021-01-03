Folder Structure of JustEmuTarkov Server

db
      assort -> contains traders assortiment as barter_scheme, items for sell, loyal_level_items, questassort
      bots -> contains bots and all of its data such as difficulty settings, health, inventory data, appearance, experience, names
      cacheBase -> contains a base files which shouldnt be changed in order to keep a consistancy(i will advice to use tampermodload to edit those in memory of server)
      customization -> contains suits and all variants of body types (head, arms, torso, legs)
      dialogues -> not much used but it contains a respond dialogues for traders
      hideout -> contains every data for hideout
      items -> contains item nodes and in that item nodes there are items (consider item nodes as categories for items)
      locales -> contains all localization for all languages (by default only 4 en/ru/fr/ge)
      locations -> contains maps with its loot also
      profile -> contains profiles to choose from on registry
      templates -> contains categories/templates for items and quests
      weather -> weather files as json
      version -> this file should store database compatiblility version of the game
      res -> contains static data such as fonts, css(style files), images, bundles
      src -> contains scripts avaliable for users to dig into
      callbacks ->
      cache -> do cache of specific things in server
      load -> load classes initializators (literally nothing to change here)
      receive -> How to respond on "string" received data (external comunication)
      respond -> How to respond in "string" responded data (internal comunication)
      classes -> contains main classes of functions whic hsuply data if something is broken its propably here
      response -> folder itself contains static responses like /client/game/config whic is saved as client.game.config.js
      dynamic -> contains all dynamicly changing responses

user

      cache -> its a place where cache is storaged
      certs -> place where ssl certificates are storaged
      configs -> storage server config files such as accounts(login & passwords), gameplay, mods, server
      events -> sheulded events to fire (most likely not used)
      logs -> This is a place where logs are storaged
      mods -> This is a place where mods are storaged (only folders from here are loaded)
      profiles -> User created profiles

Server.exe
