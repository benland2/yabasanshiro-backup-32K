# yabasanshiro-backup-32K

Some games of Sega Saturn doesn't work with the emulator Yaba Sanshiro and the internal memory card of expanded to 8MB.
Unfortunately, the core yabasanshiro-libretro can't disable this feature.
Then I generated a file "backup.bin" that simulates less than 32K free space.

The original file used for internal memory in your Yaba Sanshiro folder should be replaced with this file.


I tested it successfully with the game "Manx TT Super Bike", on super console X King with system Emuelec.
In my case, I copied the "backup.bin" into folder "/storage/roms/saturn/Manx TT Super Bike/yabasanshiro/".

Have fun !


