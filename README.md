# `.oo3` to Obsidian

I use the app [MarginNote](https://www.marginnote.com)
to breakup my PDF files into more workable chunks,
however for the actual notes themselves I use
[Obsidian](https://obsidian.md) to view and edit them.

This is (eventually) a quick script to turn the `.oo3`
files that MarginNote exports into a directory of `.md`
files that can be loaded in Obsidian (or any other markdown editor really[^1]). 

[^1]: If you want to use the generated markdown files outside of Obsidian I would
recommend running them through the [zoni/obsidian-export](https://github.com/zoni/obsidian-export)
project first to turn the `[[wiki-links]]` style into standard markdown `[...](...)`.
