# Creating game servers with Python and asyncio

https://jyrno42.github.io/pycon-2018-underlings

Can a turn-based game be written in Python with the standard API? Jürno will share
his experiences of doing exactly that. You'll learn about networking using asyncio
and making it play nicely with the statemachines.

Keywords: asyncio, networking, statemachines

## Bio

Jürno Ader is a talented Python developer, advocate for open source software
and a lover of all human beings. He enjoys solving difficult problems and making
sure systems are secure. Jürno is a Senior Developer at Thorgate; a Gamer, creator
of django-esteid and a cat person.

## Teaser

Most of us are aware of EVE online being written in stackless python. However, when
python first introduced asyncio, Jürno had one question he wanted to figure out.
Can I write a game server in Python with the standard API? This talk is about
experiences of doing exactly that for a turn-based cardgame with RPG elements. You'll
learn about networking using asyncio and making the protocol play nicely together
with the statemachines which encapsulate the rules of the game.