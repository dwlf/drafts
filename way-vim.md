Title: The Way to Vim

"It is a tool, the use of which [must be
learned](http://www.vim.org/about.php)".

Vim has been my system and software editor for 18 years (1997). I've been a
mediocre vim user this whole time. I've left vim unconfigured and haven't had a
vimrc file.

Two things have changed in my life. I'm now the parent of three children and
I'm working on transitioning to being a software maker. I'm forced to be more
productive and be productive in programmer ways.

Changing how I use vim is also influenced by changes in software systems. The
continued advancement of automation, distribution and virtualization means
logging into server and opening individual text files in unconfigured vim will
only get my so far these days. I suspect the next generation of advanced
technical support and quality assurance analysts will not be able to get the
same value as I have out of unconfigured vim.

Even if you don't want or need to know vim, I would still highly recommend
learning the basics and philosophy of it. Many unix commands use the same keys
. More importantly, you'll get the flavor of the unix philosophy: combining
small, sharp tools.

I've started now to really learn how to use vim starting with [first
principles](http://en.wikipedia.org/wiki/First_principle).  Only as I'm
starting this journey deeper into vim do I begin to understand why I've gotten
so much value out of just using vim. My activities have aligned with "normal"
mode.  I've spent half my life viewing, paging and searching through software
output.

One of the best ways for me to learn is to figure out how I would help someone
else learn, so here it is.

## Small Doses

I was embarrassed to discover just how good the documentation is and how solved
all the problems I thought I had with learning vim are. As I led with, vim is a
tool which must be learned. It is best learned using first principles and
learning in small doses. I'll revisit this. Let's get on with the show.

## Overclock Your Learning

I don't watch or listen to any recorded sessions that I can't adjust the speed of. Thankfully, changing the playback speed is now standard in YouTube. I skim most videos at x2 and watch the meaty parts at x1.5.

If I can't find relevant content on YouTube, then I'll download it and use VLC on my mac or the buggy app [swift player](https://itunes.apple.com/us/app/swift-player-speed-up-video/id545216639?mt=8) on my iphone.

## Get Seated

Mike "mscccc" Coutermarsh provides the best introduction to vim with the
mistitled, [Boston Vim: Learning Vim in a
Week](https://mikecoutermarsh.com/boston-vim-learning-vim-in-a-week/). That
article includes the slides. He has an older article, also mistitled,
"[Learning Vim in a Week](https://mikecoutermarsh.com/learning-vim-in-a-week/)"
in a tip form.

<iframe width="560" height="315"
src="https://www.youtube.com/embed/_NUO4JEtkDw?list=PL8tzorAO7s0jy7DQ3Q0FwF3BnXGQnDirs"
frameborder="0" allowfullscreen></iframe>

## Get Excited

Here are a couple of my favorite videos that after watching mscccc's
presentation got me jazzed to go deeper.

Ben Orenstein's "[Write code faster: expert-level
vim](https://www.youtube.com/watch?v=SkdrYWhh-8s)" [Notes from an older
version](https://github.com/r00k/talk_notes) of the talk are on github.

<iframe width="560" height="315"
src="https://www.youtube.com/embed/SkdrYWhh-8s" frameborder="0"
allowfullscreen></iframe>

Damian Conway's "[More Instantly Better
Vim](https://www.youtube.com/watch?v=aHm36-na4-4)" is crazy. The [show notes and all the code](https://docs.google.com/file/d/0Bx3f0gFZh5Jqc0MtcUstV3BKdTQ/edit) can be downloaded.

<iframe width="560" height="315"
src="https://www.youtube.com/embed/aHm36-na4-4" frameborder="0"
allowfullscreen></iframe>

## Calm Down

I've spent many years delaying learning vim. It's partly, because I'm so
focused in my daily work in promoting making decisions not options. I waited in
frustration for gvim, cream, and macvim to impress me out of the box. I missed
the point and you will too if you copy someone else's vim configuration or
immediately leap to download the most popularly vim plugins. **Your
configuration should evolve to match your own evolving workflow.**

Every vim experience is difference. No one can teach you what works best for you. You will be your best teacher. Be a good student. This takes time. Give yourself the time to learn in small doses.

These are sharp tools for sharp minds. 

## Repeat

Mentioned in a couple of the above sessions is changing how your keyboard works. This is common theme in many vim articles and videos.

    brew cask install karabiner seil
On Mac, we benefit from [Takayama "tekezo" Fumihiko](https://twitter.com/tekezo)'s [karabiner](https://pqrs.org/osx/karabiner/index.html.en). As recommended, I've reducing the delay before key repeat and speeding up the repeat. I currently have "delay until repeat" set to 83 and "key repeat" at 40. I didn't know what I was missing!

I've also installed the karabiner plugin seil to replace caps lock with esc (key code 80).

## Walk

You know that you are going to be spending time in vimtutor and ":h usr", but before you getting into it, let yourself enjoy a "[vim basic motions and commands](https://www.youtube.com/watch?v=Nim4_f5QUxA)" workshop with [Shawn "shawncplus" Biddle](https://twitter.com/sabiddle/).The [class notes](https://github.com/shawncplus/vim-classes/blob/master/expert-1.md) are on github.

<iframe width="560" height="315" src="https://www.youtube.com/embed/Nim4_f5QUxA?list=PL39697668A5E07C69" frameborder="0" allowfullscreen></iframe>

## Keeping Walking

Have you disabled your arrow keys for now?

I think one of the mistakes I've made more than once is giving myself access to the gui. This time around, I uninstalled macvim and discovering that the Apple supplied vim did not include "+clipboard" for allowing vim to ineract with the system clipboard, I ran:

    brew install vim --override-system-vim

## Help

XXX video on help

XXX video on splits

## Your Move
 
I started out focusing on improving my work flow around documenting as that helped keep me mostly away from plugins. What's your next move?

<!-- Help me make this better by providing feedback on the reddit thread or hacker news. XXX insert links after 1st publish -->

## Thank Yous

I've only gotten [Hacker News](https://news.ycombinator.com/) in the last six
months and there is no going back. The community has refired my engine for
personal and software development.

Thank you to [Bram Moolenaar](http://www.moolenaar.net/), the creator of vim,
still leading development 23 years later. `:help uganda`. The welcome text has
changed a little bit, calming people just looking for open source,  but the
message is still the same. It was an incredible concept to me then. It has
continued to inspire me. Its continued to be a reminder to me that I can get
too caught up in just the freedom of the software. Unfortunately, the messsage
is still radical today.

I think Bram's premise has led to vim's community being so welcoming and
helpful. Thank you to [z1mm32m4n](https://twitter.com/z1mm32m4n),
[fatih](https://github.com/fatih), [lcd047](https://github.com/lcd047) and many
others for their patience and generousity in helping me.

Thank you to thoughtbot, who's immensely helped developers get excited and
learn vim, and who [created](https://robots.thoughtbot.com/tags/vim) and
[currated](https://www.youtube.com/playlist?list=PL8tzorAO7s0jy7DQ3Q0FwF3BnXGQnDirs)
a lot of vim educational material.

Thank you to [Drew Neil](https://twitter.com/nelstrom), who's
[Vimcasts](http://vimcasts.org/) dishes out free, perfect bite size vim topics.

We wouldn't have vim, if we didn't have vi. Thank you to Chuck Haley and Bill
Joy for ex and vi. I'll stop as my ancestrial and sibling thank yous would grow
long.

tekezo's karabiner and seil provide essential services to mac users. tekezo is unwavering in [his generosity](https://github.com/tekezo?tab=activity).

[termie](https://twitter.com/termie) and
[novas0x2a](https://twitter.com/novas0x2a) stand out in my mind as inspiring
vim users that I've had the pleasure to work with. Two people that inspire me
with their personalilities, daily successes and ability to make those around
them better.
