# RepoM

RepoM is a minimal-conf git repository hub with Windows Explorer enhancements. It uses the git repositories on your machine to create an efficient navigation widget and makes sure you'll never lose track of your work along the way.

It's populating itself as you work with git. It does not get in the way and does not require any user attention to work.

RepoM will not compete with your favourite git clients, so keep them. It's not about working within a repository: It's a new way to use all of your repositories to make your daily work easier.

📦  [Check the Releases page](https://github.com/coenm/RepoM/releases) to **download** the latest version and see **what's new**!

## The Hub

The hub provides a quick overview of your repositories including their current branch and a short status information. Additionally, it offers some shortcuts like revealing a repository in the Windows Explorer, opening a command line tool in a given repository and checking out git branches.

![Screenshot](https://raw.githubusercontent.com/awaescher/RepoZ/master/_doc/RepoZ-ReadMe-UI-Both.png)

> **"Well ok, that's a neat summary ..."** you might say **"... but how does this help?"**.

If you are working on different git repositories throughout the day, you might find yourself wasting time by permanently switching over from one repository to another. If you are like me, you tend to keep all those windows open to be reused later, ending up on a window list which has to be looped through all the time.

With RepoZ, you can instantly jump into a given repository with a file browser or command prompt. This is shown in the following gif.

![Navigation](https://raw.githubusercontent.com/awaescher/RepoZ/master/_doc/QuickNavigation.gif)

For Windows, use the hotkeys <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>R</kbd> to show RepoM.

<!--
To open a file browser, simply press <kbd>Return</kbd> on the keyboard once you selected a repository. To open a command prompt instead, hold <kbd>Ctrl</kbd> on Windows while pressing <kbd>Return</kbd>. These modifier keys will also work with mouse navigation.
-->
## Documentation

- [Plugins](_doc/Plugins.md)
  - [AzureDevOps](_doc/RepoM.Plugin.AzureDevOps.md)
  - [Clipboard](_doc/RepoM.Plugin.Clipboard.md)
  - [EverythingFileSearch](_doc/RepoM.Plugin.EverythingFileSearch.md)
  - [Heidi](_doc/RepoM.Plugin.Heidi.md)
  - [LuceneQueryParser](_doc/RepoM.Plugin.LuceneQueryParser.md)
  - [SonarCloud](_doc/RepoM.Plugin.SonarCloud.md)
  - [Statistics](_doc/RepoM.Plugin.Statistics.md)
  - [WindowsExplorerGitInfo](_doc/RepoM.Plugin.WindowsExplorerGitInfo.md)
- [Search](_doc/Search.md)
- Settings
  - [Global settings](_doc/Settings.md)
  - [Repository Actions](_doc/RepositoryActions.md)
  - [Filtering](_doc/Filtering.md)
  - [Ordering](_doc/Ordering.md)

## Credits

RepoM is a fork of the amazing RepoZ, which was created by [Andreas Wäscher](https://github.com/awaescher/RepoZ).
