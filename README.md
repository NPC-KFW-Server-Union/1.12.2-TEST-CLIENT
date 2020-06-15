1.12.2-TEST-CLIENT
--------------------
1.12.2測試客戶端  

# 简述：  
由于1.7.10版本的服务端(cauldron, ...)具有很多设计问题，大多数服务器也早已升级至新版本，
故昔日邦联未立前，NPCCRAFT就有升级到高版本的准备的准备。但是由於那时一定数量的
MOD、插件不支持新版本的MC，故不得不放弃了。  
然而时间到了2019年中叶，情势发生了大幅变化——  
  1) 绝大部分MOD与插件制作者放弃对1.7.10的维护，纷纷奔向1.12.2。1.12.2成为了继1.7.10的下一个大版本。
  2) 由于MOJANG的DMCA协议，cauldron服务端不再继续开发，1.7.10是cauldron的最后版本。不光是cauldron服务端停止开发，而是凡是以修改
  官方服务器而二次发行的服务端都吃了官司(例：水桶服务器今天已经封闭了直接下载的链接：https://bukkit.gamepedia.com/FAQ#Where_can_I_get_it.3F )，
  他们现在已经身处困境。而不修改官服，而是以MOD形式给服务器增加插件功能的forgesponge服务端正火。又因接口设计良好，插件开发容易、BUG少、稳定性强、
  MOD与插件合而为一，MOD与插件发生兼容问题的可能性低、社区活跃，有问题就会即时修复，正在步步超越cauldron，成为开服的首选。
  今日绝大多数人都建议使用sponge来代替cauldron(https://forums.spongepowered.org/t/1-12-2-vs-1-7-10-spongeforge-vs-cauldron/34715/3 ).
  
所以，升级的计划必须重新考虑。我们的建议和计划是：  
  1) 升级到1.12.2
  2) 抛弃cauldron，拥抱sponge
  
<font size=5>(注：仅代表NPCCRAFT方。是案尚未经邦联整体表决通过)</font>


乃搭建1.12.2测试服务端，制作测试客户端。为以后做准备。
<br/><br/><br/>


需要注意的地方有：
  1) cauldron、bukkit所使用的插件API都是spigot API，故从不支持MOD的bukkit换用cauldron，服务器中所有插件不需要动。
  但sponge所使用的插件API是sponge API。这导致sponge的生态世界与bukkit的生态世界完全不一样。使用sponge做服务器，需要更换几乎所有的插件(除了少数
  即支持spigot API的又支持sponge API的插件)，所有的管理员需要重新学习新的插件的使用方法。
  2) 在sponge的观念中，没有「MOD」与 「插件」之分。MOD与插件皆是plugin，只不过一个用了forge API，一个用了sponge API。

  
