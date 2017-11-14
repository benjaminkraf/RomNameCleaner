# RomNameCleaner
Little java program I wrote to clean ROM names for use with scrapers in emulation front-ends like EmulationStation.

Checks ROM file names for first ocurrence of ( and removes all characters up to the file extension. For most games the removed content should the standard ROM codes for country and any special codes (verified good/bad dump, fixes, translations). There is no error checking in the current release - do not run this program on folders that do not contain ROMs. 

Do not run this program on ROM files whose names do not contain a standard ROM country code. It will crash on whatever file lacks the ROM country code. 

I'll implement something to guard against user stupidity or ignorance at some point but for now I trust that if you know enough to make use of this tool you know enough to do so without making more problems for yourself.
