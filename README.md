<h1 align="center">Mastermind Game · IUT de Paris - Rives de Seine</h1>

The "Mastermind Game" GitHub project is an application of a variant of the Mastermind board game developed with the Visual Studio environment and using the Visual Basic .NET programming language.

> **Warning** : The project has been developed exclusively in a professional context, with the specific aim of promoting learning. It is carried out as a project for the University of Paris.

<p align="center">
  <img src="https://github.com/Corentin-Lcs/iut-mastermind-game/blob/main/MasterMind.jpg" alt="MasterMind.jpg"/>
</p>

## Game Rules

Mastermind (or Master Mind) is a two-player board game whose objective is to find a code.

It is usually presented as a perforated board with 10 rows of four holes that can accommodate color pawns. The number of different colored pawns is 8, and the eight colors are generally : red, yellow, green, blue, orange, white, purple and fuchsia. There are also white and red (or black) pawns used to give indications at each stage of the game. There are many variations depending on the number of colors, rows or holes.

A player begins by placing his choice of pawns without them being seen by the other player behind a cover which will hide them from his view until the end of the round. The player who who did not select the pawns must try to determine the colors and positions of the pawns. To do this, at each turn, the player must use pawns to fill a row based on their perception of the hidden pawns. Once the pawns are placed, the other player indicates the number of pawns of the correct color placed correctly, as well as the number of pawns of the correct color but incorrectly placed.

The active player's strategy involves selecting colors and positions based on previous moves in order to gather maximum information from their partner's response, as the number of attempts is limited by the number of rows in the game. In most cases, the player aims to get as close as possible to the solution, taking into account the previous feedback. However, they may also create a combination with the sole purpose of testing certain conclusions from previous moves and making a proposal that is most conducive to deducing new information.

The player wins the round if he gives the right combination of pawns on the last row or before (Source : [Wikipedia](https://en.wikipedia.org/wiki/Mastermind_(board_game))).

## Usage

To open and launch the program on Visual Studio, click on the following file :

```bash
mastermind.sln    # Path : iut-mastermind-game/src/
```

> To better understand the progress of a game, please consult the manual for the subject by clicking [here](https://github.com/Corentin-Lcs/iut-mastermind-game/blob/main/Sujet.pdf).

## Project's Structure

```
iut-mastermind-game/
├─ README.md
├─ LICENSE
├─ Sujet.pdf
├─ Sujet.tex
├─ MasterMind.jpg
├─ pictures/
│  ├─ player1.png
│  ├─ player2try1.png
│  ├─ player2try1answer.png
│  ├─ player2try2answer.png
│  └─ player2victory.png
└─ src/
   ├─ mastermind.sln
   └─ mastermind/
      ├─ .vs/
      │  ├─ ProjectSettings.json
      │  ├─ VSWorkspaceState.json
      |  ├─ slnx.sqlite
      │  └─ sae/
      │     ├─ FileContentIndex/
      │     │  ├─ 4c04361e-18b9-4045-8492-153572eff62f.vsidx
      │     │  ├─ d13569a6-e719-4b58-8201-4d2f8fb304cb.vsidx
      │     │  ├─ dfb9a195-6346-4158-b8a7-d0c0f7c8f539.vsidx
      │     │  ├─ f94634f7-5b62-44a4-ab78-f97cbbbc5b9e.vsidx
      │     │  └─ read.lock
      │     └─ v17/
      │        ├─ .suo
      │        └─ .wsuo
      ├─ My Project/
      │  ├─ Application.Designer.vb
      │  ├─ Application.myapp
      │  ├─ AssemblyInfo.vb
      │  ├─ Resources.Designer.vb
      │  ├─ Resources.resx
      │  ├─ Settings.Designer.vb
      │  ├─ Settings.settings
      │  └─ app.manifest
      ├─ obj/
      │  └─ Debug/
      │     ├─ .NETFramework,Version=v4.8.AssemblyAttributes.vb
      │     ├─ DesignTimeResolveAssemblyReferencesInput.cache
      │     └─ mastermind.vbproj.AssemblyReference.cache
      ├─ Resources/
      │  └─ Blanc-BDE-Informatique-2023-2024.ico
      ├─ App.config
      ├─ ChoixMotForm.Designer.vb
      ├─ ChoixMotForm.resx
      ├─ ChoixMotForm.vb
      ├─ ColorPickerForm.Designer.vb
      ├─ ColorPickerForm.resx
      ├─ ColorPickerForm.vb
      ├─ CombinationProposition.vb
      ├─ DebutForm.Designer.vb
      ├─ DebutForm.resx
      ├─ DebutForm.vb
      ├─ Game.vb
      ├─ HelpForm.Designer.vb
      ├─ HelpForm.resx
      ├─ HelpForm.vb
      ├─ MastermindGameForm.Designer.vb
      ├─ MastermindGameForm.resx
      ├─ MastermindGameForm.vb
      ├─ MastermindTextBoxes.vb
      ├─ MemeForm.Designer.vb
      ├─ MemeForm.resx
      ├─ MemeForm.vb
      ├─ MusicPlayer.vb
      ├─ Options.vb
      ├─ OptionsForm.Designer.vb
      ├─ OptionsForm.resx
      ├─ OptionsForm.vb
      ├─ StatsForm.Designer.vb
      ├─ StatsForm.resx
      ├─ StatsForm.vb
      ├─ TextBoxBorder.vb
      ├─ TimeTools.vb
      ├─ mastermind.sln
      ├─ mastermind.sln.DotSettings.user
      ├─ mastermind.vbproj
      ├─ mastermind.vbproj.DotSettings.user
      └─ mastermind.vbproj.user
```

Named `Sujet.pdf` (Subject.pdf), the file contains the subject of the project and is the compiled version of `Sujet.tex` (Subject.tex).

Named `mastermind.sln`, the file is the program executable.

## Meta

Created by [@Corentin-Lcs](https://twitter.com/CorentinLenclos). Feel free to contact me !

Distributed under the GNU GPLv3 license. See [LICENSE](https://github.com/Corentin-Lcs/iut-mastermind-game/blob/main/LICENSE) for more information.
