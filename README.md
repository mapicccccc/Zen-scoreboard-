# ZenScoreboard 1.0.0

Standalone Paper plugin source for Paper 1.21.11 / Java 21. Players use `/scoreboard` (alias `/sb`) to toggle their own Player Name, Rank, Money, Kills, Deaths, Shards and Ping lines. Preferences are saved by UUID in `plugins/ZenScoreboard/config.yml`.

## Dependencies
- Paper 1.21.11
- PlaceholderAPI (recommended for LuckPerms prefix and Vault economy placeholders)
- Vault plus an economy plugin for money
- Your shards plugin, if you want a shard value. Edit `%shards_balance%` in `config.yml` to the placeholder your plugin provides.

## Build
Run `mvn package` in this folder with Java 21 and internet access. The output JAR will be `target/ZenScoreboard-1.0.0.jar`. Place that JAR in `plugins/` and restart the server. This environment could not download Paper/PlaceholderAPI dependencies, so a tested binary JAR could not be built here.
