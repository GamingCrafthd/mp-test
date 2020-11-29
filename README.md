# MP-Test
An Multiplayer-Test for Source 2007 by Valve, Corp.
A real name will come soon, but for now, this is only a test.

## Install

### Client (needed for dedicated server too.)

- Clone this repo into `[...]/Steam/steamapps/sourcemods`<br>
  Please use the Main Steam directory in which `uninstall.exe` should be.
- Restart steam

### Dedicated Server

- Download `steamcmd.exe` and place it into a directory, that is in `PATH` like `C:\Windows`
- Run `steamcmd` in your command prompt. (You can use `Git-Bash`, `VS Developer Promt` and `Power-Shell` too.)
- Login into the anonymous account using `login anonymous`
- Select the directory of your dedicated server with `force_install_dir <path>`.
- Download the dedicated server with `app_update 310`.
- Wait for the dedicated server to download.
- When done, close SteamCMD using `exit`.
- Go to your dedicated server using `cd` or the Explorer.
- Start `srcds.exe`
- Select the Game (If you only have MP-Test, it should be that by default.)
- Setup your server.
- When done, click on `Start Server`.
- Remember to open the ports between `26900` and `27015`<br>
  For exact infos on the ports visit [this page](https://developer.valvesoftware.com/wiki/Source_Dedicated_Server) by Valve.
  
## Custom Maps
Custom maps (`*.bsp`) can be copied into `[...]/Steam/steamapps/sourcemods/mp-test/maps`
