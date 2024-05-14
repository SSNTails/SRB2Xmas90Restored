#### Sonic Robo Blast 2: Christmas v0.90 Restoration Project
#### Release by SSNTails ( www.youtube.com/@ssntails )
#### https://github.com/SSNTails/SRB2Xmas90Restored
#### Special thanks to Saxman for preservation!

An early build of SRB2 was given to me by my old friend Saxman, who worked with me on Sonic Doom 2 and is best known for starting the Sonic ROM hacking scene. Back in March 2000, I gave him an in-progress build of the game along with a complete copy of the source code.
Recently, we attended Retro World Expo in Hartford, Connecticut in August 2023 together, and he shared with me the original, intact files that I sent him.

At the forefront of the files was the SRB2 Prototype ( https://github.com/SSNTails/SRB2Proto ). But I later discovered that there was a seeemingly innocuous, and also disassembled with DEUTex, copy of srb2xmas.wad included.

It turns out that this was the WAD to SRB2 Christmas v0.90, which has been lost forever, contrary the the rule that everything on the Internet is forever.

But it was still missing a few things... most notably, an EXE file. And also the 'doom3.wad' equivalent, xmassupp.wad. This is where the Prototype comes into play!

Back before source control, I would mark each changed line in the code with // Tails MM-DD-YYYY. Since the Prototype isn't much older, I could take it, and work backwards, reverting the changes made after 12-24-1999. And so I did.

A few things from v0.90 were removed though, most notably the 'Infini-Thok'. Thankfully, I remember quite vividly how it was implemented, so it is back in all of its original janky glory.

#### If you get an error, "I_RegisterSong: StreamBufferSetup FAILED", that means you must use the -nomusic parameter to launch the game.

### Usage: srb2win.exe -nomusic -nocd -win
### You must launch from command line. If you don't know how to do this, you'll need to learn! TUSL is included as a handy way to add parameters to the game.

#### Pull Requests are welcome! Want to fix a bug? Add the new SDL2 layer? Those are just a few ideas.


~SSNTails
