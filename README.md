usage: ttll-windows.exe [-h] [-v] [-y] [--archive ARCHIVE] [-a APK] [-o OBB] [-i INI] [-m MAP] [-c COMMANDLINE]
                        [-so SO] [-rn RENAME] [-p PATCH] [-rm] [-l] [-ls] [-op] [-sp] [-sk] [-cc] [-r]
                        [--set-config KEY VALUE] [--adb ...] [-sw] [--stay] [--message MESSAGE]
                        [download ...]

Triple T Legacy Launcher 1.0.0 By Kube Built Off Legacy Launcher 1.4.7 By Obelous Source Code

positional arguments:
  download              Build version to download and install -

options:
  -h, --help            show this help message and exit
  -v, --version         show program's version number and exit
  -y, --yes, --auto-confirm
                        Automatically confirm prompts
  --archive ARCHIVE     Path/URL to a zip archive (use archive:/path/inside.apk)
  -a, --apk APK         Path/URL to an APK file
  -o, --obb OBB         Path/URL to an OBB file
  -i, --ini INI         Path/URL for Engine.ini
  -m, --map MAP         What map to load in format "Label|Path/To/Map"
  -c, --commandline COMMANDLINE
                        Launch arguments for UE
  -so, --so SO          Inject a custom .so file
  -rn, --rename RENAME  Rename the package to com.LegacyLauncher.<VALUE>
  -p, --patch PATCH     Byte pattern to patch
  -rm, --remove         Uninstall all versions
  -l, --logs            Pull game logs from the headset
  -ls, --list           List available versions
  -op, --open           Launch the game once finished
  -sp, --strip          Strip permissions to skip pompts on first launch
  -sk, --skipdecompile  Reuse previously decompiled files
  -cc, --clearcache     Delete cached downloads
  -r, --restore         Restore to the latest version
  --set-config KEY VALUE
                        Set an existing config key to a value
  --adb ...             Run a custom adb command using bundled adb (example: --adb devices)
  -sw, --switch-map     Change which map to load
  --stay                Keep the window open until Enter is pressed
  --message MESSAGE
