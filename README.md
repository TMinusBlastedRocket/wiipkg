# wiipkg
an alternative to WAD based on 7z&LZMA that allows for installing multipule channels and/or IOS's at once and better compression for archival



# How to make a .wiipkg file
(We suggest using 7z for this)

- Download the repo as a zip file 
- Step 1: extract the wiipkg folder (we will use this as a template)

- until a wiipkg manager is made for wii, we will use existing WAD files for building a wiipkg
- Step 2: dump or get a WAD file
- Step 3: use ShowMiiWads or somthing of its nature to extract the wad to a folder
- Step 4: remove 'wiipkg/ios/0' & 'wiipkg/title/EXAM' & 'wiipkg/sd/dummy'
- Step 5a(For Channel/Menu Wads):Find the title id of the channel your trying to convert and create a new folder in 'wiipkg/title' named after the title ID (all caps)
- Step 5b(For IOS's):Find the number of the IOS your trying to convert and create a new folder in wiipkg/ios with the IOS number
- Step 6: paste the dumped files in to the folder you have created
- (if you want to add more Channels/IOS's repeat steps 2-6 till you have got all the content you want added)
- Step 7: add any files you want extracted to the sd card to wiipkg/sd
- Step 8:create a .7z archive with the wiipkg folder **in** it using the config from configinfo at the root of this github


- Step 9:change the file extension to .wiipkg and make the name whatever you want
# Congrats Your Done, enjoy your file
