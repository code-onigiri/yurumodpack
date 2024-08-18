# ルビコン3modpack(yurumodpack)
読まなきゃ殴り込みに行きます(嘘です)

## 手動導入必須mod
- NanoLaser ([NanoLaser](https://web.archive.org/web/20190522122003/https://dl.dropboxusercontent.com/s/odiwor0armqlpm7/NanoLaser-1.7.10-8.2.3-1.2.2.jar))
- 竹mod ([竹](https://www.dropbox.com/s/sc5vf0imhlrmoba/Bamboo-2.6.8.5.jar?dl=1))
- HyperDimensionalBag ([HyperDimensionalBag](https://web.archive.org/web/20190522122003/https://dl.dropboxusercontent.com/s/juc61fzxvjnrdnt/HyperDimensionalBag-1.2c-forMC1.7.jar))
- 似蛭 ([Nihil](https://web.archive.org/web/20190715140008/https://forum.minecraftuser.jp/download/file.php?id=61937))
- 鞘無し ([SlashBlade-Kirisaya](https://web.archive.org/web/20190715123647/http://forum.minecraftuser.jp/download/file.php?id=57176))
- 神威 ([SlashBlade-Kamuy](https://web.archive.org/web/20190715123647/http://forum.minecraftuser.jp/download/file.php?id=55969))
- 木刀 ([toyako](https://web.archive.org/web/20190715123647/http://forum.minecraftuser.jp/download/file.php?id=48477))
- 錬金術師の太刀 ([Slashblade-Laemmle](https://web.archive.org/web/20190715123647/http://forum.minecraftuser.jp/download/file.php?id=60590))
- SlashArts ([SlashArts](https://web.archive.org/web/20190715123647/http://forum.minecraftuser.jp/download/file.php?id=52353))
- SpawnChecker ([SpawnChecker](https://www.dropbox.com/scl/fo/ldhq4k4ctsxt9d4d436o0/AE6nAWWTFJMXIHsd2hnADkM/SpawnChecker/Minecraft_1.7.x/1.7.10?preview=SpawnChecker-2.1.4.128.jar&rlkey=emhq3an4gnpa8e52gtvmmmdx3&subfolder_nav_tracking=1&st=0ktwphxr&dl=0))
- AdditionalEnchantments ([AdditionalEnchantments](https://web.archive.org/web/20190715132818/https://dl.dropboxusercontent.com/s/6k0hhj4jg7ck43s/AdditionalEnchantments-1.7.10-1.2.11.jar))
- DigBedrock ([DigBedrock](https://web.archive.org/web/20190715185020/https://dl.dropboxusercontent.com/s/ycrw8wetebaazt0/DigBedrock-1.7.10-1.5.3.jar))
- MapleTree ([MapleTree](https://web.archive.org/web/20171113044952/http://forum.minecraftuser.jp/download/file.php?id=71626))
- SextiarySector2 ([SextiarySector2](https://web.archive.org/web/20190715200711/https://forum.minecraftuser.jp/download/file.php?id=65308))
- 

## lwjgl3ifyについて
この環境ではlwjgl3ifyが必須です。
導入はlwjgl3ifyのgithubが下記の文章をお読みください。([github](https://github.com/GTNewHorizons/lwjgl3ify))

### MultiMC系列(PrismMCなども)
まず[ここ](https://github.com/GTNewHorizons/lwjgl3ify/releases/tag/2.1.2)の"lwjgl3ify-2.1.2-multimc.zip"と"lwjgl3ify-2.1.2.jar"をダウンロードしてください
そして"lwjgl3ify-2.1.2-multimc.zip"を展開して、.minecraftが**ある**フォルダ(.minecraftの中ではない)に中身を入れます。そしてmodsに"lwjgl3ify-2.1.2.jar"を入れたら完成です
(MultiMCの場合はjava引数に
```
-Dfile.encoding=UTF-8 -Djava.system.class.loader=com.gtnewhorizons.retrofuturabootstrap.RfbSystemClassLoader -Djava.security.manager=allow --add-opens java.base/java.io=ALL-UNNAMED --add-opens java.base/java.lang.invoke=ALL-UNNAMED --add-opens java.base/java.lang.ref=ALL-UNNAMED --add-opens java.base/java.lang.reflect=ALL-UNNAMED --add-opens java.base/java.lang=ALL-UNNAMED --add-opens java.base/java.net.spi=ALL-UNNAMED --add-opens java.base/java.net=ALL-UNNAMED --add-opens java.base/java.nio.channels=ALL-UNNAMED --add-opens java.base/java.nio.charset=ALL-UNNAMED --add-opens java.base/java.nio.file=ALL-UNNAMED --add-opens java.base/java.nio=ALL-UNNAMED --add-opens java.base/java.text=ALL-UNNAMED --add-opens java.base/java.time.chrono=ALL-UNNAMED --add-opens java.base/java.time.format=ALL-UNNAMED --add-opens java.base/java.time.temporal=ALL-UNNAMED --add-opens java.base/java.time.zone=ALL-UNNAMED --add-opens java.base/java.time=ALL-UNNAMED --add-opens java.base/java.util.concurrent.atomics=ALL-UNNAMED --add-opens java.base/java.util.concurrent.locks=ALL-UNNAMED --add-opens java.base/java.util.jar=ALL-UNNAMED --add-opens java.base/java.util.zip=ALL-UNNAMED --add-opens java.base/java.util=ALL-UNNAMED --add-opens java.base/jdk.internal.loader=ALL-UNNAMED --add-opens java.base/jdk.internal.misc=ALL-UNNAMED --add-opens java.base/jdk.internal.ref=ALL-UNNAMED --add-opens java.base/jdk.internal.reflect=ALL-UNNAMED --add-opens java.base/sun.nio.ch=ALL-UNNAMED --add-opens java.desktop/com.sun.imageio.plugins.png=ALL-UNNAMED --add-opens java.desktop/sun.awt.image=ALL-UNNAMED --add-opens java.desktop/sun.awt=ALL-UNNAMED --add-opens java.sql.rowset/javax.sql.rowset.serial=ALL-UNNAMED --add-opens jdk.dynalink/jdk.dynalink.beans=ALL-UNNAMED --add-opens jdk.naming.dns/com.sun.jndi.dns=ALL-UNNAMED,java.naming
```
を入れてください)

### curseforgeランチャーなどのその他のランチャー
lwjgl3ify公式では手段が用意されていません。
Prismlauncherを入れるのが良いでしょう。