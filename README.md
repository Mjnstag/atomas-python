# atomas-python 

This project was meant to be a first try at using pygame and probably is not optimised algorithmically or advised code language usage in any way.

It consists of a basic implementation of the mobile game [Atomas](http://sirnic.com/atomas/). Currently it does not feature any features outside of the normal atom fusing and the usage of the "plus" and "minus" atoms, as well as an upper limit of which atom can be reached.

In addition to this, some assumptions have been made regarding game behaviour, such as spawning rates. This was primarily done using this [stackoverflow post](https://gaming.stackexchange.com/questions/255280/in-atomas-what-determines-the-next-element-a-player-receives) as well as the [Atomas fandom wiki](https://atomas.fandom.com/wiki/Atomas_Wiki). One example of this is that in the mobile game "minus" atoms can spawn more randomly. In this version they are spawned every ~20 turns.

TODO:
- [ ] Add "shiny" atoms behaviour (8+ atoms fused at once)
- [ ] Game over screen in window and not in console