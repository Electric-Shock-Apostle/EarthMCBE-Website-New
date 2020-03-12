这是所有Factions命令的列表。 稍后将对它们分别进行详细说明。
/f ?,h,help [page=1] get help  
/f list [page=1] list all factions  
/f f,faction [faction=you] show faction information  
/f player [player=you] show player information  
/f status [page=1] [faction=you] [sort=time] show status  
/f join <faction> join faction  
/f leave leave your faction  
/f warp use warps  
/f warp go <warp> [faction=you] go to a warp  
/f warp list [faction=you] [page=1] list warps  
/f warp add,create <name> [faction=you] add new warp  
/f warp remove <warp> [faction=you] remove warp  
/f map [on/off=once] show territory map  
/f create,new <name> create new faction  
/f name <new name> [faction=you] set faction name  
/f description <desc> change faction description  
/f motd [new=read] faction motd  
/f sethome [faction=you] set the faction home  
/f unsethome [faction=you] unset faction home  
/f invite manage invites  
/f kick kick player from faction  
/f title [title=none] set player title  
/f rank set <player><rank> set rank  
/f rank show <player> show rank  
/f rank list [page=1][faction=you] list ranks  
/f rank edit edit ranks  
/f rank edit create <name> <priority> [prefix=none] [faction=you] create rank  
/f rank edit delete <rank> [faction=you] delete rank  
/f rank edit name <rank> <new name> [faction=you] set rank name  
/f rank edit prefix <rank> <new prefix> [faction=you] set rank prefix  
/f rank edit priority <rank> <new priority> [faction=you] set rank priority  
/f money manage faction money  
/f money balance [faction=you] show faction money  
/f money deposit <amount> [faction=you] deposit to faction  
/f money withdraw <amount> [faction=you] withdraw from faction  
/f money ff <amount> <faction> <faction> transfer f –> f  
/f money fp <amount> <faction> <player> transfer f –> p  
/f money pf <amount> <player> <faction> transfer p –> f  
/f top <Topcategory> [page=1] show faction top  
/f seeChunk,sc [active=toggle] see the chunk you stand in  
/f seeChunkOld,sco see the chunk you stand in  
/f territorytitles,tt [on|off=toggle] toggle territory titles  
/f claim claim faction territory  
/f unclaim unclaim faction territory  
/f access manage access  
/f relation manage faction relations  
/f perm change faction permissions  
/f flag manage faction flags  
/f unstuck teleport to nearest wilderness  
/f override,admin [on/off=flip] enable override mode  
/f disband [faction=you] disband faction  
/f powerBoost manage powerboost  
/f setpower,sp set power  
/f config edit config  
/f clean clean the factions database  
/f v,version display plugin version  
###### 总览  
**本节介绍以下命令：**  
/f Factions basecommand  
/f ?,h,help [page=1] get help  
/f list [page=1] list all factions  
/f top <Topcategory> [page=1] show faction top  
/f f,faction [faction=you] show faction information  
/f player [player=you] show player information  
/f status [page=1] [faction=you] [sort=time] show status  
/f join <faction> join faction  
/f leave leave your faction  
/f map [on/off=once] show territory map  
**键入/ f时，将获得所有与Faction相关的命令的列表。 键入/f ? 2将带您进入第二页。 列出派系是通过/ f list完成的，这里也可以有几页。 如果您不仅需要列表，还可以通过键入/f top来查看几个类别中的所有顶级派系。 如果您随后选择一个派系并想了解有关该派系的一些基本信息，则可以键入/f f [faction]，如果未指定派系，则将获取有关您自己派系的信息。 同样，/f player [player]会为您提供有关玩家的信息，如果未指定任何玩家，则将与您有关。 要获取有关派系中玩家的信息，请键入/f status [page] [faction]，此处可能需要浏览多个页面，因此，如果要查看过去的第1页，请指定一页，然后指定要查看派系的派系 那不是你的。**  
**当派系邀请您加入时，请键入/f join <faction>。 当您想离开时，键入/f leave。 您只能是一个派系的成员。**  
**您可以通过输入/f map来查看谁拥有您周围的土地。**  
###### 传输
**本节介绍以下命令：**  
/f warp use warps  
/f warp go <warp> [faction=you] go to a warp  
/f warp list [faction=you] [page=1] list warps  
/f warp add,create <name> [faction=you] add new warp  
/f warp remove <warp> [faction=you] remove warp  
**一个派系可能会有传输点。 要查看您的派系有哪些传输点，请键入/f warp list。 要转到一种传输类型，请输入/f warp <warp>。 每个获得许可（稍后将介绍权限）的人都可以使用所有派系的传输点。 如果您具有“setwarp”权限，则可以使用/f warp add和/f warp remove为派系添加和删除传输点。 服务器管理员设置的最大传输点数。**  
###### 新建派系
**本节介绍以下命令：**  
/f create,new <name> create new faction  
/f name <new name> [faction=you] set faction name  
/f description <desc> change faction description  
/f motd [new=read] faction motd  
/f sethome [faction=you] set the faction home  
/f unsethome [faction=you] unset faction home  
**通过键入/f create <名称>创建派系。 如果以后要给它起一个新名称，请键入/f name <新名称>。 您可以使用/f desc <desc>更改公共派系描述。 您可以通过输入/f motd查看您的派系的每日消息，也可以通过输入/f motd <new motd>进行更改。 您甚至可以在motd中使用颜色。**  
**您可以通过站立/f sethome设置家的位置来设置派系的家。 您可以通过再次执行/f sethome来设置新主目录，或者可以决定没有主目录并执行/f unsethome（不推荐）。**  
###### 成员管理 
**本节介绍以下命令：**  
/f invite manage invites  
/f invite list [page=1] [faction=you] list invited players  
/f invite add <player> invite player  
/f invite remove <player/all> revoke an invite  
/f kick kick player from faction  
/f title <player> [title=none] set player title  
**当您希望某人加入您的派系时，您可以/f invite <玩家>，将该玩家添加到受邀玩家列表中。 当您想知道邀请谁时，请执行/f invite list。 然后，您可能想从该列表中删除某人并撤消他们的邀请，您可以通过键入/f invite remove <玩家>来执行此操作，如果您想完全清除列表，则可以执行/f invite remove all**  
**如果有人在您的派系行为不正常，您可以使用/f kick <玩家> 来踢出他们。**  
**如果您的派系中的某人很特别，并且应该获得标题，则可以执行/f title <玩家> [标题]。 如果要删除其标题，只需将标题留空并执行/f title <玩家>。 您可以在标题中使用颜色。**  
###### 等级
**所有派别都有等级。 您从领导者（400），官员（300），成员（200）和新兵（100）开始，但是您可以根据需要添加和删除。 排名还可以有一个前缀，该前缀将在任何玩家名称之前（前缀也可以有颜色）。 所有等级的优先级均在名称后的括号中显示。**  
**具有最高优先级的等级被认为是“领导等级”（可以重命名），只有一个人可以拥有该等级。 每当有新成员加入派系时，他们将被分配具有最低优先级的等级。 优先级很重要，因为它们确定谁可以做什么。 例如：您不能踢出与您自己等级相同或更高的人。 因此，如果您既有军官又有共同领导者，那么不要担心军官会踢共同领导者或共同领导者会互相踢对方。 他们不能。 改变职级，职称和其他类似的事情也是一样。**  

