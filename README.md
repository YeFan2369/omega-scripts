这是个用来替换DayZServer\mpmissions\dayzOffline.chernarusplus\init.c文件的代码
不使用任何mod就可以在自己的服务器上使用管理员命令，例如传送、治疗、杀死玩家、刷DayZ中的一切物品等等
有时候各种mod之间会有不兼容的情况，所以这个文件从游戏源代码上加入了管理员的命令。

使用方法：
1.点右侧下载.zip文件
2.打开dayz服务器目录，找到DayZServer\mpmissions\dayzOffline.chernarusplus\init.c这个文件，用记事本/notepad++/VS code打开这个文件。
3.在文本编辑器中Ctrl+A全选所有的内容
4.Ctrl+C复制这个omega-scripts/admcmd.c中所有的内容
5.Ctrl+V将admcmd.c的所有内容复制到你自己服务器的init.c。
6.在文本编辑器中搜索1234567890，然后用你得steam ID64替换双引号中的内容（不要删除双引号！！！）steam ID64查询地址：https://steamid.io/lookup
7.保存
8.开启服务器。

进入游戏，连接服务器后，按T，输入#login 服务器的管理员密码（密码在serverDZ.cfg文件中第三行passwordAdmin = "";如果双引号间没有内容，那么添加到双引号之间的内容就是服务器管理员的密码 ）
现在，你可以在聊天窗口输入管理员命令了。
按T打开聊天窗口输入：
/spawn 物品名称  
~刷东西在脚边，在DayZServer\mpmissions\dayzOffline.chernarusplus\db\types.xml文件中有DayZ定义的所有物品名称

/inv 物品名称//////////////////////////////////////////////////////把东西刷到你的背包里

/gun 枪名////////////////////////////////////////刷一把能满配吃鸡的枪到你手上，枪名：upm/cz75/mak/cz61/mp5/svd/mp133/mosin/m4/fal/akm/sks/izh18/m70/cz527/fnx

/tp 地点//////////////////////////////////////////传送到预设好的地点，地点名：nwaf/nwaf_tents/tisy/vmc/pmc/tmc/

/strip 玩家名     ////////////////////////////////////////清空玩家身上的所有东西

/slap 玩家名    /////////////////////////////////////////管理员传送到玩家身边

/topos 坐标x 坐标y 玩家名字      ///////////////////////////把玩家传送到坐标地点

/goto 玩家名      ////////////////////////////////同上

/allgoto                 //////////////////////////////把所有玩家传送到一个玩家旁边

/here 玩家名             /////////////////////把玩家传送到管理员身边

/allhere                 //////////////////////////////////////把所有玩家传送到管理员身边周围开会

/time 小时 分钟      /////////////////////////////////////改变服务器的当前时间

/day         ////////////////////////////////////变成白天

/night        ////////////////////////////////////变成晚上

/kill 玩家名    //////////////////////////////////// 杀掉玩家

/killall        ////////////////////////////////////集体死亡

/heal 玩家名        ////////////////////////////////////治疗玩家

/freecam        ////////////////////////////////////自由镜头

/offroad        ////////////////////////////////////刷辆毛子的拉达（滑稽）

/sedan        ////////////////////////////////////轿车

/refuel        ////////////////////////////////////给身边的车加油水箱加满水

/////////////////////////////////////////////////////////////////////////////////////////////////////
This is a code to replace the DayZServer\mpmissions\dayzOffline.chernarusplus\init.c file.
You can use admin commands on your own server without using any mods, such as transferring, healing, killing players, spawn everything in DayZ, etc.
Sometimes there are incompatibilities between various mods, so this file adds administrator commands from the game source code.

Instructions:
1. Click on the right side to download the .zip file
2. Open the dayz server directory, find the DayZServer\mpmissions\dayzOffline.chernarusplus\init.c file, and open this file with Notepad/notepad++/VS code.
3. Select all the contents in Ctrl+A in the text editor.
4.Ctrl+C to copy all the contents of this omega-scripts/admcmd.c
5.Ctrl+V paste all the contents of admcmd.c to your own server's init.c.
6. Search for 1234567890 in the text editor, then replace the contents of the double quotes with your steam ID64 (do not remove the double quotes!!!) steam ID64 query address: https://steamid.io/lookup
7. Save
8. Run server.

Enter the game, connect to the server, press T, enter the administrator password use the #login adminpassword(adminpassword in the third line of the serverDZ.cfg file passwordAdmin = ""; if there is no content between the double quotes, then add the content between the double quotes Is the password of the server administrator)
Now you can enter the admin command in the chat window.
Press T to open the chat window and enter:
/spawn itemname        ////////////////////////////////////spawn item at the your position, all the item names defined by DayZ in the DayZServer\mpmissions\dayzOffline.chernarusplus\db\types.xml file

/inv itemname        ////////////////////////////////////spawn item  into your inventory

/gun gunname        ////////////////////////////////////give a weapon that can be winner winner chicken dinner to your hand XD. Gun name: upm/cz75/mak/cz61/mp5/svd/mp133/mosin/m4/fal/akm/sks/izh18/m70/cz527/fnx

/tp location        ////////////////////////////////////Transfer to the preset location, location name: nwaf/nwaf_tents/tisy/vmc/pmc/tmc/

/strip playername        ////////////////////////////////////Empty everything on the player

/slap playername        ////////////////////////////////////sent Administrator to the player

/topos coordinateX coordinateY playername        ////////////////////////////////////teleport the player to the coordinate location

/goto playername        ////////////////////////////////////Same as above

/allgoto playername        ////////////////////////////////////Transfer all players to a player

/here playername        ////////////////////////////////////Transfer the player to the administrator

/allhere        ////////////////////////////////////Transfer all players to the meeting around the administrator

/time hours minutes        ////////////////////////////////////Change the current time of the server

/day        ////////////////////////////////////Become daytime

/night        ////////////////////////////////////Become night

/kill playername        ////////////////////////////////////kill the player

/killall        ////////////////////////////////////collective death

/heal playername        ////////////////////////////////////Treat players

/freecam        ////////////////////////////////////free lens

/offroad        ////////////////////////////////////Lada (LOL) spawn the soviet Lada

/sedan        ////////////////////////////////////car

/refuel        ////////////////////////////////////Fill the radiator adn tank of your car around you
