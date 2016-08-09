export packages (only packages name)

apm list --installed --bare > ~/Gdrive/backup.txt

import

apm install --packages-file ~/Gdrive/backup.txt

on Linux apm available if you install atom from .deb file, on OSX: open atom -> install shell command, Windows: apm in  C:\Users\YOUR_NAME\AppData\Local\atom\bin



APM
C:\Users\*\AppData\Local\atom\bin

apm install --packages-file c:\Users\okcomputer\.atom\packages.list