**现在是以下命令：**  
/f rank manage ranks  
/f rank set <player><rank> set rank  
/f rank show <player> show rank  
/f rank list [page=1][faction=you] list ranks  
/f rank edit edit ranks  
/f rank edit create <name> <priority> [prefix=none] create rank  
/f rank edit delete <rank> [faction=you] delete rank  
/f rank edit name <rank> <new name> set rank name  
/f rank edit prefix <rank> <new prefix> set rank prefix  
/f rank edit priority <rank> <new priority> set rank priority  
**要确定一个派系的排名，请执行/f rank list [页数] [派系名]，该列表在您的派系中默认为第1页。 然后将某人的等级设置为所列的等级之一，请设置/f rank set <player> <rank>。 如果要检查某人的排名，请/f rank show <player>.**  
**现在一切都很好，但是您想要更多的控制权。 您想要更多的排名。 然后转到/f rank edit。 该命令只能由派系负责人使用。 在这里，您可以通过/f rank edit create <name> <priority> [prefix]创建一个新等级，名称和优先级都是必需的，并且对于该派系必须是唯一的，前缀是可选的，并且不必唯一。 您可以使用不言自明的命令来编辑名称，优先级或前缀 /f rank edit name <rank> <new name>， /f rank edit prefix <rank> <new prefix>和/f rank edit priority <rank> <new priority>。 首先输入等级名称，然后输入名称，优先级或前缀的新值。 最后，如果/f rank delete <rank>完成了一个等级，则可以删除该等级。**  
###### 钱
**本节介绍以下命令：**  
/f money manage faction money  
/f money balance [faction=you] show faction money  
/f money deposit <amount> [faction=you] deposit to faction  
/f money withdraw <amount> [faction=you] withdraw from faction  
/f money ff <amount> <faction> <faction> transfer f –> f  
/f money fp <amount> <faction> <player> transfer f –> p  
/f money pf <amount> <player> <faction> transfer p –> f  
**如果您有一个支持派系的经济插件，那么所有派系都可以赚钱。 为了显示派系拥有的资金，/f money balance [faction=you]。 要将钱存入派系帐户，请执行/f money balance [faction=you]，取回它们请执行/f money withdraw <amount> [faction=you]。 要将钱从派系转移到非玩家，请执行/f money fp <amount> <faction> <player>，并在两个派系之间进行转账/f money ff <amount> <faction> <faction>。 如果您是管理员，还可以使用 /f money pf <amount> <player> <faction>将钱从另一个玩家转移到特定派系。**  
###### 领土
**本节介绍以下命令：**  
/f seeChunk,sc [active=toggle] see the chunk you stand in  
/f territorytitles,tt [on|off=toggle] toggle territory titles  
/f claim claim faction territory  
/f claim one [faction=you] claim a single chunk  
/f claim auto [faction=you] claim as you walk around  
/f claim fill [faction=you] claim by filling  
/f claim square [radius=1] [faction=you] claim by square and radius  
/f claim circle [radius=1] [faction=you] claim by circle and radius  
/f claim all <all|map> <faction> claim all faction land  
/f unclaim unclaim faction territory  
/f unclaim one unclaim a single chunk  
/f unclaim auto unclaim as you walk around  
/f unclaim fill unclaim by filling  
/f unclaim square [radius=1] unclaim by square and radius  
/f unclaim circle[radius=1] unclaim by circle and radius  
/f unclaim all <all|map><faction>unclaim all faction land  
**派系土地是基于大块土地。 块是16×16的块区域，可以由一个派系主张，也可以完全没有派系主张。 要查看块的边界，请输入/f sc，停止则再输入/f sc。 然后，您可能想为自己争取一些土地。 要仅声明您站着的块，请执行 /f claim one，要在任何地方进行声明，请执行/f claim auto（然后再次键入以禁用）。 如果您在声明时已经绕圈走了，并且想要声明圆圈内的所有内容（或正方形，五边形或其他任何东西），请执行 /f claim fill。 如果您更愿意声明自己的立场，并且您的所有周围环境都声明/f claim square [radius]或/f claim circle [radius]声明在指定块半径内的所有内容。 您只能根据自己的权限声明尽可能多的块，因此，如果要声明新内容，则可能必须取消声明旧内容。 要做到这一点，只需/f unclaim，然后使用用于声明的任何命令进行处理。**  
###### 访问
**本节介绍以下命令：**  
/f access manage access  
/f access view vies access  
/f access player <player> [yes/no=toggle] grant player access  
/f access faction <faction> [yes/no=toggle] grant player access  
**Sometimes you might want to give someone access to a specific chunk rather than all of you faction. That is the point of of access. With access you can give either a player or a faction the ability to build, open chests and interact in one specific chunk.
To see who has access in the chunk you are standing in type /f access view. To grant a player access in the chunk you are standing in type /f access player <playerName> yes and when you decide to take it away type /f access player <playerName> no. To grant a faction access in the chunk you are standing in type /f access faction <factionName> yes and when you decide to take it away type /f access faction <factionName> no.**
###### Relations
**This section covers the following commands:**  
/f relation manage faction relations  
/f relation set <faction> <relation> set relation wish to another faction  
/f relation list [page=1] [faction=you] [relations=all] list all factions with certain relation  
/f relation wishes [page=1] [faction=you] list the relation wishes  
**Two factions can have a relation between them. Per default the relation is neutral, but it can be changed to Enemy, Truce or Ally. The relation between the two factions is equal to the lowest wished relation between them. So if one wishes to be enemies and the other wishes to be truced, the enemy wish will prevail. If the Faction that wishes to be enemies then changes their wish to truce they will become truce because now both Factions wish to be truced.**  

