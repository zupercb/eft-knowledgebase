
SP-AKI CHANGELOG

R7
    SERVER::
    
      HARD CODE CHANGE IN SERVER, CUSTOM PMC NAMES
    
    BOTS::
    
      "Bots": {
        "pmcSpawn": {
            "usecChance": 25,
            "types": {
                "followerTest": 75,
                "bossTest": 75,
                "assault": 50,
                "pmcBot": 25
    

AKI NOTES::

    const enableRain = 0;
    const enableFog = 0;
    data.weather.cloud = -30;
    data.weather.wind_speed = 1;
    data.weather.wind_direction = this.getRandomInt("windDirection");
    data.weather.wind_gustiness = this.getRandomFloat("windGustiness");
    data.weather.rain = 0;
    data.weather.rain_intensity = 0;
    data.weather.fog = 0;
    data.weather.temp = 16;
    data.weather.pressure = 888;
  
  
