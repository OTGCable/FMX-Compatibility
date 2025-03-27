This repo is looking for **collaborators**!
You could help manage **issues**, approve **pull requests**, and **directly edit markdown files without needing a pull request**. If you’d like to become a collaborator, please apply through the [Issues](https://github.com/XDanfr/FMX-Compatibility/issues) tab.
 
# FreeMyXe Compatibility Database
This is a community-driven compatibility database for Games and Homebrew running on [**FreeMyXe**](https://github.com/InvoxiPlayGames/FreeMyXe)**-patched Xbox 360 consoles**.
The goal is to document which Games and Homebrew work, which have issues, and any possible fixes.

## How to Use:
1. **Check Compatibility**:  
 - Browse the [Retail Games](/Retail.md), or [Homebrew](/Homebrew.md) lists to see if a title works with FreeMyXe.
2. [**Contribute**](#how-to-contribute):  
 - If you've tested a Game or Homebrew, contribute your findings by creating a pull request or using the Issues tab to report compatibility. See [How to Contribute](#how-to-contribute) for more.
3. **Additional Information**:  
 - Visit the [**Wiki**](https://github.com/XDanfr/FMX-Compatibility/wiki) for more detailed guides on testing and patching methods.
 
> [!NOTE]
> This repo is made for **legally dumped Games** and Homebrew. This does **not** serve for piracy.
> While pirated Games *will usually* run the same, this repo is made for people to see which legally dumped Games and Homebrew will run and therefore does not support or endorse piracy in any way.
 
## Game Compatibility List

Compatibility reports are categorised as follows:

| Status | Meaning |
|--------|---------|
| ✅ Works | Fully functional with no issues. |
| ⚠️ Partially | Works, but has glitches or requires fixes. |
| ❌ Borked | Does not work or crashes. |
| 👤 Offline | Only use an offline account (not Xbox Live) to prevent a ban. |
 
## Assumptions
- All Games and Homebrew listed in this database are assumed to have been patched using one of the methods in the [**Wiki**](https://github.com/XDanfr/FMX-Compatibility/wiki) before testing. If a title does not work, please ensure it has been properly patched before reporting compatibility issues.
- **Arcade games should work out of the box** in GoD format, but if you experience any issues, please report them via the issues tab or add them to the database.
 
> [!NOTE]
> If a Game or Homebrew doesn't work via XexTool, it's very likely that it'll work via [this method](https://www.youtube.com/watch?v=tUajcJjVaPY) (video). This is the recommended method.
 
## Known Issues and Troubleshooting
- **Game not working after patching?**  
 
- Make sure you followed the recommended patching method outlined in the [Wiki](https://github.com/XDanfr/FMX-Compatibility/wiki/Recommended-method:-How-to-patch-Title-Updates). If it still doesn't work, it is likely `❌ Borked`. Please submit an issue regarding this. 
 
- **Problems with Indie Games?**  
 
- Indie Games often require an Xbox Live connection, which could lead to a potential **ban** from Microsoft if you are using FreeMyXe. While these games will generally work when connected, we strongly **recommend using an offline account** to prevent any risk.
 
## How to Contribute
We rely on the community to expand and maintain this database (though I will be posting a lot here too with my findings!). To submit a compatibility report:
 
1. **Fork this repo**
2. **Edit the relevant markdown file**
3. **Use this format** when adding a new Game or Homebrew:
   ```md
   | Game/Homebrew Title        | Manual | XexTool | GoD patching | No patching | Notes (Crashes, Fixes, Patches)      |
   |----------------------------|:------:|:-------:|:------------:|:-----------:|--------------------------------------|
   | Example Game               |   ⚠️   |         |              |     ❌      | Crashes after loading world 2        |
   | Another Game 👤            |   ✅   |   ✅    |              |             | No issues found, use offline account |
   | Yet Another                |   ❌   |   ❌    |      ❌      |             | Doesn't launch at all                |
   ```
 

   So that it'll look like this:
 
   | Game/Homebrew Title        | Manual | XexTool | GoD patching | No patching | Notes (Crashes, Fixes, Patches)      |
   |----------------------------|:------:|:-------:|:------------:|:-----------:|--------------------------------------|
   | Example Game               |   ⚠️   |         |              |     ❌      | Crashes after loading world 2        |
   | Another Game 👤            |   ✅   |   ✅    |              |             | No issues found, use offline account |
   | Yet Another                |   ❌   |   ❌    |      ❌      |             | Doesn't launch at all                |

5. **Submit a pull request** with your changes.


> [!NOTE]
> Need more help? Check out GitHub's guide on [Contributing to a project](https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project).

Alternatively, you can report compatibility using **GitHub Issues**:

- Open an [**Issue**](https://github.com/XDanfr/FMX-Compatibility/issues/new?template=compatibility_report.yml) and follow the provided template.


We are also looking for contributors! Check the top of this readme to find out more.
 
> [!NOTE]
> To avoid compatibility issues, **always make sure you're using the latest version** of [BadUpdate](https://github.com/grimdoomer/Xbox360BadUpdate/releases/latest) and [FreeMyXe](https://github.com/InvoxiPlayGames/FreeMyXe/releases/latest).

<!-- CONTRIBUTORS_START -->
<!-- CONTRIBUTORS_END -->
 
## Help Wanted
- **Testing** additional [Homebrew](/Homebrew.md) and documenting their compatibility.
- **Improving** the [Wiki](https://github.com/XDanfr/FMX-Compatibility/wiki) with easier to understand patching instructions.
- **Translating** the repo into other languages to make it more accessible globally.
 
## Roadmap
- Nothing left! Feel free to give suggestions via the Issues tab.
 
## Credits
This project is maintained by the Xbox 360 community! Special thanks to:
- [**InvoxiPlayGames**](https://github.com/InvoxiPlayGames) for creating [**FreeMyXe**](https://github.com/InvoxiPlayGames/FreeMyXe) and discovering the Rock Band Blitz save file exploit.
- [**grimdoomer**](https://github.com/grimdoomer) for developing [**Xbox360BadUpdate**](https://github.com/grimdoomer/Xbox360BadUpdate).
- **evangeloush** ([u/3v4ng310u5](https://reddit.com/u/3v4ng310u5)) for helping out with a couple of questions and making an awesome [**tutorial**](https://www.reddit.com/r/360hacks/comments/1j7kaz8/running_actual_Games_on_the_badupdate_exploit/).
- [**CabooseSayzWTF**](https://github.com/CabooseSayzWTF) for discovering the recommended [**manual patching method**](https://github.com/XDanfr/FMX-Compatibility/wiki/Recommended-method:-How-to-patch-Title-Updates) - many Games would not work or have TUs working **without your work.**
<!-- CONTRIBUTORS_START -->
<!-- CONTRIBUTORS_END -->
<!-- CONTRIBUTORS_START -->
<!-- CONTRIBUTORS_END -->
<!-- CONTRIBUTORS_START -->
<!-- CONTRIBUTORS_END -->
<!-- CONTRIBUTORS_START -->
<!-- CONTRIBUTORS_END -->
<!-- CONTRIBUTORS_START -->
<!-- CONTRIBUTORS_END -->
<!-- CONTRIBUTORS_START -->
<!-- CONTRIBUTORS_END -->
<!-- CONTRIBUTORS_START -->
<!-- CONTRIBUTORS_END -->
<!-- CONTRIBUTORS_START -->
<!-- CONTRIBUTORS_END -->
<!-- CONTRIBUTORS_START -->
<!-- CONTRIBUTORS_END -->
<!-- CONTRIBUTORS_START -->
<!-- CONTRIBUTORS_END -->
<!-- CONTRIBUTORS_START -->
<!-- CONTRIBUTORS_END -->
<!-- CONTRIBUTORS_START -->
<!-- CONTRIBUTORS_END -->
<!-- CONTRIBUTORS_START -->
<!-- CONTRIBUTORS_END -->
<!-- CONTRIBUTORS_START -->
<!-- CONTRIBUTORS_END -->
<!-- CONTRIBUTORS_START -->
<!-- CONTRIBUTORS_END -->
<!-- CONTRIBUTORS_START -->
### Top Contributors
| Contributor | Contributions |
|-------------|---------------|
| [olakase123lol](https://github.com/olakase123lol) | 37 |
| [lucmsilva651](https://github.com/lucmsilva651) | 3 |
| [needmorepaper](https://github.com/needmorepaper) | 3 |
| [boazvdwansem](https://github.com/boazvdwansem) | 1 |
| [Creativezito](https://github.com/Creativezito) | 1 |
| [RobertLippai](https://github.com/RobertLippai) | 1 |
| [Sunne223](https://github.com/Sunne223) | 1 |
| [butterfingersman](https://github.com/butterfingersman) | 1 |
| [hj-0](https://github.com/hj-0) | 1 |
| [pinzit](https://github.com/pinzit) | 1 |
<!-- CONTRIBUTORS_END -->
