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

Are they complete? Ha! You're funny. Well, I *think* they're kind of complete in the sense that you probably won't find any major topics missing but the further down (up?) the tree you go, the more things you'll find you want to add.

How do you add stuff? Couple of suggestions.

1. Try to minimise the changes you make to the stuff I've supplied. If you want to get updates, the things I change on my end will conflict with any changes you've made. You can use `git stash` to get around this as described at https://stackoverflow.com/questions/10414769/git-pull-keeping-local-uncommitted-changes but it's likely to be a bit of as shit experience. I've tried to add (but I'm also a bit of a shit experience, so I might miss some - yeah, I know, write a tool) a link at the bottom of each note to a note extension note file you can put your own notes in. I've added an entry to `.gitignore` for a `notes` subfolder. That's where I put all my personal notes and I suggest you do the same.
2. Just grab a copy of my notes as a one shot deal and don't bother trying to keep your notes up to date with my notes. Definitely the simplest approach and the one that was in the intended spirit of the project to start with. To some degree you need to make your own notes, about the things that interest you, in the way that suits you, all on your own. Big pants on.
3. If your notes are worth including, send me a pull request.
4. Why should you not fork it? Well, you could... But if they're your own personal notes, for your own personal use, why would you bother? If you want to share your updates with the world, pull request (or just send me a message) would seem a better way to have a central resource. You do you though.
