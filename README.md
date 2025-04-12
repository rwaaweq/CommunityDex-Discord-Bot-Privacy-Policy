---

# CommunityDex Discord Bot | Privacy Policy

------------------------------------------------------------------------------------------------------------------------------------------------------------------  
**The following document explains what data is collected by CommunityDex.**

## Things to Note

- "Application" or "Discord Application" refers to the Discord bot user. Its associated owners and the servers it has access to.  
- "Data" refers to data stored by an individual instance, including personal data.  
- "Bot" or "Instance" refers to the copy of the code running the Discord application, with its own data.  
- "Collectible" refers to any object that is meant to be collected, in this case those are flags, a virtual sort of currency.  
- "Application Owner" refers to the owner of the Discord application, meaning the one with any form of access to the application's authentication method and data belonging to the instance.  
- "CommunityDex Staff Team" or "Staff Team" refers to the owner of the Discord application and the users they may choose to be part of the staff team. You may find a list of these users on the [Official CommunityDex Discord Server](https://discord.gg/k5ZQx4n3tQ).

## Open Source

The code of CommunityDex is available and taken from https://github.com/laggron42/BallsDex-DiscordBot. A copy of the licence can be found there.

**The instance is guaranteed to be running an exact copy of the code made open source.** The version may not be the latest available, but no local changes will be made. This may change, but users will be notified in the [Official CommunityDex Discord Server](https://discord.gg/k5ZQx4n3tQ) about any changes.

You may check the source code and see how the data is managed, in addition to the following policy.

## What data is collected?

CommunityDex **only** collects the following data from Discord:  
- **User IDs** | Used to identify you inside our database  
- **Server (or Guild) IDs** | Used to store settings necessary to the bot's operation  
- **Channel IDs** | Used to know in which channel the collectibles should spawn  

Additionally, the following data created by CommunityDex is stored and used:  
- **The list of collectibles owned by a user of the service**  
- **A history of trades done on collectibles, including the users that once owned the said collectible but do not anymore**

## How is the data stored?

All data is stored on a PostgreSQL server, running on a Docker Desktop Virtual Machine hosted by *Italianhistorian*, the owner of CommunityDex.

Interaction between the bot and the database server is exclusively local using [Tortoise ORM](https://github.com/tortoise/tortoise-orm).

## Access to the data

The only person who is allowed to access the data is the application owner.

An application owner may interact with the bot and the administrator interface. Only *Italianhistorian* has direct access to the hosting machine.

The CommunityDex staff team **does not have access to the data.**

**The data will never be made publicly available.** Access to the data must and will be secured accordingly.

## Your rights

You may request a copy or the deletion of your personal data held by the application by contacting the application owner. This can be done by joining our [Official CommunityDex Discord Server](https://discord.gg/k5ZQx4n3tQ) and DMing *Italianhistorian*. Sending a request directly to *Italianhistorian* is also allowed.

------------------------------------------------------------------------------------------------------------------------------------------------------------------  
`Privacy Policy was last updated: 12/04/2025 | Created on: 07/05/2024 (7th May, 2024)`

---
