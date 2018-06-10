# About
TNE offers conversion from 33 other economy plugins through the Conversion Module. The process has been revamped from previous
versions of TNE to be more user-friendly.

# How To Use
To use, simply install the Conversion Module, and run once. After the first run
a file called convert.yml will appear to allow you to configure your old plugin's
database settings. After configuring, if your old plugin used flatfile, SQLite, or H2 please
place the file in your /plugins/TheNewEconomy directory or set `Conversion.File` in
convert.yml to `../\<old plugin directory\>/\<file\>`. After this, simply start your server back up, or
reload your conversion module and type the command /convert <old plugin name>. Your old
balances will be exported to extracted.yml, after this process has finished, which may take
some time depending on your database size, simply use the command /tne restore.

# Supported
The official list of plugins supported for conversion.

- AdvancedEconomy
- BasicEconomy
- BConomy
- BEconomy
- Blings
- BOSEconomy
- CraftConomy
- DevCoinSystem
- EasyCoins
- ECEconomy
- EconomyAPI
- EcoPlugin
- EcoSystem
- EssentialsEco
- FeatherEconomy
- FeConomy
- GemsEconomy
- iConomy
- Meep
- Meller
- MineCoin
- MineCoinsYML
- MineConomy
- MinetopiaEconomy
- MoConomy
- RealEconomy
- SaveEconomy
- SimpleConomy
- SimplisticEconomy
- SQLConomy
- SwiftEconomy
- TokensEconomy
- TownyEco
- XConomy