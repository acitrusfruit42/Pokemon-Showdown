Pokemon Showdown
========================================================================

Pokemon Showdown is a simulator of Pokemon battles. It currently supports singles battles in Generations 4-5 (HGSS, BW, BW2).

This repository contains the files needed to set up your own Pokemon Showdown server. Note that to set up a server, you'll also need a server computer.

You can use your own computer as a server, but for other people to connect to your computer, you'll need to expose a port (default is 8000 but you can choose a different one) to connect to, by setting up any firewalls you might have to allow that port through to you (this sometimes isn't possible on certain internet connections).


Making your own server.
------------------------------------------------------------------------
Pokemon Showdown requires node.js in order for you to get the server up. 

What you will need:
-Node.js: v0.6.3 through v0.8.22, or v0.10.2 and up. Install node.js if you don't have it yet; the latest stable version is a good choice to install.
-Server Computer OR opening port 8000 on your router. Use <a href="http://portforward.com/">this</a> as a guide for doing so.

Step 1:
Download GitHub onto your computer. Search a repository by the name of "Zarel/Pokemon-Showdown". Download this ("Clone" on the GitHub Program")
Step 2:
Search "cmd" in the Windows START Menu. Click on the first result.
    "Terminal" on everything else.
Step 3:
Open up the Command Prompt (cmd) and type in cd C:\Users\Username on computer\Documents|Downloads\GitHub (if in downloads, leave this blank)\Pokemon-Showdown. A new line should appear. Typr in nmp install, which should trigger a bunch of crap to come up.
Step 4:
After typng in npm install and everything is done loading, type in "node app.js".

Test your server at localhost.psim.us




Setting up an Administrator account
------------------------------------------------------------------------

Once your server is up, you probably want to make yourself an Administrator (~) on it.

### config/usergroups.csv

To become an Administrator, create a file named `config/usergroups.csv` containing

    USER,~

Replace `USER` with the username that you would like to become an Administrator.

This username must be registered. If you do not have a registered Pokemon Showdown account, you can create one using [the registration form][3].

Once you're an administrator, you can promote/demote others easily with the `/admin`, `/leader`, `/mod`, etc commands.

  [3]: http://pokemonshowdown.com/forum/register


Browser support
------------------------------------------------------------------------

Pokemon Showdown currently supports, in order of preference:

 - Chrome
 - Firefox
 - Safari
 - Chrome/Firefox/Safari for various mobile devices
 - Opera
 - Firefox for Android
 - IE9+

IE8 support can technically be added without too much difficulty, but it doesn't run PS fast enough to be usable.

As for older browsers (Firefox 3.6), I won't go out of my way to support them, but if there's a simple fix, you can suggest it to me and I'll implement it.


Community
------------------------------------------------------------------------

The Pokemon Showdown development IRC channel is `#showdown` at `irc.synirc.net`.

[The Pokemon Showdown forums][4] are hosted on Smogon Forums.

  [4]: http://www.smogon.com/forums/forumdisplay.php?f=209


License
------------------------------------------------------------------------

Pokemon Showdown's server is distributed under the terms of the [MIT License][5].

  [5]: https://github.com/Zarel/Pokemon-Showdown/blob/master/LICENSE


Credits
------------------------------------------------------------------------

Pokemon Showdown was created by Guangcong Luo [Zarel].

Developers

- Guangcong Luo [Zarel]
- Cathy J. Fitzpatrick [cathyjf]
- Bill Meltsner [bmelts]

Contributors

- [Marty-D]
- [The Immortal]
- [Joim]
- Cody Thompson [Rising_Dusk]
