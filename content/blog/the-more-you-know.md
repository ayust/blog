+++
title = "The More You Know"
draft = false
date = "2016-10-16T16:24:35-07:00"

+++

{{< figure src="img/themoreyouknow2.jpg" >}}

**The more you know, the harder it is to build things.** I think
this primarily stems from something akin to movie spoilers: there
are many things in tech that, once you know about them, they are
impossible to un-know.

Performance. Security. Modularization. Accessibility. These and
many other concepts, things that are typically not on the mind of
the novice developer just starting to play around with creating a
web application. In the mind of that novice developer, there is
just a simple vision of what they want the thing they are building
to look like, and 100% of their effort goes towards either making
that thing or learning the new skills they need to make that it.

As a developer grows more experienced, however, they gradually
become aware of other concepts, other things to factor into how
they build. Things that can easily distract from or delay moving
towards their vision.

* They accidentally introduce an XSS vulnerability into their
application. From then on they make sure to use templating
libraries for all of their dynamic HTML generation, rather than
just concatenating strings.

* They learn about how over time a code base can develop into a
giant mess of spaghetti code. From then on they make sure to
organize their code neatly into modules and create separations
between chunks of functionality.

* They have their first encounter with a slow database query that
prevents anything else from loading. From then on they always
build their applications to support parallel or asynchronous
request handling.

* They read an article about the impact of accessibility failures
in web applications. From then on they are careful to incorporate
the necessary accessibility features into their projects and check
for other issues.

Don't get me wrong: these are all important elements to take into
account when building excellent web applications. The things a
novice programmer builds tend to not be what they would want to
ship a few years later. But the higher bar inherently takes more
effort to reach.

That higher bar can be daunting when starting a new project. It's
worth taking a moment at the beginning to think about your what
your priorities are. For many projects the right priority is
realizing your vision, and the added complexity of doing things
"right" needs to wait until later.
