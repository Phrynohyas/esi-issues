# XML to ESI Migration


## char

### AccountBalance

https://esi.tech.ccp.is/latest/#!/Wallet/get_characters_character_id_wallet

### AssetList

https://esi.tech.ccp.is/latest/#!/Assets/get_characters_character_id_assets

### Blueprints

https://esi.tech.ccp.is/latest/#!/Character/get_characters_character_id_blueprints

### Bookmarks

https://esi.tech.ccp.is/latest/#!/Bookmarks/get_characters_character_id_bookmarks

### CalendarEventAttendees

### CharacterSheet

**WIP** (roles, titles, faction_id)

https://esi.tech.ccp.is/latest/#!/Character/get_characters_character_id

https://esi.tech.ccp.is/latest/#!/Clones/get_characters_character_id_clones

https://esi.tech.ccp.is/dev/#!/Skills/get_characters_character_id_skills

https://esi.tech.ccp.is/latest/#!/Skills/get_characters_character_id_attributes

https://esi.tech.ccp.is/latest/#!/Clones/get_characters_character_id_implants

https://esi.tech.ccp.is/latest/#!/Character/get_characters_character_id_fatigue

### ChatChannels

https://esi.tech.ccp.is/latest/#!/Character/get_characters_character_id_chat_channels

### Clones

https://esi.tech.ccp.is/latest/#!/Character/get_characters_character_id

https://esi.tech.ccp.is/latest/#!/Skills/get_characters_character_id_attributes

https://esi.tech.ccp.is/latest/#!/Clones/get_characters_character_id_clones

https://esi.tech.ccp.is/latest/#!/Clones/get_characters_character_id_implants

https://esi.tech.ccp.is/latest/#!/Character/get_characters_character_id_fatigue

### ContactList

https://esi.tech.ccp.is/latest/#!/Contacts/get_characters_character_id_contacts

### ContactNotifications

### ContractBids

https://esi.tech.ccp.is/latest/#!/Contracts/get_characters_character_id_contracts_contract_id_bids

### ContractItems

https://esi.tech.ccp.is/latest/#!/Contracts/get_characters_character_id_contracts_contract_id_items

### Contracts

https://esi.tech.ccp.is/latest/#!/Contracts/get_characters_character_id_contracts

### FacWarStats

### IndustryJobs

https://esi.tech.ccp.is/latest/#!/Industry/get_characters_character_id_industry_jobs

### IndustryJobsHistory

https://esi.tech.ccp.is/latest/#!/Industry/get_characters_character_id_industry_jobs with `included_completed=true`

### KillLog

Deprecated in XML

### KillMails

https://esi.tech.ccp.is/latest/#!/Killmails/get_characters_character_id_killmails_recent

https://esi.tech.ccp.is/latest/#!/Killmails/get_killmails_killmail_id_killmail_hash

### Locations

### MailBodies

https://esi.tech.ccp.is/latest/#!/Mail/get_characters_character_id_mail_mail_id

### MailMessages

https://esi.tech.ccp.is/latest/#!/Mail/get_characters_character_id_mail

### MailingLists

https://esi.tech.ccp.is/latest/#!/Mail/get_characters_character_id_mail_lists

### MarketOrders

https://esi.tech.ccp.is/latest/#!/Market/get_characters_character_id_orders

### Medals

https://esi.tech.ccp.is/latest/#!/Character/get_characters_character_id_medals

### NotificationTexts

### Notifications

### PlanetaryColonies

https://esi.tech.ccp.is/latest/#/Planetary32Interaction

### PlanetaryLinks

https://esi.tech.ccp.is/latest/#/Planetary32Interaction

### PlanetaryPins

https://esi.tech.ccp.is/latest/#/Planetary32Interaction

### PlanetaryRoutes

https://esi.tech.ccp.is/latest/#/Planetary32Interaction

### Research

https://esi.tech.ccp.is/latest/#!/Character/get_characters_character_id_agents_research

### SkillInTraining

Not needed?

### SkillQueue

https://esi.tech.ccp.is/latest/#!/Skills/get_characters_character_id_skillqueue

### Skills

https://esi.tech.ccp.is/latest/#!/Skills/get_characters_character_id_skills

### Standings

https://esi.tech.ccp.is/latest/#!/Character/get_characters_character_id_standings

