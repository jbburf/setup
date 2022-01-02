## Initial OS Setup
- Keyboard Settings
  - System Prefeerences -> Keyboard -> Input Sources, Add DVORAK and remove QWERTY
  - Uncheck `Show Input menu in menu bar`
  - Remove repeat delay on keyboard input
- Trackpad Settings
- Set computer name
- Touchbar Settings
  - Touch Bar shows: Expanded Control Strip
  - Remove Siri Button
- Finder Settings
  - Finder Menu -> Preferences, unchecked all items shown on desktop
  - New windows shows: user directory aka `~/{user}` or `~/ben` for me
  - Uncheck all tags
  - Set sidebar to show: Recents, Downloads, User Folder. Uncheck all iCloud and check all locations except this computer being setup.
- Finder View Options
  - On the Desktop: View Menu -> Show View Options, set Stack By to `Kind`
  - Add path to Finder's toolbar
- Finder Window Toolbar
  - Add `Path` then `View` icons, remove all others
- System Preferences -> Mission Control -> Disable Automatically rearrange Spaces based on recent use

## Download Apps
- [Dropbox](https://www.dropbox.com/downloading)
  - Configure application and begin Smart Sync
- [1Password](https://1password.com/downloads/mac/)
- [TG Pro](https://www.tunabellysoftware.com/tgpro/)
  - Enter activation code, set menu bar to show temp with colors and application icon.
- [Little Snitch](https://www.obdev.at/products/littlesnitch/download.html)
- [Things](https://culturedcode.com/things/)
  - Configure Things Cloud and let it sync
- [Alfred 4](https://www.alfredapp.com/) + PowerPack
  - Skip migration and sync to `~/dropbox/app_sync` and enter licence code
  - Set Spotlight shortcut to `⌥ + space` via System Preferences -> Keyboard -> Shortcuts -> Spotlight
  - Set Alfred's shortcut to `⌘ + space` in Alfred preferences
- [Bartender](https://www.macbartender.com/)
- [Chrome](https://www.google.com/chrome/)
  - Add my profiles
  - Remove "Warn Before Quitting" in the application menu
- [Vitamin R-3](https://www.publicspace.net/Vitamin-R/)
- [Visual Studio Code](https://code.visualstudio.com/download)
  - Sign in with GitHub on enable config syncing
  - Install shell command 'code', ⌘ + ⇧ + P then type `Shell command` and it will autofill the rest.
- [MonitorControl](https://github.com/MonitorControl/MonitorControl) if I'm using external monitors.

## CLI Setup
- [iTerm 2](https://www.iterm2.com/downloads.html)
  - Import [my profile](/iTerm-profile-jbb.json) or set manually:
    - Preferences -> Profile -> Window -> Style -> Full Width Top of Screen
    - Preferences -> Profile -> Transperancy = 25% && Blur = 50%
    - Preferences -> Keys -> HotKey -> Show/hide all windows... CONTROL-`
    - Preferences -> Profile -> Text -> Use build-in Powerline glyphs
  - Setup [visor behavior](https://apple.stackexchange.com/questions/48796/iterm-as-a-slide-out-terminal-from-the-top-of-the-screen) on ⌥ + ⌥ (like [TotalFinder](https://totalfinder.binaryage.com))
- [Xcode](https://apps.apple.com/us/app/xcode/id497799835)
  - Just install CLT (commandline tools) seperately and skip Xcode unless I need to do iOS/MacOS development.
  - CLT can be installed via $ `xcode-select --install`
  - Note: If you're running a beta verion of MacOS, you may need to download CLT directly from [Apple here](https://developer.apple.com/download/more/).
- Install [Homebrew](https://brew.sh/) with $`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"`
- Install [zsh](https://www.zsh.org/) with $`brew install zsh`
- Install [Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh) with $`sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`
- Install [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) with $ `brew install zsh-syntax-highlighting`
- Install [nvm](https://github.com/nvm-sh/nvm#installation-and-update)
  - Brew is not a supported install method, check [NVM's github](https://github.com/nvm-sh/nvm#install--update-script) or use the next line:
  - $ `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh | bash`
  - Setup NVM to have current Node LTS as well as any previous stable releases needed
- Configure your `.zshrc`, feel free to [borrow mine](/.zshrc).
- Install [shellcheck](https://github.com/koalaman/shellcheck)
  - $ `brew install shellcheck`
- The theme I run in ZSH takes care it if but [here is some great info on changing your prompt](https://phoenixnap.com/kb/change-bash-prompt-linux).

Stack specific setup can be found in a seperate readme for [Javascript](/javascript.md), PHP, GoLang, C++, Rust, Python, Ruby and [Java](/java.md).

## Additional Apps
- Communication
  - [Slack Beta](https://slack.com/beta/mac)
  - [Teleglam Desktop](https://desktop.telegram.org/)
  - [Discord](https://discord.com/download)
- Browsers
  - [Brave](https://brave.com/download/)
  - [Firefox](https://www.mozilla.org/en-US/firefox/new/)
  - [Tor Browser](https://www.torproject.org/download/)
- OS Extensions
  - [SoundFlower](https://github.com/mattingalls/Soundflower/releases)
  - [Superduper!](https://www.shirt-pocket.com/SuperDuper/SuperDuperDescription.html)
  - Add [webP support](https://ourcodeworld.com/articles/read/1160/how-to-enable-webp-image-format-preview-on-the-macos-finder) to Finder with $`brew install --cask WebPQuickLook`
- [Mountain Duck](https://mountainduck.io/) + [Cyberduck](https://cyberduck.io/download/)
- [Tuxera NTFS](https://www.tuxera.com/products/tuxera-ntfs-for-mac/download/)
- Productivity
  - [Deltawalker](https://www.deltawalker.com/download)
  - [The Unarchiver](https://apps.apple.com/us/app/the-unarchiver/id425424353)
  - [Gemini 2](https://macpaw.com/gemini)
  - [PDF Squeezer](https://witt-software.com/pdfsqueezer/)
  - [Home Inventory](https://binaryformations.com/products/home-inventory/)
  - [Deliveries](https://apps.apple.com/us/app/deliveries/id924726344)
- Virtualization
  - [Parallels Desktop](https://www.parallels.com/products/desktop/trial/)
  - [Docker Desktop](https://www.docker.com/products/docker-desktop)
  - [VirtualBox](https://www.virtualbox.org)
- Media
  - [VLC](https://www.videolan.org/vlc/download-macosx.html)
  - [Transmission](https://transmissionbt.com/download/)
  - [Airy](https://mac.eltima.com/airy-download.html)
  - [Sonos](https://support.sonos.com/s/downloads)
  - [Resilio](https://www.resilio.com/individuals/)
- Design Software
  - [Balsamiq Mockups 3](https://balsamiq.com/wireframes/desktop/)
  - [Affinity Designer](https://affinity.serif.com/en-us/designer/)
  - [Gimp](https://www.gimp.org/downloads/)
  - [Sketch](https://www.sketch.com/get/)
  - [Abstract](https://app.abstract.com/download)
  - [Miro](https://miro.com/apps/)
  - [MindNode](https://mindnode.com/download)
- Software Development
  - [GitKraken](https://www.gitkraken.com/download/mac)
  - [Postman](https://www.getpostman.com/downloads/)
- Database Management
  - [Robo 3T](https://robomongo.org/download)
  - [Azure Data Studio](https://docs.microsoft.com/en-us/sql/azure-data-studio/download-azure-data-studio?view=sql-server-ver15)
- Mobile Development
  - [Reflector 3](https://www.airsquirrels.com/reflector/download)

## Notification Settings
- Mail
  - Mail Alert Style: None
  - Uncheck all expect `Badge app icon`
  
## MacOS Processes
- I generally block everything that doesn't seem to serve a good purpose with Little Snitch. I'd like to list out all processes that I block but have found that the default settings work pretty well.