| Wishes | Enemy | Neutral | Truce | Ally |
| --- | --- | --- | --- | --- |
|Enemy|Enemy|Enemy|Enemy|Enemy|
|Neutral|Enemy|Neutral|Neutral|Neutral|
|Truce|Enemy|Neutral|Truce|Truce|
|Ally|Enemy|Neutral|Truce|Ally|

**To set your wished to another faction type /f relation set <faction> <relation>. If you wished to be enemies you are now enemies, if you wish to be truced or allied the other faction must respond by setting the same relation wish.
To then see your relations type /f relation list and if you need to see the next page type /f relation list 2, to only see allies type /f relation list ally to see for another faction type /f relation list <factionName>. Now mix and match page, relation type and faction, to see the third page of enemies for the Faction Kalmar, type /f faction relation list 3 kalmar enemy.
If you would rather want to see relation wishes. That is not your current relations, but the relations you wish to have, type /f relation wishes.**
###### Permissions
**In this section the following commands are covered:**  
/f perm change faction permissions  
/f perm list [page=1] list perms  
/f perm show <perm>[faction=you ]show who has perm  
/f perm view <rank/rel/player/faction> [faction=you] view perms given to  
/f perm viewall <rank/rel/player/faction> [faction=you] view all perms held by  
/f perm set <perm> <rank/rel/player/faction> <yes/no> [faction=you] set perms  
**A faction has a list of permissions, that is who can do what. A permission can be given to either a rank, a. player, a relation, everyone in another faction or a specific rank in another faction.
To list all permissions type /f perm list. To show who has a specific perm type /f perm show <perm> per default permissions are only granted to ranks within your faction and a few perms are given to allies, but if you have changed it that will be displayed here.
If you want to know what permissions are specifically given to someone do /f perm view <someone>. If you want to check a rank, let’s say Officer, do /f perm view Officer to check allies do /f perm view ally, to check a player Madus you would do /f perm view Madus, to check a specific faction, let’s say Kalmar, do /f perm view Kalmar and to check permissions specifically given to officers of Kalmar do /f perm view Kalmar-Officer. This allows a high degree of granularity. Do you have a super-duper-best-friend ally, that is more important than your other allies you can give permissions to everyone in just that Faction, or even just people with a specific rank in a faction. Do you have a co-leader you can give permissions just to her (or you could create a co-leader rank) or you can give permissions to special people even when they are not a part of the faction.
If you want to check all permissions a player has you can do /f perm viewall <playerName>. This is all the permissions they have, not just the ones granted to them specifically. This is all permissions they have because of faction membership, rank, relation to your faction and the ones given to them specifically.
To set perms do /f perm set <perm> <someone> <yes/no>, you have to specify the perm (build, door, etc.) who has to get the perm and a yes/no to give it or take it away. The someone can be a rank, relation, individual player or a specific faction, just as explained earlier..**
###### Flags
**In this section the following commands are covered:**  
/f flag manage faction flags  
/f flag list [page=1] list flags  
/f flag show [faction=you] [page=1] show flags  
/f flag set <flag> <yes/no> [faction=you] set flags  
**Flags are on/off attributes of most factions. To list them do /f flag list, to show whether they are enabled or disabled for a specific faction do /f flag show <factionName> and to set them do /f flag set <flag> <yes/no>. Per default you can change whether your faction is open (which means everyone can join even without invitation), whether monsters can spawn in the territory and whether animals can spawn in the territory).**