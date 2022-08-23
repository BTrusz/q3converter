== Description ==

This tool is intended to convert quake 3 assets (maps) into the FBX format so that it can be reused in various 3D model editors or engines that support the FBX (2018) format.
It has been tested in Unreal Engine and it works pretty well.

== Usage ==

q3converter_x64.exe -gamepath "Path to the Quake3 folder" "base game folder name" -outdir "Output directory" -file maps/map.bsp

You can specify more files by adding another -file parameter, or by specifying an asterik on the file name.

Example :

q3converter_x64 -gamepath "C:/Games/ioquake3" baseq3 -outdir "C:/Games/ioquake3/converted" -file "maps/q3dm17.bsp" -bsp_nosky

This command will convert q3dm17 from Quake 3, without including the sky from the BSP.

== More informations ==

You are free to use this tool convert assets from Quake 3 and Quake 3 based games, and do whatever you want with the converted assets as their ownership remain to the game and as the tool author is not responsible about the usage of these assets.
You cannot redistribute/resell this tool commerically however.

-Ludovic (author)