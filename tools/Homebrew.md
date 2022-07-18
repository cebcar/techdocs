# Homebrew
[Homebrew Tool Profile](#homebrew-profile)<br/>
*The Missing Package Manager for macOS (or Linux)*<br/>

We use Homebrew to install software on macOS.

## Homebrew Tasks

### Find and Install a Package
from directory ~/dotfiles:
> brew search 	[--cask] &lt;pkgname&gt;
> brew info   	[--cask] &lt;pkgname&gt;
> brew install	[--cask] &lt;pkgname&gt;

<br/>
## *Homebrew Profile*<br/>
CLI tool @ /usr/local<br/>
*The Missing Package Manager for macOS (or Linux)*<br/>

**Version**: 3.0.0<br/>
**Source**: [brew.sh](brew.sh)<br/>
**Obtained**: 2021-11-03; [Homebrew](brew.sh)<br/>
**License**: public domain<br/>
**Critical Data**: /usr/local<br/>
- Homebrew package @ /usr/local/Homebrew
- Installed packages @ /usr/local/Cellar
- Casks for gui apps @ /usr/local/Caskroom
- Symlinks for accessing installed software are stored at the locations users expect
in other /usr/local folders, e.g. /usr/local/bin
**Installation**:<br/>
- copy installation command fom Homebrew's homepage at brew.com; currently
> /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

**Documentation**: [Homebrew Docs](docs.brew.sh)<br/>

### Homebrew Configuration
#### GitHub Personal Access Token for Homebrew (TODO: finish)
Create a GitHub personal access token:
``` zsh
  https://github.com/settings/tokens/new?scopes=gist,repo,workflow&description=Homebrew
  echo 'export HOMEBREW_GITHUB_API_TOKEN=your_token_here' >> ~/.zshrc
```
### Homebrew Automation
### Homebrew Shortcuts
### Homebrew Alternatives Considered
Homebrew is the standard for package installation.
No other alternatives were considered.