### UpcomingCalendarEvents

### WalletJournal

https://esi.tech.ccp.is/dev/#!/Wallet/get_characters_character_id_wallet_journal

### WalletTransactions

https://esi.tech.ccp.is/latest/#!/Wallet/get_characters_character_id_wallet_transactions


## corp

### AccountBalance

https://esi.tech.ccp.is/latest/#!/Wallet/get_corporations_corporation_id_wallets

### AssetList

### Blueprints

### Bookmarks

### ContactList

### ContainerLog

### ContractBids

### ContractItems

### Contracts

### CorporationSheet

### CustomsOffices

### FacWarStats

### Facilities

### IndustryJobs

### IndustryJobsHistory

### KillLog

Deprecated in XML

### KillMails

in staging

### Locations

### MarketOrders

### Medals

### MemberMedals

### MemberSecurity

### MemberSecurityLog

### MemberTracking

https://esi.tech.ccp.is/latest/?datasource=tranquility#!/Corporation/get_corporations_corporation_id_membertracking

### OutpostList

### OutpostServiceDetail

### Shareholders

### Standings

### StarbaseDetail

### StarbaseList

### Titles

### WalletJournal

in staging

### WalletTransactions


## eve

### AllianceList

https://esi.tech.ccp.is/latest/#!/Alliance/get_alliances

https://esi.tech.ccp.is/latest/#!/Alliance/get_alliances_alliance_id_corporations

### CertificateTree

Deprecated

### CharacterAffiliation

https://esi.tech.ccp.is/latest/#!/Character/post_characters_affiliation

### CharacterID

https://esi.tech.ccp.is/latest/#!/Search/get_search with `strict=true` and `categories=["character"]`

### CharacterInfo

https://esi.tech.ccp.is/latest/#!/Character/get_characters_character_id

https://esi.tech.ccp.is/latest/#!/Wallet/get_characters_character_id_wallets

https://esi.tech.ccp.is/latest/#!/Skills/get_characters_character_id_skills

https://esi.tech.ccp.is/latest/#!/Skills/get_characters_character_id_skillqueue

https://esi.tech.ccp.is/latest/#!/Location/get_characters_character_id_ship

https://esi.tech.ccp.is/latest/#!/Location/get_characters_character_id_location

https://esi.tech.ccp.is/latest/#!/Character/get_characters_character_id_corporationhistory

### CharacterName

https://esi.tech.ccp.is/latest/#!/Universe/post_universe_names

### ConquerableStationList

https://esi.tech.ccp.is/latest/#!/Sovereignty/get_sovereignty_structures

then filter outpost types into

https://esi.tech.ccp.is/latest/#!/Universe/get_universe_stations_station_id

### ErrorList

Not needed?

### FacWarStats

https://esi.tech.ccp.is/latest/#!/Faction32Warfare/get_fw_wars

https://esi.tech.ccp.is/latest/#!/Faction32Warfare/get_fw_stats

### FacWarTopStats

https://esi.tech.ccp.is/latest/#!/Faction32Warfare/get_fw_leaderboards

https://esi.tech.ccp.is/latest/#!/Faction32Warfare/get_fw_leaderboards_characters

https://esi.tech.ccp.is/latest/#!/Faction32Warfare/get_fw_leaderboards_corporations

### OwnerID

Not needed?

### RefTypes

All expanded in relevant endpoints

### SkillTree

https://esi.tech.ccp.is/latest/#!/Universe/get_universe_categories_category_id (category_id=16)

https://esi.tech.ccp.is/latest/#!/Universe/get_universe_groups_group_id

https://esi.tech.ccp.is/latest/#!/Universe/get_universe_types_type_id

https://esi.tech.ccp.is/latest/#!/Dogma/get_dogma_attributes_attribute_id

### TypeName

https://esi.tech.ccp.is/latest/#!/Universe/get_universe_types_type_id


## map

### FacWarSystems

https://esi.tech.ccp.is/latest/#!/Faction32Warfare/get_fw_systems

### Jumps

https://esi.tech.ccp.is/latest/#!/Universe/get_universe_system_jumps

### Kills

https://esi.tech.ccp.is/latest/#!/Universe/get_universe_system_kills

### Sovereignty

https://esi.tech.ccp.is/latest/#!/Sovereignty/get_sovereignty_map
