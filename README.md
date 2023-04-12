# WindSeed
Some stuff for certain XLua framework;

# Scripts
Place your script to C:/Windy/*.luac, and /windy  <luac name without .luac> ;

For compiling scripts just take your .lua file, drag and drop it to luac.exe (Lua compiler), rename it to anything if you need to.
(There may be some issues, for example some scripts may not work. If you found a certain Lua script that you think doesn't work correctly, create an issue including the Lua name, or write to us in the Discord server.)

# Implementing (2 ways)

1) Take that files in sources, change it at correct paths in your grasscutter server and recompile it. (Current proto version is 3.6, you can always just download new one and change) and make sure you have those lines in PacketOpCodes.java:
```java
	public static final int WindSeedType1Notify = 23435;
	public static final int WindSeedType2Notify = 24656;
	public static final int WindSeedType3Notify = 22438;
```
2) Use any pre-made special server, for example [gingerPS](https://github.com/mintygingy/gingerps)
1) Take the files in the source code, change file locations to correct paths in your Grasscutter server and recompile it. (Current proto version is 3.5, you can always just download new one and change)
2) Use any pre-made special server, for example: [GingerPS](https://github.com/mintygingy/gingerps)

