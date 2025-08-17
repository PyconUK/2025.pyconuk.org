---
layout: post
author: The PyCon UK team
title: An interview with Hynek Schlawack
---
We’re delighted to share an interview with one of our keynote speakers for PyCon UK 2025, Hynek Schlawack. Hynek kindly took the time to let us pick his brains about his first steps into programming, his career, the projects that inspire him today, and what he’s most looking forward to when he joins us in Manchester this September. Let’s dive in!

#### 1. What first got you interested in programming, and how did your journey with Python begin?

Curiosity! My way into programming is very odd, because like many Eastern European immigrants, I grew up in an education-first-but-financially-challenged household. That means I was encouraged to do more than gaming with my Amiga 500 that I got very late in its lifecycle, and that I used a tuned Amiga 1200 into the early 2000s.

The whole time I was piecing my programming education in AmigaBASIC together from library books that were often for different computers altogether. But it was endlessly fascinating for me to watch the computer do things I told it to do!

Later I switched to Pascal and even later to C which accompanied me for much of my career – but I remained starved for information on how things actually work until the rise of the web. It’s also wild to think how expensive compilers and reference material were back then!

My transition to Python happened as for many of my generation of Python web-adjacent developers: I got sick of Java. I started my first big work Python project in 2009 (using Python 2.5 and Pylons – Pepperidge Farm remembers!) the rest is as they say history.

Notably, this was the first time in my life that I felt I was part of a real, open community. Maybe that was fueled by the not-terrible Twitter back then, but it’s something I’ve failed to find in my secondary language years later. I choose to think we’re special!

#### 2. What have been some of the most rewarding or surprising moments in your career so far?

It’s cliché, but it’s the interactions with the Python community. I need to stress this: for people who serve the community in one way or another like I do, it’s absolutely vital to meet the community. It’s very nice to get a heart emoji or even money online, but it’s transforming to talk to people in real life who tell you that they’re curing cancer with your software, got into public speaking because you were encouraging to them two years ago, or that they appreciate your YouTube videos specifically because they’re also non-native English speakers.

So, that’s my advice for everyone who’s feeling burned out and/or unappreciated for their work: go to conferences and meet your users/readers/viewers – it’s extremely rewarding.

#### 3. Could you tell us about a current project or idea you’re excited about — professionally or personally?

From my open-source projects, it’s clearly [https://svcs.hynek.me/](https://svcs.hynek.me/) that I gave a lightning talk on at the last PyCon UK! Unfortunately it’ll probably never reach mainstream interest, given the problems it’s solving. But those who use it, tend to love it!

People tend to get more excited by my more conventional projects, but they’re usually not solving problems in novel ways while svcs is genuinely unique in the Python ecosystem.

When thinking about larger scope projects, I’m of course excited about my new-ish YouTube channel: [https://www.youtube.com/@The_Hynek](https://www.youtube.com/@The_Hynek)

#### 4. How has the Python language and community shaped or supported your work over the years?

I’m almost entirely community-made!

When I started using Python, I was already five years out of college and had written software for the bigger part of my life. But my approach to programming today resembles nothing of what it did back then. I was shaped by lucking into the quality-obsessed corners of the Python community like CPython core, Twisted, or Pylons/Pyramid and by my constant drive to get better at designing robust software. I think part of my arc is the humbleness to know that I’m not an exceptional programmer at all – so I’m trying to find ways to compensate for that with guardrails like comprehensive test suites, type hints, and being strict about design.

Nowadays, it’s my turn to support the community intellectually, and the community mostly supports me back financially through GitHub Sponsors, thanks.dev, and Tidelift, which I’m incredibly grateful for and the only reason I can attend PyCon UK for the second time!

#### 5. What are some of the challenges you see the Python ecosystem facing today — and what gives you hope for the future?

I think the Python community is facing pretty much the same challenges any other open-source community is facing: many people are making commutatively trillions of dollars with Python, but only select few are giving back such that the PSF had to suspend their grants program which is heart-breaking.

And we’ve seen what a difference money can make to a community if spent well! Whether it’s the amazing work our developers-in-residence do (paid for by Meta, Bloomberg, Alpha-Omega, and an anonymous donor) or Astral’s decision to burn VC money to fix Python packaging.

Technologically, Python seems fine to me. It’s a bummer Microsoft dissolved the performance group, but free-threading (aka nogil) is a huge deal that opens many doors as does the continuously improving support for iOS, Android, and WebAssembly.

Finally, as far as governance goes, the PSF and the Steering Council seem to be set up for success, too. Every person I know on those bodies is all-in with their hearts and wants only the best for Python.

#### 6. This year, you're joining PyCon UK as a keynote speaker! What are you most looking forward to about the event?

My biggest memory from my first-and-only PyCon UK 2023 is how warm and welcoming everyone was. In my experience, smaller local conferences tend to be a bit insulated from the larger Python ecosystem or, as a friend once called it: The PyCon US Cinematic Universe. So, introverted by nature, I often end up wandering a bit aimlessly. Not so in Cardiff! I felt like I’ve always been part of the community from day one – so that’s what I look forward to happen again. :)

#### 7. Without giving too much away, what’s something you hope the audience will come away thinking about after hearing your talk?

Like many keynotes, I want people to feel good about one thing and be motivated to improve another.

#### 8. Have you spent much time in Manchester before? Are there any places you're hoping to explore while you're here?

I have never been to Manchester, so I hope I’ll overcome my laziness and do some serious sightseeing. This very much dates me, but when I hear of Manchester, my first thought to this day are Eric Cantona‘s pulled up shirt collar and kung-fu attacks – let’s see if this will change!

#### 9. If you could invent a new Python standard library module for any task (serious or silly), what would it do?

This might sound weird, but I wish we had a great high-level sync/async HTTP client in the standard library that is actively maintained by a dedicated team of (paid) domain experts and that has looser backwards-compatibility requirements than the rest of the standard library.

The last part is important, because HTTP is ever-evolving and, for example, as of now, the URL parsing module has all kinds of bugs and edge cases that can’t be fixed due to Hyrum’s Law <https://www.hyrumslaw.com/>. I’ve seen several fixes being rolled back because they broke something obscure.

The reason why I’d like to have one in the standard library is seeing how over the years the “good client” shifted around. Having had insider knowledge of its development process, I was never a fan of requests, and now httpx is starting to give me concerning vibes too. An HTTP client is very complex software, but I feel very strongly that in a mature ecosystem like Python, making an HTTP request really shouldn’t require in-depth research of all the alternatives. So maybe we should make a concerted effort to fix this.

But the adage of “packages go to the standard library to die” is definitely true, because the inclusion enforces a major slow down on development and a strong filter on possible changes. Therefore, for this to work, we would have to tread unprecedented territory policy-wise.


#### 10. If you could time travel to the very beginning of Python — or jump 10 years into its future — which would you choose, and why?

Despite all the proof to the contrary, I choose to be an optimist and believe that the world will still exist in 10 years and I would love to see what will have happened to the language by then!

**And that's a wrap!**


Thank you very much Hynek, for taking the time to participate. We look forward to seeing you on stage in September 🚀
