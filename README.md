### studying eng physics & meche @ stanford

macOS extensions i now maintain forks of / have built:
- [Ice](https://github.com/amichaelyu/Ice): menu bar management (since original broke in macOS 27)
- [SourceCodeSyntaxHighlight](https://github.com/amichaelyu/SourceCodeSyntaxHighlight): quick lock for code files (added LaTeX support)
- [Compress Screen Recordings](https://github.com/amichaelyu/launchAgents/tree/main/compress-screen-recordings): macOS native screen recordings are excessively large for no reason
- [Zed LaTeX Viewer](https://github.com/amichaelyu/zed-skim-latex): custom sync extension between Zed and Skim for LaTEX editing
- [Skim](https://github.com/amichaelyu/skim): macOS PDF viewer with no flashing with hot reloading
- [SMB Auto Reconnect](https://github.com/amichaelyu/launchAgents/tree/main/smb-autoreconnect): auto reconnect to your network shares
 
all can be downloaded from my homebrew tap:
```
brew trust amichaelyu/tap   # Homebrew won't load third-party tap formulae until trusted
brew install amichaelyu/tap/syntax-highlight-plus
brew install --cask amichaelyu/tap/ice
brew install amichaelyu/tap/compress-screen-recordings
brew install --cask amichaelyu/tap/skim
brew install amichaelyu/tap/smb-autoreconnect
```
contact: yumich [at] stanford [dot] edu
