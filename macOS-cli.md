## CLI Setup
- Add [subject line](https://gist.github.com/getaaron/a9dc64b6ea2fa8299af6b7077f4386ae) to Messages
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
