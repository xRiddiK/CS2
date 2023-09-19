## CS2 Config Shit

### Video Settings
#### Step 1:
Go to "Steam\userdata\<YOUR ID>\730\local\cfg".

Create a backup of your old "cs2_video.txt" (just rename it to "cs2_video.txt.old" or smth) (!!!DONT DELETE IT!!!).
#### Step 2:
Download my "cs2_video.txt" or copy the content of it into a new "cs2_video.txt".

inside of the "cs2_video.txt" change:
```
"DeviceID"		"<YOUR ID>"
```
to your "DeviceID" on line 5, you can find your "DeviceID" in your old "cs2_video.txt". (and thats why you dont delete your old .cfg).
#### Step 3:
Change it to your desired Resolution.

on line 10 & 11 you can find the part for your resolution, Width & Height.

for me it is 1280x960 on 4:3.

down here is an example for 1280x960 on 4:3.
```
"setting.defaultres"		"1280"
"setting.defaultresheight"		"960"
```
you can change it to any resolution you want tho.

before you switch from 4:3 to 16:9 or vice versa (or any other aspect ratio) you have to change the ratio in CS2 itself before you apply the new video.cfg.

also you can play a bit with those settings on line 27 & 28
```
"setting.r_character_decal_resolution"		"128"
"setting.r_texture_stream_max_resolution"		"128"
```
those settings are for the "quality" of the models etc. on "128" everything lowkey looks like sh*t (but fck it, fps over everything)

but if you dont like the full sh*t look just multiply those numbers by 2

for example "128 > 256 > 512" and so on.

### Language File
just as in CS:GO, i also use an own language file in CS2 (just cuz, why not right?).

in case you want to use my language file, just download it and put it into "\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\resource".

after you placed the language file there add .
```
-language xriddik
```
to your CS:GO/CS2 start options in steam

you can change anything in that file to your own wishing

you also can rename the file to anything, for example "csgo_monkeylanguage.txt"

just remember to also change the name in ur start options then!










Credits:

[Afromnazareth](https://twitter.com/Afromnazareth). For the hardly optimized video.cfg
