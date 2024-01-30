# Readme
# infosec-starter-kit
A starter set of atomic Markdown notes with internal and external links, organised as a (not quite strictly acyclic) tree of files intended for those getting started in Info Sec

Massive caveat. These are the notes I'm creating at the start of my own journey. I think I'm beginning to get a few clues about what I'm doing but if you're thinking these notes are going to be treatable as 100% inerrant gospel? Not going to end well. Trust but verify.

Suggested use case? You're just getting your feet wet in the infosec ocean and you're all of a sudden finding yourself a bit intimidated by the complexity and size of it all. You're realising you're going to need to document your journey a bit (yeah, get used to that feeling fella) and you want a bit of a framework to start hanging your shiny new knowledge on. But it's feeling a bit chicken and egg. You don't know the terminology, or how it all fits together, or even what most of the pieces are. So you don't know how to structure your notes. Clone this little set of files into a folder somewhere and you'll have a decent enough start.

- The notes are 'atomic' in the sense that each file represents a single concept (or acts as a simple grouping of links to sub-topics) - it talks about one thing and one thing only.
- They're written in Markdown because it's simple, efficient, flexible and future-proof
- The notes link to each other where it makes sense. For example the note about physical security has a link in it to the note about lock picking but it doesn't have a link to the note about IP addresses.
- They're organised approximately as a tree with a root node at [HMFIC](hmfic.md) getting more detailed and specialised the further away from that note you get. But some of the branches connect to each other as you move away from the trunk (for example, `firewall` is a child node of both `filtering` and `network-nodes`) so in terms of graph theory it's not acyclic - the tree has loops in it. My tree, my rules.
- The combination of atomic notes and not-a-true-tree means the linking can represent the richness of the subject. Difficult to explain why but trust me till you work it out for yourself.
- They're aimed at someone getting started. If you've already got your own notes you might want to cut and paste bits and pieces but your structure isn't going to mesh very well with my structure.
- I use [Obsidian](https://obsidian.md/) to store and edit these notes but you could import them into whatever tool you fancy. Just use them as plain (Markdown) text files if you like.
- There are a few Obsidian tags in the files (strings starting with `#`) used for references (`#ref`) and to indicate glossary definitions (`#glossary`)

Are they complete? Ha! You're funny. Well, I *think* they're kind of complete in the sense that you probably won't find any major topics missing but the further down (up?) the tree you go, the more things you'll find you want to add.

How do you add stuff? Couple of suggestions.

1. Fork the repo, add/change some stuff and submit a pull request. There's a quick summary at [How To Pull Request in 3 Minutes - YouTube](https://www.youtube.com/watch?v=jRLGobWwA3Y)
2. I've added a link at the bottom of each file to an extension note file you can put your own personal notes in. These links all point to filenames in a `notes` subfolder. None of the files actually exist because I added an entry to `.gitignore` for the whole of the `notes` subfolder. That's where I put all my personal notes and I suggest you do the same. Think of it as a private notes storage area, great for todo lists or stuff that's not really useful to the wider world.
3. For stuff that you think would improve the experience for anyone else using these notes, make changes to your local forked repo and hit me up for a pull request. Not done it before? Bit scared? Don't be. I promise I'll be kind. This is a great repo for your first experiments with contributing to git projects because you can just drill down till you find a niche topic you're interested in that I haven't mentioned and just add a file. Or fix a typo somewhere. Or add a useful YouTube video to one of the existing subjects. It's not like you have to spend hours trying to get to grips with a complex codebase before you can contribute something useful. Have a go.
