# System Preferences
First thing you should do is update the system. To do that go: **Apple menu () > About This Mac > Software Update.**

Also upgrade your OS in case you want to work on the latest OS. macOS upgrades are usually free so you might as well keep your machine up to date.

If this is a new computer, there are a couple tweaks you could make to the System Preferences. **These settings are all optional, consider them suggestions.**

## Users & Groups
- Login Options -> Change fast switching user menu to Icon

## Trackpad
- Point & Click
    - Check all
- Scroll & Zoom
    - Check all

## Accessibility 
- Mouse & Trackpad
    - Trackpad Options
        - Check "Enable dragging": three finger drag

## Dock
- Visual settings
    - Change position to left and make the size of Icons small
    - Activate magnification
- Other settings
    - Remove workspace auto-switching by running the following command:

```
$ defaults write com.apple.dock workspaces-auto-swoosh -bool NO
$ killall Dock
```

## Display 
- Check Scaled and choose the most confortable resolution

## Bluetooth
- Check "Show Bluetooth in menu bar"

## Audio
- Check "Show volume in menu bar"

## Spotlight
- Uncheck fonts, images, files etc.
- Uncheck the keyboard shortcuts as we'll be replacing them with Alfred

## Accounts
- Add an iCloud account and sync Calendar, Find my mac, Contacts etc.

## User Defaults
- Enable repeating keys by pressing and holding down keys: `defaults write NSGlobalDomain ApplePressAndHoldEnabled -bool false` (and restart any app that you need to repeat keys in)

## Menu Bar
- Change battery to show percentage

## Finder (Finder App)
- Preferences
    - General
        - Change 'New Finder windows show:' to something other than 'All My Files' (which is a memory hog)
    - Sidebar
        - Add home and code directory
        - Remove shared and tags
        - New finder window to open in the home directory
    - Advanced 
        - Check "Show all filename extensions"
        - Check "Remove items from the Trash after 30 days"
        - Change "When performing a search:" to "Search the Current Folder"
