# WindSeed
Some stuff for certain XLua framework;

# Scripts
Place your script to C:/Windy/*.luac, and /windy  <luac name without .luac> ;

For compiling scripts just take your .lua, drag to special luac.exe, rename and here you are
(there may be some issues, like some scripts won't work, create an issue then or write us then)

# Implementing (2 ways)
1) Take that files in sources, change it at correct paths in your grasscutter server and recompile it. (Current proto version is 3.6, you can always just download new one and change) and make sure you have those lines in PacketOpCodes.java:
```java
	public static final int WindSeedType1Notify = 23435;
	public static final int WindSeedType2Notify = 24656;
	public static final int WindSeedType3Notify = 22438;
```
2) Use any pre-made special server, for example [gingerPS](https://github.com/mintygingy/gingerps)
