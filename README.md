# Password Codecs

Collection of password encoders and decoders created
with the *Cracking Videogame Passwords* video series at:
https://www.youtube.com/playlist?list=PLzLzYGEbdY5nEFQsxzFanSDv_38Hz0w7B

Back in the day when games were supplied on ROM cartridges, there were no
files or memory cards to which the game could be saved.

On cartridges that did not have battery-backed SRAM, some games still
provided the save-and-load function by using *paper* as the storage:
The game state would be encoded in such a way
that the player can transcribe it down on paper.
For example, as a sequence of letters.
Later, the player can enter the password,
and if the password passes validation,
the game will load the state stored in it.

Because the password was stored in media that is subject to
both intentional degradation (cracking)
and unintentional degradation (misspelling or misreading),
most games employed encryption and checksumming.
The purpose of encryption and checksumming was to make sure,
that the player cannot cheat or accidentally enter such a password
that gives them an unfair advantage.
Each game did this a bit differently.

The act of saving the game as a password was an art unto itself.
Some games were particularly creative with how they did it.
This makes it an entertaining subject of study in my opinion.
It also provides a window into the minds and process of game development
in the early console era, and is a way to document and appreciate
the hard work the programmers did back in the day.
Sometimes it may spotlight caveats that are still applicable to developers even today.

Note: The “Research by” headers list the research that was utilized in the
making of the episode. It is not a leaderboard of people who were
globally the first to crack the passwords.

The word “codec” means a combined en**co**der-**dec**oder.
These programs encode and decode passwords.

## Episode 1: NES Mega Man 2 (Rockman 2)

Episode date: 2016-09-03  
Research by: Bisqwit, 199x

No files

## Episode 2: NES Mega Man 3 (Rockman 3)

Episode date: 2016-09-04  
Research by: Bisqwit, 199x

No files

## Episode 3: NES Gremlins 2

Episode date: 2016-09-05  
Research by: Bisqwit, 2016

* multigrep.php (PHP): A tool for searching files for strings with a character set offset and possibility of sparse strings

## Episode 4: NES Bubble Bobble

Episode date: 2016-09-06  
Research by: Bisqwit, 2016

* bubbob-password.php (PHP): A tool that prints the list of all passwords that can be decoded by the game, producing 1719 lines of output.

## Episode 5: NES Mega Man 4 (Rockman 4)

Episode date: 2016-09-07  
Research by: unknown, 200x

* mm4minimal1.php (PHP): A minimal tool for generating a random valid password as an image.
* mm4minimal1.py (Python): A Python version of the same.
* megaman4-model2.png (PNG): An image file used by the above two programs.

## Episode 6: NES Castlevania II — Simon’s Quest (Dracula II — Noroi no Fuuin)

Episode date: 2016-09-10  
Research by: unknown, 200x  
Research by: Bisqwit, 200x

* simonspass.cc (C++): An encoder and decoder for the passwords. No main program.

## Episode 7: NES Bomberman

Episode date: 2016-09-15  
Research by: Bisqwit, 2016

* bomberpass.cc (C++): An encoder and decoder for the passwords.

## Episode 8: NES Solar Jetman — Hunt for the Golden Warpship

Episode date: 2016-09-27  
Research by: TNSe, 2004  
Research by: Bisqwit, 2016

* solarpass.rs (Rust): An encoder and decoder for the passwords.

## Episode 9: NES River City Ransom (Downtown Nekketsu Monogatari)

Episode date: 2016-10-02  
Research by: Bisqwit, 2016

* rcrpass.cc (C++): An encoder and decoder for the passwords. UTF-8 combining diacritics and accents supported.

## Episode 10: NES The Guardian Legend (Guardic Gaiden)

Episode date: 2016-10-30  
Research by: TNSe, 2004  
Research by: Bisqwit, 2016

* guardicpass.cc (C++): An encoder and decoder for the passwords. ASCII only.
