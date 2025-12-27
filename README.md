# ChromiumClaudeContext-alfred-workflow

It can be hard to keep track of Claude chats.
You can't have multiple instances of the Desktop app running either.

Just having tabs open in the browser is a mess.
So I came up with this solution:

Open Claude split view at current Chromium tab (I use Arc Browser).
This way the Claude instance is right next to the original content that prompted me to open it.

Will refine later, this is proof of concept.
It's an ugly AppleScript with delays (Arc is slow af on my M1 MacBook), but it works.

[Demonstration](https://www.loom.com/share/8f3b558769024de58e1d4c3f28a0743d)

There are some options for how to use Claude URL:

1. Starting a new chat with a query:
https://claude.ai/new?q=your%20question%20here

This way one could create automated queries.

2. Opening a project:
https://claude.ai/project/alphanumerical-project-code
