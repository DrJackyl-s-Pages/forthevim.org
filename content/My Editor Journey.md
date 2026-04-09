+++
title = "My Editor Journey"
date = 2026-04-03
+++

How I arrived at Neovim after years of lacking an editor that I liked as much as I liked Sublime Text at the time I got to know it.

<!-- more -->

With regards to editors I came long way from Sublime Text via disappointing intermediates and Vim to Neovim. I started using Vim, when I began with Zed Shaw's "Learn C the hard way" (which I never finished). He recommended to use a plain text editor, and also to not put the course material next to the editor, so one could copy the code, but rather look at the code in the course material, memorize it, switch to the editor with the course material hidden, and write it from memory.

I liked this idea and started having "no IDE days": I would code in a plain text editor, from memory, build from command line, go through the compiler errors in the build output, navigate to the code and fix it. This also meant to manually edit the project files - csproj files at the time, as I was working on Xamarin based iOS apps. When I returned to the IDE the next day, I felt like having super powers, because I knew what I wanted to type before I looked at auto completion. Auto completion now was "just" speeding me up, like what it was supposd to do, not to be a shortcut for being lazy and not remembering. I appreciated the knowledge and intuition I gained over my code base. I can recommend "no IDE days" 😉

As I wanted to look into Vim for a long time, the "plain text" editor of of my choice became Vim. And for simple plain text editing getting used to Vim didn't add too much friction.

At some point, I discovered, that there was an official Swift syntax highlighting plugin, which still exists to this day[^1]. I can remember being amazed, installed that, but I can also remember, I didn't want to dive deeper into Vim at the time. But I registered this domain (forthevim.org), for when I would then finally... \<cough> - anyways.

Some years later, I had become Tech Lead iOS in the meantime, I had one of those nerd discussions with an Android Tech Lead and he talked about LunarVim[^2] and AstroNvim[^3]. When I saw the screenshot of these two configs, I was hooked: How freakin' cool did these TUIs look! Months later, I guess I had headroom, I decided to install Neovim and the AstroNvim config. Boy, was that a rough ride - coming from other experiences, where most of the things "just work". This was also pre-AI, where finding, reading and understanding information was a bit more difficult, than it is now. Because it wasn't easy, because it had to be conquered, it had some appeal to me.

Though, it wasn't before 2024, when I forced myself to switch. It was still frustrating at times, but with AI available, it also had become much easier to figure things out. - "Is there a way to 'navigate back', when I jumped to a symbol's definition?" - "Sure, there is the jumplist[^4], which you can open with :jumps and with \<C-o> and \<C-i> you can jump back and forth." - "Nice…"

Since then I've been using Neovim with the AstroNvim config. I've been wanting to dive deeper into lua and create my own config, eg. from kickstart.nvim[^5], but didn't get to that, yet. Besides my default config for coding and text editing, I have a config variant via a git worktree and NVIM\_APPNAME, which has the obsidian-nvim plugin configured for working with my Obsidian vaults. As I have a Steam Deck and switched to Linux on my Gaming PC, I also want to look into managing my dot files using git and GNU Stow.

So, here I am, having used Neovim for a while now and appreciating it. Overall, that push led to exploring the terminal, CLIs and TUIs much more. I keep looking into other editors at times, like Zed for example. I even made peace with VS Code, which I use from time to time. But nah, thanks.










---

[^1]: [github.com/swiftlang/swift/tree/main/utils/vim](https://github.com/swiftlang/swift/tree/main/utils/vim)
[^2]: [LunarVim](https://www.lunarvim.org)
[^3]: [AstroNvim](https://astronvim.com)
[^4]: [Neovim Docs :jumps](https://neovim.io/doc/user/motion/#%3Ajumps)
[^5]: [github.com/nvim-lua/kickstart.nvim](https://github.com/nvim-lua/kickstart.nvim)











