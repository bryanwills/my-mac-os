# My wonderful world of macOS [![Thanks](https://bit.ly/saythankss)](https://github.com/sponsors/nikitavoloboev)

> List of applications and tools that make my macOS experience even more amazing

![](https://raw.githubusercontent.com/nikitavoloboev/my-mac-os/master/night.png)

> Dark appearance. All apps are in one desktop since there is delay in switching between macOS multiple desktops. Dock is hidden. Desktop background is dynamic.

![](https://raw.githubusercontent.com/nikitavoloboev/my-mac-os/master/light.png)

> Light appearance. Use light themes when outside or when there is glare from the sun as it makes text more readable.

- [Applications](#applications)
  - [Productivity](#productivity)
  - [Code](#code)
  - [Social](#social)
  - [Design](#design)
  - [Music](#music)
  - [Video](#video)
  - [Browsers](#browsers)
    - [Safari Extensions](#safari-extensions)
- [Command Line Apps](#command-line-apps)
- [My wonderful world of iOS](#my-wonderful-world-of-ios-)
- [Similar Setups](#similar-setups)
- [Related](#related)
- [Contributing](#contributing)

## Applications

I use a [lot of apps](https://wiki.nikiv.dev/code/config#macos-apps-i-have-installed) on my mac. Below is a list of my favorite tools with descriptions of how I use them.

I also share [my dotfiles](https://github.com/nikitavoloboev/dotfiles) together with my [iOS setup](https://github.com/nikitavoloboev/my-ios). And I made a [Telegram group](https://t.me/joinchat/BBKnQU4_rty6_942PFbPbw) to discuss all things macOS/iOS.

I have [extensive wiki](https://wiki.nikiv.dev) where I share [everything I know](https://wiki.nikiv.dev/sharing/everything-I-know). I go in detail about how I use each of the apps in the wiki. Not to duplicate the content, I simply link to the wiki from here as the wiki will always be up to date.

My workflow in general is described in detail [here](https://wiki.nikiv.dev/sharing/my-workflow).

### Changing themes

I made [KM macro](https://wiki.nikiv.dev/macOS/apps/keyboard-maestro/km-macros) with [this AppleScript](https://www.macobserver.com/tips/quick-tip/change-light-dark-mode-applescript-app/) to switch [between light/dark macOS appearances](https://twitter.com/nikitavoloboev/status/1311336647338983432). As appearances are switched, the themes get updated accordingly on most apps.

### Productivity

- [Alfred](https://wiki.nikiv.dev/macOS/apps/alfred), [Raycast](https://wiki.nikiv.dev/tools/raycast) & [Script Kit](https://wiki.nikiv.dev/macOS/apps/scriptkit) for everything search related. I create many custom plugins to do specific searches I need.
- [Karabiner](https://wiki.nikiv.dev/macOS/apps/karabiner/) is essential tool I use to remap my keyboard. It's the tool on which my entire mac workflow is built. Essentially all the keys on my keyboard are dual purpose keys. Press once, it enters the key, hold together with another key and do custom action. I have 100's of these custom actions all within 1 second of activation for me.
- [Keyboard Maestro](https://wiki.nikiv.dev/macOS/apps/keyboard-maestro/) for all automation needs that are not search related. Both Alfred/Raycast/ScriptKit and KM are activated from Karabiner directly. I share all my KM macros [here](https://wiki.nikiv.dev/macOS/apps/keyboard-maestro/km-macros).
- [2Do](https://wiki.nikiv.dev/macOS/apps/2do) for personal tasks. It has the best onscreen keybinds ever like `y` to move task for due tomorrow. Easily change priority or assign task to list.
- [Height](https://height.app) for project & personal [goals](https://wiki.nikiv.dev/focusing/goals) management. It's one of my main tools to [break down problems as I solve them](https://wiki.nikiv.dev/research/solving-problems) in team or personal setting.
- [1Password](https://wiki.nikiv.dev/macOS/apps/1password) use it to keep all passwords and secret info. I prefer to use Single Sign On via GitHub or Google as I do dislike keeping track of passwords.
- [BetterTouchTool](https://wiki.nikiv.dev/macOS/apps/bettertouchtool) use to for custom trackpad gestures. Specifically love three finger swipe left/right to move between tabs in [Safari](https://wiki.nikiv.dev/web/browsers/safari). Three finger swipe up to create new tab. Three down to close. Four finger swipe global swipe to show Safari. Four to right to open [VSCode](https://wiki.nikiv.dev/text-editors/vs-code). Four left to open [Warp](https://wiki.nikiv.dev/unix/shell/warp).
- [Fantastical](https://wiki.nikiv.dev/macOS/apps/fantastical) use to manage my calendar and events.
- [Dictionary](https://support.apple.com/en-gb/guide/dictionary/welcome/mac) surprisingly useful to [quickly search Wikipedia](https://i.imgur.com/wFkJXwd.png).
- [CleanShot](https://getcleanshot.com) use it for quick editing of screenshots.
- [Transmission](https://www.transmissionbt.com/) is great [BitTorrent](https://wiki.nikiv.dev/networking/peer-to-peer/bittorrent) client.
- [Notion](https://wiki.nikiv.dev/tools/notion) is useful to manage team wikis or share documents with others. Don't like using it as my general knowledge management tool.
- [NetNewsWire](https://netnewswire.com/) use it to read all my [RSS](https://wiki.nikiv.dev/web/rss) feeds.

### Code

- [VS Code](https://wiki.nikiv.dev/text-editors/vs-code) is my main editor and where I spend the most time in aside from [Safari](https://wiki.nikiv.dev/web/browsers/safari). Use and love its [extensions](https://wiki.nikiv.dev/text-editors/vs-code/vs-code-extensions). Keep my UI minimal and useful.
- [Sublime Text](https://wiki.nikiv.dev/text-editors/sublime-text) use it for [quick edits of markdown, specifically my wiki](https://wiki.nikiv.dev/other/wiki-workflow). It opens up instantly and is joy to edit in. Have custom [KM macros](https://wiki.nikiv.dev/macOS/apps/keyboard-maestro/km-macros) such as quickly creating markdown links and other little useful actions.
- [Sublime Merge](https://www.sublimemerge.com) use it as visual Git client. It gives nice overview of files changed, what branches exist and more. I have custom actions bound to go through Git tasks fast. I also use [gitupdate](https://github.com/nikitavoloboev/gitupdate) for throwaway commits either on PR branches where main commit will be written when squashed or some random doc related repos.
- [Dash](https://kapeli.com/dash) use it to [search for APIs fast](https://i.imgur.com/P5LQaLz.png). Use it through [Alfred workflow](https://www.alfredapp.com/blog/productivity/dash-quicker-api-documentation-search/).
- [Paw](https://paw.cloud) use it for sending HTTP requests as I test endpoints.

### Social

- [Telegram](https://wiki.nikiv.dev/tools/telegram) use it as my main messenger and absolutely love it. Love its stickers, the speed and honestly everything about it.
- [Spark](https://sparkmailapp.com) use it as my email client. Does good job of sorting mail and getting out of my way when writing/replying to things.
- [Discord](https://wiki.nikiv.dev/tools/discord) use it the main way to interact with various communities. Much better than [Slack](https://wiki.nikiv.dev/tools/slack) as it keeps the history forever and recently added a nice Forum feature better question asking.

### Design

- [Figma](https://wiki.nikiv.dev/design/figma) use it as my primary design tool.

### Music

- [Spotify](https://www.spotify.com) use it to stream all [my music](https://wiki.nikiv.dev/music). Keep all my liked songs in a [playlist](https://open.spotify.com/playlist/0ERn0U4qZIKC8Dy7RrMMsn).

### Video

- [IINA](https://github.com/lhc70000/iina) use it to play video files of movies/series.

### Browsers

- [Safari](https://wiki.nikiv.dev/web/browsers/safari) spend majority of time on mac in the app.
- [Google Chrome Canary](https://wiki.nikiv.dev/web/browsers/google-chrome) use Canary over regular as I don't use Chrome for browsing but for development as its [dev tools](https://wiki.nikiv.dev/web/browsers/google-chrome/chrome-dev-tools) are superior. Sometimes canary builds break so I go to regular Chrome.

## Command Line Apps

Use [Brew](https://wiki.nikiv.dev/package-managers/brew) and global [pnpm](https://pnpm.io/) packages for most of my CLIs. Although eventually want to settle down on [Nix](https://wiki.nikiv.dev/package-managers/nix) as I learn it more.

I try to keep my macOS declarative. Currently it's a [Go file](https://github.com/nikitavoloboev/dotfiles/blob/master/magefile.go) in my [dotfiles](https://github.com/nikitavoloboev/dotfiles) and is not up to date.

I list CLIs I use [here](https://wiki.nikiv.dev/cli).

## [My wonderful world of iOS 📱](https://github.com/nikitavoloboev/my-ios)

If you found this interesting, I also have [similar repository](https://github.com/nikitavoloboev/my-ios) going over what applications I use on iOS/WatchOS as well as how and why I use them.

<a align="center" href="https://github.com/nikitavoloboev/my-ios">
    <img width="250" heigth="400" src="https://images.nikiv.dev/my-ios-screen.PNG"></a>

<a align="center" href="https://github.com/nikitavoloboev/my-ios">
    <img width="250" heigth="400" src="https://images.nikiv.dev/my-ios-screen-2.PNG"></a>

<a align="center" href="https://github.com/nikitavoloboev/my-ios">
    <img width="250" heigth="400" src="https://images.nikiv.dev/my-ios-screen-3.PNG"></a>

## Similar Setups

Here you can find more setups by other people that you can take ideas and inspiration from.

- [Works for me](https://works-for-me.github.io/) - Collection of developer toolkits.
- [Use This Interviews](https://usesthis.com) - What do people use to get stuff done?
- [Omar Bahareth's my-mac-os](https://github.com/obahareth/my-mac-os) - Another my-mac-os.

## Related

- [Awesome mac](https://github.com/jaywcjlove/awesome-mac)
- [Interesting macOS apps](https://github.com/learn-anything/macos-apps)
- [Open Source macOS apps](https://github.com/serhii-londar/open-source-mac-os-apps)

## Contributing

If you shared a similar personal setup to this, be it for Windows, Linux or anything else, you can add it in [Similar Setups](#similar-setups) section.

I love finding new awesome tools and apps. If you have a favorite tool or app that you think I missed, please [say it](../../issues/new).

## Thank you

You can support me on [GitHub](https://github.com/sponsors/nikitavoloboev) or look into [other projects](https://nikiv.dev/projects) I shared.

[![CC4](https://img.shields.io/badge/license-CC4-0a0a0a.svg?style=flat&colorA=0a0a0a)](https://creativecommons.org/licenses/by/4.0/) [![Twitter](http://bit.ly/nikitatweet)](https://twitter.com/nikitavoloboev)
