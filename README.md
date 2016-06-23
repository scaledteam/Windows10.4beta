# Windows10.4beta

## Changes:

### API 5.0

	appStart(string,vector2,vector,number) replaced by app(string)
	appGraphics() replaced by appGraphics(vector2,vector,number)
	appEnd() function deleted
	Renamed many function and varriables
	Launch app from App_Launch = "App name" or intent("App name", table())
	Optimised some EGP objects, using egpCopy command
	Many functions replaced by varriables
	appContextMenuAnswear(VarName:string) return string
	appEgpMemory(EGPID_Count)

### Support extended mode of second screen

	System of search pos of second screen
	Support EGP Hub's

### New apps:

	E2Editor (only for servers with remote writing)
	PlayerRace
	LoadAnim (demo)
	Illusion (original by CornerPin, Windows version by scaled)

### Reduced system requirements

	Minimal quota requirements:
		tick: 15000
		hard: 50000
		soft: 5000
	Also you can use Windows 10.4 without all extentions

### Other

	Screen rotating
	Volume settings
	Fixed multi-threading
	Many stability
	Change resolution without reboot
	Possibility exclude input, screen2 and scripts
	New file structure
	Perf test now support few threads
