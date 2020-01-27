## scpl-starter-kit

Usage:
1. Run `npm run dev`, you'll get the shortcut path from local server
2. Using [`remote-installer`](https://gist.github.com/realdennis/e95b4ae6c04d1717d6d2a831dd0b99ff) to fetch this shortcuts.
3. Enjoy it.

Feature:
It will hot watch when you modified the `src/index.scpl`, so that you can update and download it as soon.

Goal:
Our goal is build a clear way to build the shortcut project, and we might release the `.shortcut` file in to different static assets service, make a git-flow / contributor friendly repo using this template, and release automatically.

So that, developer could focus on code / test / review, and user only need to use something like `remote-installer` (or maybe iOS will enable in the future), to download the shortcuts.