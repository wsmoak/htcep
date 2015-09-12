
Hello!  I'm so excited to be here.  The conference has been great so far and I have trouble deciding which talk to go to!

I'm going to be talking about Why and How To Contribute to Elixir and Phoenix.  Not because you couldn't figure it out if you really wanted to, because most of you are developers working on your own projects, so you know how to write code and use GitHub.

It's precisely *because* you're busy developers working on your own projects that I want to a chance to convince you why you *should* contribute, and then show you where they keep everything around here so you don't have to go digging for it.

Just so I can get a feel for the audience, who has already contributed to an open source project, you've forked the code or the docs, fixed something, and submitted a pull request?

And now who never has?

Is there anyone who is more focused on documentation and answering questions?

That's great!  By the end of this talk I hope everyone is ready to contribute something to Elixir, Phoenix, or one of the many surrounding projects.

So, a little about me.  I got involved in open source waaaay back (I had to look this up) in 2005.  I started asking questions on some Apache Software Foundation mailing lists, and then I started answering them and fixing the documentation, and the rest is history.  I was invited to be a committer and an Apache member and was recruited into a startup to do consulting and... it changed my life.

Now I do tech support at Chargify, where we automate recurring billing for subscription services so that people can focus on building their business.

I came to Elixir by way of the development team at Chargify who kept mentioning it over and over.  Initially I thought they were talking about Yet Another JavaScript framework and I ignored them, but eventually I took a look at it and tried it out.  And then I started asking questions and trying to answer them... and we'll have to see where it leads this time.

So Why should you contribute?  Why would you want to spend any of your limited free time working on this stuff and not getting paid for it?

Well the traditional reason is "scratch your own itch" and if you're working on your own project and something in Elixir or Phoenix isn't doing what you want it to do, discussing and possibly changing it is great.

You might also see someone else with a need, but  maybe they're not quite at the level of being able to fix it, so maybe you can help them out.  As long as there's a valid use case for a change, based on what I've seen so far, the core developers will consider it.

And when you fix someone else's something, you instantly have a new friend!  You'll also meet people doing all the other things we'll talk about later.  I've been lucky to get to go to conferences and actually meet some of the people that I've known for years online.

Maybe instead of having a real world problem, you just want to learn something new.  Functional programming is all the rage these days, right?  One of the BEST ways to learn something is to teach it, so dive in, figure it out, and write a blog post about it!

I'm not kidding, open source can get you a job.  If you get involved, start writing, get really, genuinely *interested* in something, that enthusiasm will shine through and it's really, really attractive to employers.  (Or at least, it is to the kind of employers I'm interested in working for!)

So let's assume I've convinced you that you definitely need to contribute.  What kinds of things might you do?

Well the very first thing you can do is ask questions.  Just Ask.  If you are confused about something, chances are you are not alone, and the other person may not be brave enough to ask.  So put aside your fear of looking silly, do your research and come up with a good question, and ASK.

A note about WHERE to ask.  When I got involved in open source, there was a project mailing list.  And that's pretty much it.  Now there are SO many places to ask!

There's a table in the handout that attempts to sort out what goes where.  For example, the 'core' lists are where the developers discuss features and such, so if you have a question about how to do something using the latest release, that goes on the 'talk' list.  We'll talk about when it's okay to use the 'core' list in a bit.

Stack Overflow is great if you have a well thought out question with a code snippet, and you'll get a wider audience, but it can be a rough crowd.  The mailing list is nicer. :)

There are Slack and IRC channels.  Slack tends to be a little less formal, and also on IRC you're likely to find the core developers discussing some implementation detail and it can feel a little less like you should drop your beginner question right in the middle of that.

One word about archives.  I don't think the Slack channel is archived forever, so please if you get a good answer, or if you see one go by, take some time to write it down.  IRC does have logs on BotBot.Me, but they're not indexed and it's very hard to search and find questions and answers unless you happen to remember, "Someone asked about that recently".  And even if you find it it's hard to link to a discrete discussion because other things may be interleaved.

## Documentation

This is where I start with any project, and I encourage you to as well.  For one thing, read it all!  There isn't TOO much of it yet.

You will be my hero if you keep an eye on Slack and document just *one* question that got a great answer so that it doesn't disappear and have to be asked again.

## Reproduce a Bug

One thing you can do to help is simply confirm that someone else isn't seeing things.  You can set up and run their example code and tell them whether or not you get the same error.

Sometimes, just in the process of doing what you think they said they did, you'll do something different, and it will work.  Then you can backtrack and figure out what you did differently, and tell them what worked for you.  Or, you can confirm that yes, it really does do Y when you press X, and agree that it really shouldn't do that.

Which brings us to...

## Report A Bug

So you've reproduced what someone else is seeing... should you go straight to the issue tracker and start typing?  Not Yet!

First you should search the issues (including closed ones) to see if it's already in there.

Next you should see if it can be reproduced with the latest and greatest version of the code available.

Which brings us to...

## Hacking on Phoenix

Phoenix comes in two parts, the Installer (which is what you're using when you type mix phoenix.new -- it's a Mix Task) and the framework itself, which gets pulled in as a dependency in your project.

Despite the fact that the installer comes first, it's actually *inside*

## Hacking on Elixir

Elixir itself is actually *super* simple to build.  This is what it looks like:

git clone ...
cd elixir
make clean test
set environment variables




And now that I've shown a few ways for you to get more involved, what ideas do you have that would get more people active?

What about pairing with someone?  I would *love* for the community to organize meetups -- Zoom is fabulous and only $15 a month.



