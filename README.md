# WindowsTerminalSettings

Install-Module -Name PSReadLine -AllowPrerelease -Scope CurrentUser -Force -SkipPublisherCheck

Install-Module oh-my-posh -Scope CurrentUser

Install-Module posh-git -Scope CurrentUser


Add to profile:

Import-Module posh-git

Import-Module oh-my-posh

Set-Theme Paradox


Install cascadia code pl font to fix glyphs:
https://github.com/microsoft/cascadia-code/releases
