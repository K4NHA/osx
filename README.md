# osx

<b>Copy/Paste from within Preview and Quick Look windows:</b>

defaults write com.apple.finder QLEnableTextSelection -bool TRUE;killall Finder


<b>Stop TimeMachine from asking about using external disks when connected:</b>

defaults write com.apple.TimeMachine DoNotOfferNewDisksForBackup -bool TRUE


<b>Prevent .DS_Store file creation on remotely connected drives:</b>

defaults write com.apple.desktopservices DSDontWriteNetworkStores true


<b>Add to .bashrc in Home Directory to enable color-coding within command line:</b>

export CLICOLOR=1
export LSCOLORS=ExFxCxDxBxegedabagacad


<b>Change location screenshots are saved:</b>

defaults write com.apple.screencapture location /new/location/path/
