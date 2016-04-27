# the-goldman-clause MMAI 17: Spiders Final Submission

This repository contains the final submission for team "the-goldman-clause" in the Spring 2016 MegaMiner AI Competition
run by SIG-Game at the Missouri University of Science and Technology. All files except `games/spiders/ai.py`
are part of the provided Python client, so to see what this AI does differently than others, look there.

Here is a complete description of the AI:

1. Spawn as many `Spitter`s as possible.
2. Try to kill anything you can, prefer to not die while doing so.
3. If you are the only spider in your nest, you can't leave.
4. If there is an enemy on a web you can get on, move onto the web closest to breaking.
5. If there is an empty web leading to an empty nest, move onto it, otherwise move onto their `BroodMother`'s nest.
6. If there is an empty nest, spit a web on it, otherwise spit a web onto their `BroodMother`'s nest.

The only repository changes made since final submission are the modifications to this README.md file.
Final ranking of this AI in the global tournament (includes all competitors)
was first place, although there was at least one team that can reliably beat it head-to-head.
