### Privacy & Security -> Profiles
You may export macos configuration. Is it safe, does it contain sensible information?

# macos-setup
Notes, suggestions and helpful scripts that I often need during fresh installation

## Software installation

### Firefox Developer Edition
### 1Password
Github, create new ssh key, directly with 1Password then:
https://developer.1password.com/docs/ssh/git-commit-signing/ ; there might be a better doc, you need to add a read/write key (warp <-> 1password integration for ssh)

Settings -> privacy : check for vulnerable passwords
Appearance -> always show catgegories sidebar
General -> Select default vault

### Modifier Keys vs Karabiner
### Sec
Turn on FileVault !
### Whatsapp
### IDEA Toolbox
config file for intellij ?
### Warp || iTerm2
Integrate Warp with IDE https://docs.warp.dev/features/integrations-and-plugins#jetbrains-ides
### Zap
### Postman || Obsidian
Replace Finder?


### brew
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
- Run these two commands in your terminal to add Homebrew to your PATH:
```bash
    (echo; echo 'eval "$(/opt/homebrew/bin/brew shellenv)"') >> $HOME/.zprofile # TODO change to have .settings or whatever
    eval "$(/opt/homebrew/bin/brew shellenv)"
```

### sdkman
https://sdkman.io/install
```
export SDKMAN_DIR="$HOME/.userconfig/sdkman" && curl -s "https://get.sdkman.io" | bash
source "$HOME/.userconfig/sdkman/bin/sdkman-init.sh"
```

https://www.reddit.com/r/zsh/comments/qtehjs/changing_the_location_of_configuration_files/?rdt=35082

$WORKSPACES

## warp

## Finder -> settings
### General
- Show hard drives, connected servers
- do not show CDs,DVDs,ipod
- New Finder windows shows $HOME
### Sidebar
- configure sidebar
### Advanced
- advanced: when performing a search, current folder

### - secu
FileVault
