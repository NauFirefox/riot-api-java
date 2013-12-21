riot-api-java
=============

A Java client for the [Riot Games API](https://developer.riotgames.com/api/methods).

## Supported API Versions
|API|Version|
|---|-------|
|champion|1.1|
|game|1.2|
|league|2.2|
|stats|1.2|
|summoner|1.2|
|team|2.2|

## Usage

Retrieving a summoner by name:
```java
Riot client = new Riot("your-api-key", Region.NA);
Summoner summoner = client.summoner().getSummoner("SummonerName");
```

## Legal Jibber Jabber
This library isn’t endorsed by Riot Games and doesn’t reflect the views or opinions of Riot Games or anyone officially involved in producing or managing League of Legends. League of Legends and Riot Games are trademarks or registered trademarks of Riot Games, Inc. League of Legends © Riot Games, Inc.