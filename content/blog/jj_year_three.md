+++
title = "On three years in the Jujutsu project"
date = 2025-11-03
[taxonomies]
tags=["vcs", "Jujutsu"]
+++

**Intended Audience:** The people from the Jujutsu Discord and random 
bypassers.

{{ note( header="Disclaimer", body="The year I'm talking about is from <br>
2024.11.03 - 2025.11.03, this also has an alternative title <br>
'Three years of whatever this is'") }}

## What happened in the project.

In this year the project moved from `martinvonz/jj` to the Alphabet 
suborganization `jj-vcs/jj` which also led to the logo change away from the 
Jujube, the previous name of the project, to the two blue jays which were drawn
by J.J and got its governance with the first set of Maintainers. We also choose 
to standardize the `change-id:` header in the Git object with both GitButler and
Gerrit. Which Martin then brought up in the Git mailing list.
The standardization of the `change-id` header also brought many 
discussions about the UX of divergence in the project which has improved a bit.
These discussions aren't done yet since it requires the users to understand
that divergence is not a "failure" state and isn't as harmful as conflicts.

The CLA also was a really tiring hot issue this year, in which better 
communication definitely would've helped.

Also [East River Source Control](https://ersc.io) came out of hiding which makes the 
project have three interested parties, Google, ERSC and Open-Source users.

The project also had a new community leader step up as another one stepped
down.

There also was the first convention for the project in Sunnyvale 
California named "JJ-Con", which was colocated with Git Merge 2025. 

## My year

### A bad start until the summer

Honestly my year wasn't great, since I choose to add my name to the 
potential "Maintainer" list where I personally already thought that it was 
unlikely for me to get added (like a 0.01% chance). Since I was the only person
who wasn't chosen it didn't feel great to hear about it on the Jan 1st post 
without receiving a message beforehand. I also stepped into a discussion with
Drev Devault because it was eerily similar to what I'd do or already did in 
the past. While I also had some plans to give the
project docs a better structure, it never happened because I lost my job in 
February. At the same time I also asked someone for their prototype of 
integrating a scripting language with `jj` so I could work on it. I also 
continued my work on the Topics design doc before burning out on it. At various
points early in the year, I've had the feeling of my opinion not being seen 
which resulted in the horrible message I sent in Spring.
I think this could've been entirely prevented by the project having active
moderation, not just people sitting on the sideline. While the conflict 
resolution was quite fast, it affected me negatively for longer which 
obviously isn't great[^1]. It almost resulted in me quitting the project 
entirely. The whole situation forced me to recognize what I achieved in the 
project to get myself back on my feet, it also took some time until I was 
comfortable expressing myself in the Discord again[^1]. This year I lost 
multiple nights of sleep to the project, by just having my name mentioned in 
certain ways and I had various moments where I was questioning my motivations 
in the project, since it had such negative effects on me. In July I was back to 
"normal", if there's such a thing. 

### JJ-Con and Git Merge

And when the CFP for JJ-Con went up in July, I just decided to write a cool 
title for a side-project I wanted to discuss anyway. I was very baffled to see 
that it was the most liked talked during the first three days of voting and it 
was even stranger to me that it held its top five position which allowed me to 
hold the talk[^2]. JJ-Con and the all the events around it were a bunch of 
firsts for me, I gave a [technical talk][mh], held a [discussion][topics] and 
upon the suggestion of Manish held a unconference session which was related to
the current governance. Also Git Merge was smaller than I expected and quite 
nice. I also got to talk to the Sapling developers which were interested in 
the scripting language I proposed for `jj`. There I also was asked if I were 
interested in  working in Source Control which was quite interesting[^3]. 
It also was the first time I've heard that I stand up for the community, which
never crossed my mind since I only represent myself and try my best to consider
what the community wants.

To my surprise I even could attend the Git contributor summit which was an
interesting experience of its own where I tried to push the change-id header
discussion a bit further.

### My pain points with the current Governance

The current governance is doing its job poorly with these points for me:

  * It fails to be any kind of organization, instead it's a bunch of 
    individuals.
  * There's still not any kind of leadership, be it in a social or technical
    manner. Deferring to the community is not leadership for people which 
    should deem themselves as the "core project".
  * It is not transparent at all with its decision making with all the leading 
    steps upon its creation.
  * It also immediately failed to write down the _actual job_ of a Maintainer
    presenting some vague ideas which only the people involved in the temporary
    Governance understand (this excludes a high amount of the community). 
  * It on one hand wants to steer the technical and organizational direction 
    of the project while it hasn't proven it being capable of any of these.

I also don't find it good at all that a majority of the Maintainers can't take
the time necessary for the project only retaining their voting position, if it
comes to that. I mean a Maintainer should be active in the project and 
concerned about its future and not constantly complain about the length of the
PR queue, since they're responsible for the development speed of the project.
I also find it bad capacity planning to make 2/N maintainers responsible for 
a vast majority of code-reviews, since it will create a single point of failure
when one of them has to disappear for internal needs at times. 

Most of the above make my opinion of the Governance lacking, I mean it is OK 
but it definitely could improve and make their position clearer. If I were 
Google I'd wait another year to see how it improves and what pans out.

### Closing

At this point it has been three years since I joined the project wanting to 
write `jj run`. During this time I've answered _many_ questions about the 
project, tried to implement some processes for it and even had a plan on how a 
native future could look. I even recognized that the project has no 
leadership figure and thus drove some decisions even though I was asked to 
step back from this. At this point I've worn many hats, some of them making 
time for own code contributions  harder, this by sometimes shielding people 
from questions and otherwise. I want to write code too. 

It also seems that multiple people in the project think that I'm a Googler 
working on this full-time as a lead, which is both an insult and a compliment.
I have my own reasons to be here, such as making the project a success and 
having an actual Jujutsu-native future, not just as a better Git client. 

I also have thought about enabling GitHub sponsors to give the community a 
way of sponsoring my presence on the project but I find that soliticing money
for something I already do extremely hard. Maybe someone could convince me that
it is a good idea, since my involvement currently doesn't pay for my rent. 

I also could try to get into the Maintainer position next year but I doubt it
will happen even though it would validate all my efforts across the years for 
the project.

At this point I've also have become very interested in making Meta a third 
party involved in the project since someone talked about their use-case in 
the Discord and I always said that I want to write a `jj on EdenFS`. But
that will be in a separate article and which I promised to at least one person.

My last such post ended with my plans for next year, but since I was unable to
implement them this year, I'll just keep on working on my publicly known
projects, which means at some point pulling out the `Topics` design doc out of
the freezer again. 

[^1]: At this point I should have received a warning per CoC but that didn't really happen.

[^2]: I didn't really feel safe for two weeks. 

[^3]: While I've held presentations, this was the first time I ever gave a
technical talk in front of a large crowd.

[^4]: I obviously would like to, but I find it unlikely that I receive a job 
offer from Google or Meta.

[mh]: https://youtu.be/QPp_o3CMJlY?si=fyUkn1ZVw_ONQ0VT 

[topics]: https://youtu.be/JWEFkZr7TIc?si=_kjdXVfyCnqIepgg
