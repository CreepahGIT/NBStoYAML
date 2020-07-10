# NBStoYAML - Play Note Block Songs in Skript

**Hello there!** <br />
You want to play Note Block Studio songs on your minecraft server using [Skript](https://github.com/SkriptLang/Skript)? <br />
There are some addons that help you do that, find them using [Google](https://www.google.com). <br />
<br />
What's that? You can't get those addons for some reason? <br />
And you have an addon that allows you to read YAML? (SkQuery, Skellett, skript-yaml, etc.) <br />
Well, **NBStoYAML** can help you do that. <br />
<br />
**NBStoYAML** uses [Open NBS](https://opennbs.org). <br />
**Supported NBS Versions:** 4.0 <br />
<br />
**How NBStoYAML works:**
1. Note Block Song (`.nbs`) files are converted to YAML (`.yml`) files with a skript-parsable format
1. Using Skript, these files are read and played in-game to play a song<br />

**How to use NBStoYAML:**
1. Download [Open NBS](https://opennbs.org) and make/download a song.
    * You can also download [test.nbs](https://github.com/CreepahGIT/NBStoYAML/blob/master/Usage%20Example/test.yml) from this repository.

1. Download *NBStoYAML.exe* from the latest release.
    * If you are not on Windows, clone this repository and compile *NBStoYAML.exe* on [Visual Studio 2019](https://visualstudio.microsoft.com) or any other IDE of your choice.
1. Open command prompt/terminal.
    * If you are on Windows, press `WIN+R`, type `cmd` and press enter.
1. Run *NBStoYAML.exe* from command line.
    * First argument is the path to Note Block Song (`.nbs`) file to convert.
    * Second argument is the path to YAML (`.yml`) file to save to.
1. You should see a YAML (`.yml`) file containing some data. You now have two options:
    * Download [ExampleParser.sk](https://github.com/CreepahGIT/NBStoYAML/blob/master/Usage%20Example/ExampleParser.sk) from this repository.
    * Write your own parser with Skript to play the song.
1. Using Skript and the parser you acquired from the last step, play your song.
    * If you are using [ExampleParser.sk](https://github.com/CreepahGIT/NBStoYAML/blob/master/Usage%20Example/ExampleParser.sk), you can load songs by calling `NBSYAML_loadSong()` or executing `/loadsong` and play songs by calling `NBSYAML_playSong()` or executing `/playsong`. For a better understanding of the parser, please try to read the script. 
<br />
  
**Note:** *NBStoYAML* may be far less efficient than using an addon to read from Note Block Song (`.nbs`) files directly, but in the case that those addons are not available, *NBStoYAML* can be used.<br />
<br />