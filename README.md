piMyHome
========

piMyHome is a fast web application for the Bticino/Legrand home automation system, running on a Raspberry Pi, a credit card sized and cheap mini computer platform. piMyHome is not a commercial project, it's completely open source and free for anybody. Developers who wanna join us are very welcome. 

Current Status
----
piMyHome ist still in development and not ready yet. First public release is expected in January 2015.

Features
----
- a monitor daemon is fetching OWN messages from your Bticino gateway and stores the state of each device (light, shutter, heating etc) in a Redis value cache
- an event daemon watches what's going on and launches a user-defined action when an event is raised. The action launched can be anything, not just limited to the bticino system.
- a nice and responsive web multi-language frontend let you manage your home automation with any device such as smartphone, tablet, desktop PC or XMBC (TV)
- Access control for user and groups
- Each user can have his own environment and favorites
- Completely managed via browser, no programming skills needed
 
Homepage
----
http://www.pimyhome.org
