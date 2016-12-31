---
layout:    presentation
title:     "PaintBoard: Prototyping Interactive Character Behaviours by Painting Storyboards"
presenter: Daniel J. Rea
video:     c_F6DJIjBB4
date:      2015-03-26
---

The creation of interactive worlds, such as those in video games, often include a set of computer controlled characters that must intelligently act and react in response to dynamic input from the user. These interactive behaviours usually require authors to programmatically define each behaviour, reaction, and interaction the character should take in response to user input across a range of scenarios, a process that can take significant time. While this method can successfully create robust characters, the large development overhead is not conducive to the exploration, prototyping, and testing of new character ideas.

We designed and developed PaintBoard, a system that enables users to rapidly prototype interactive character movement by digitally painting a storyboard. PaintBoard promotes prototyping by facilitating quick, visual authoring, and by enabling immediate testing by allowing the user to interact in real-time with a behaviour generated from a painted storyboard. To generate the interactive behaviour, we developed a novel algorithm that analyzes a painted storyboard and uses machine-learning to generalize the painted examples to new situations. Our algorithm uses this generalized behaviour to control the computer character during real-time interaction with the user character.

To help ground our design decisions in how real designers approach the problem of creating interactive behaviours, we conducted two preliminary exploratory studies with industry professionals and programmers. We further conducted a proof-of-concept workshop with our prototype to investigate how real developers may use PaintBoard; this illustrated the initial success of our painting-storyboards authoring metaphor. Finally, we performed an initial evaluation of the behaviour generation algorithm which informed us of directions for future work to improve PaintBoard’s performance.

Contributions of this work include the design and evaluation of both a new interaction metaphor— digitally painting storyboards for interactive behaviour authoring—and a novel behaviour generation algorithm (for generating real-time interactive behaviours from storyboards). Our results demonstrate that the PaintBoard approach can be useful to developers as an exploratory prototyping tool due to its fast and understandable painting metaphor, and that PaintBoard itself can quickly (in real-time) generate an interactive behaviour.

[Daniel J. Rea](https://twitter.com/bitbytechomp/) is a Ph.D. student (Computer Science) at the University of Manitoba with a strong interest in game design, literature, music, and the universe in general. He speaks and reads Japanese fluently, swing dances, and loves to read. His M.Sc. and Undergraduate degrees were in Computer Science, also at the University of Manitoba. He has worked in Japan for almost two years, and is trying my hand at making games in his spare time.
