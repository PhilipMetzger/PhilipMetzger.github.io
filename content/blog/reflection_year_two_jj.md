+++
title = "Reflecting on two years on the Jujutsu Project"
date = 2024-12-22
[taxonomies]
tags=["vcs", "Jujutsu"]
+++

**Audience:** The people from the [Jujutsu Discord][dc] and random bypassers.

{{ note( header="Disclaimer", body="This is my page, so I'm allowed to liberally critize myself.<br>
If you disagree with that feel free to keep it to yourself. <b>It is my own choice.") }}

The project has grown by a sizeable amount and as such also the Discord. While
this makes it less comfortable to me, it shows that this is the right approach
to a new VCS. 

On the other hand, it was a strange year for me in the project, as judging by 
the [Testimonials] page which I added to the docs made me a "Developer"
(thankfully no Maintainer yet).
I see myself as a fine technical contributor, but my social skills sometimes 
are not the best and mixing that with strong opinions is a dangerous concoction.


## The Bad (aka making mistakes)

During early Spring this year, I made some mistakes and was a undoubtely 
a bad _contributor_ to the project.

 * It started with my [giant fuckup][fu][^1]. And as I believe actions should 
   have consequences, this led to a very personal offer to  @martinvonz 
   and the formation of a [Governance structure][gov]. 
 * Then the whole `prev/next` debacle also wasn't great to continue that 
   streak, where once again my _strong_ words did not help anyone. 
   I believe that my reactions there were _toxic_. 
 * And to top it off, the whole hook discussion also strained me heavily. Here
   I am thankful for the private conversation I had with Matt (@msta).

All of these interactions were not beneficial to me, or my mental state
which led to the reoccurring thought of just resigning from the project. While
this solves the immediate issue, it doesn't remove my interest in project 
itself and I think keeping me around as a person with some strong opinions 
can help the project grow further. And as I owe everyone the `jj run` 
implementation, it is hard to disappear into shadows. 

After taking a healthy break this summer, my attitude finally improved towards
the project and I got my motivation back to work on `jj`.

## The Good

I was motivated to continue my work on `run` after taking a break. 
Hopefully it is in a MVP state now. Then Matt (@msta) started the initial work
on `jj api` which won't be finished any time soon, as it will need to grow
with the project.

Then we also went ahead and [renamed Jujutsu's branches to bookmarks][rename], 
which opens the path for [Topics] and solidifies it as our first term 
(although a similarily named but different mechanism exists for Mercurial).

## Looking forward in the Project

My personal goal for the next year is to finish `jj run` and give others 
some room with it, I think both @hooper and @arxanas can improve it.

The things I really want to get in for next year is [Topics], where I also 
was heavily involved and get the ball rolling on interchanging Change-IDs in
the Git protocol and the start of some kind of native repository/server to 
begin modeling the world from Jujutsu's eyes, as importing terms from Git never 
helped the project. 

I also want the more powerful aliases, so we can deprecate `jj commit` and make
it a configurable alias for those who want to stick to the 30 years of VCS 
history.

On the docs side, I still want to completly restructure them when Steve 
Klabnik's tutorial lands. As they're a bit incoherent.

## Conclusion 

This was the year of communication failure, both in the project and at 
`$WORK`, where my frustration from work clearly affected my behavior in the 
project, which definitely wasn't what I wanted. I also will stick around for 
now, although always keeping a self-ban in mind.

I've also really tried to improve on my communication which is something I 
intend to keep up for next year (I expect occassional relapses, but such is 
life). 

[^1]: Macro-expanded [here][fu2].

[dc]: https://discord.gg/dkmfj3aGQN
[fu]: https://github.com/jj-vcs/jj/pull/2842#issuecomment-1979068782
[fu2]: https://github.com/jj-vcs/jj/pull/3218#pullrequestreview-1917415818
[gov]: https://github.com/jj-vcs/jj/discussions/3877
[rename]: https://github.com/jj-vcs/jj/pull/4341
[Topics]: https://github.com/jj-vcs/jj/issues/3402
[Testimonials]: https://jj-vcs.github.io/jj/latest/testimonials/
