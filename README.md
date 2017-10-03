# Milandra - English Translation ROM Hacking Project

## What is Milandra?
	
Milandra is a little known roguelike for the Super Famicom developed by Tomcat System, and published by ASCII in 1997. The game's unique feature, is the follower/party system. You can recruit allies, and issue them commands.

## Why translate it?
It's a roguelike and I want to beat it.

## How far am I?
I've created a table for all the Kana, English characters, and symbols. I've hacked together an English name input for the game, seen below.

![English input in Milandra](/images/name_entry.png)

I'm also including an IPS patch for this hack. It should work for ROM's of the game with MD5 hash

`62f86bcc861d9c0ff3a2eba00208602e`

I've included the table file in this repository.

## What do I need help with?
Translation, for one, but I'm not there yet. I need to create a Hex lookup
table for the Kanji. I've done a few, but it's so inefficient for me, so
I'm posting this here to get some crowd-sourced help.

Each image contains the beginning offset for the hex value in Kanji. The hex offset for the Kanji (and all characters for that matter) are in 2 bytes, and in little endian.

The kanji starts at address 2013, and the next kanji is at address 3213, the one after is 4413. This guide should show how the images are laid out. I need the Kanji pasted in Unicode next to each offset.

If all of that is confusing to you, the table is already created with blank entries in the order the Kanji appears, from left to right, going down.

![Kanji guide](/images/kanji_guide.png)


## Images

![Kanji 01](/images/1_2013_f.png)
![Kanji 02](/images/2_c018_f.png)
![Kanji 03](/images/3_601e_f.png)
![Kanji 04](/images/4_0024_f.png)
![Kanji 05](/images/5_a029_f.png)
![Kanji 06](/images/6_402f_f.png)
![Kanji 07](/images/7_e034_f.png)
![Kanji 08](/images/8_803a_f.png)
![Kanji 09](/images/9_2040_f.png)
![Kanji 10](/images/10_c045_f.png)
![Kanji 11](/images/11_604b_f.png)
![Kanji 12](/images/12_0051_f.png)

