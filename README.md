# Hi! Welcome to my Github.

![](https://nonsense.mpwb.xyz/about/photos/dm.jpg)

The most important thing about this profile is I'm not really here that much.
Well, my work goes here (you probably can't see it), but my [personal projects
live on infrastructure I control][explore].

On [my website][website] you can read more [about me][about], [my
homelab][sunshine], [how to write a queue in Erlang][q-er], or other
miscellaneous topics.

## Current Projects

### Infra: [infra/servers](https://code.mpwb.xyz/infra/servers)

My homelab is a couple of mini PCs, a computer that I built, and a VPS in
someone's cloud. Like most well-organised servers, they are held together by too
much YAML, which is exactly the case for me.

My one-and-a-bit node setup doesn't really call for anything too exotic, so it's
a lot of hand-written Ansible playbooks.

### Dotfiles: [mpwb/dotfiles](https://code.mpwb.xyz/mpwb/dotfiles)

I've been maintaining my dotfiles repository for well over a decade now. Every
few years I dive back through history and find things a past version of me did
that I now find neat and clever. But for the most part, this is just a snapshot
of how my computers work. I'm extremely fussy about that.

### (n)vim-mbnotes: [mpwb/vim-mbnotes](https://code.mpwb.xyz/mpwb/vim-mbnotes)

I had some free time over a holiday, and wanted a notes system that truly worked
for me. So I built it in vim9script, which was a lot of fun but probably a
mistake. Even more so because last year I switched (back) to Neovim, which
doesn't support vim9script. I have some plan to port this to Lua one day, but I
haven't gotten to it yet.

I went arguably way too hard with this, so it has a comprehensive help text,
which is where I'd recommend you go if you're curious.

<details>

<summary>See some (much) older projects on my Github</summary>

## Archives

One thing my Github has that won't be on my Forgejo instance is a whole bunch of
old stuff. 

### [Eisenhardt][eisenhardt]

Back when Magento 2 was new, Docker was only slightly less new. Containers have
been an interest of mine for a long time, and I wanted to use them for work
because I was equally sick of non-compliant local environments and virtual
machines.

While old as hell, I'm still pretty proud of this! I was running non-privileged
containers, integrated debugging, all the additional software in the stack,
separate networks, custom images, the works. Truly ahead of its time!

### [YouTube Sync][youtube] (February 2017)

For his PhD, [my dad][dad] was experimenting with recording improvised concerts
from different perspectives, and analysing the difference in audience experience
based on that. Over an evening we developed a little web application that he
could configure to allow easy switching between the different recording points.

The software takes a collection of time-synced videos hosted on YouTube along
with co-ordinates of the other cameras visible from within any given frame. We
rendered buttons that switched between them with timestamped links.

### [JQuery Data][jquery] (November 2014)

I wrote a blog post on a previous incarnation of my website that dove into the
implementation of the venerable jQuery's Data API. I had a lot of fun doing
this, and even went as far as writing my own test runner for it.

I should corral all of my writing into one place some time, but until then, the
accompanying post can be read on the [Wayback Machine][wayback].

### [Psym][psym] (March 2014)

I wanted to build a symbolic mathematial engine! Something that could do
pretty-printed calculations. I never got to building an actual parser, but the
structure took inspiration from JSX and other similar technologies.

</summary>

[explore]: https://code.mpwb.xyz/explore/repos
[website]: https://nonsense.mpwb.xyz
[about]: https://nonsense.mpwb.xyz/about/
[sunshine]: https://nonsense.mpwb.xyz/posts/project-sunshine-part-2-the-metal/index.html
[q-er]: https://nonsense.mpwb.xyz/posts/queueing-in-erlang/index.html

[eisenhardt]: https://github.com/maxbucknell/eisenhardt
[dad]: http://dafmusic.com
[jquery]: https://github.com/maxbucknell/jquery-data
[wayback]: https://web.archive.org/web/20190129173936/http://www.maxbucknell.com/blog/2014/11/27/jquery-data-everything-you-ever-wanted-to-know-but-were-afraid-to-ask
[psym]: https://github.com/maxbucknell/psym
[youtube]:https://github.com/maxbucknell/youtube-sync
