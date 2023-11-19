### Café Neuro

Every Wednesday 10am-11am CET, we get together (mix of virtual and in-person) for coffee, cake and a short talk. On a rotating basis, each member of the lab gives a small project update: what they've been working on in the past 1-2 months, what their current data and results are, what pending question they may have. 

[List of upcoming topics](2022-01-25-Upcoming_cafe_neuro.md). 

<hr>

### Software

In addition to data and code that is specific to each of [our papers](publications.md), we develop and maintain a number of free, open-source research software which we make available for the research community.

#### CLEESE (Reverse Correlation)

CLEESE ("Ministry of silly talks") is a Python toolbox designed to generate an infinite number of natural-sounding, expressive variations around an original speech recording. More precisely, CLEESE creates random fluctuations around the file’s original contour of pitch, loudness, timbre and speed (i.e. roughly defined, its prosody). One of its main applications is the generation of very many random voice stimuli for reverse correlation experiments, as in [Ponsot et al. PNAS 2018](https://www.pnas.org/content/115/15/3972) or [Goupil et al. Nature Communications 2021](https://www.nature.com/articles/s41467-020-20649-4). 

CLEESE is a free, standalone Python module, distributed under an open-source MIT Licence. It was originally developped by Juan José Burred, Emmanuel Ponsot and Jean-Julien Aucouturier ([CREAM](cream.md) team, IRCAM, Paris), in collaboration from [Pascal Belin](https://www.int.univ-amu.fr/_BELIN-Pascal,659_?lang=en) (Institut des Neurosciences de la Timone, Aix-Marseille Université). 

<a href="https://github.com/creamlab/cleese">:material-github: CLEESE Github page</a>&nbsp;&nbsp;&nbsp;
<a href="https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0205943">:material-book: Companion paper</a>&nbsp;&nbsp;&nbsp;

<hr>

#### DAVID (Vocal feedback)


DAVID (Da Amazing Voice Inflection Device) is a real-time voice transformation tool able to "colour" any voice recording with an emotion that wasn’t intended by its speaker. DAVID was especially designed with the affective psychology and neuroscience community in mind, and aims to provide researchers with new ways to produce and control affective stimuli, both for offline listening and for real-time paradigms. For instance, we have used it to create real-time emotional vocal feedback in [Aucouturier et al. PNAS 2016](https://www.pnas.org/content/113/4/948) and [Goupil et al. Consciousness & Cognition 2021](https://www.sciencedirect.com/science/article/abs/pii/S1053810020305390?dgcid=coauthor). 

Technically, DAVID is implemented as an open-source patch for the close-source audio processing plateform Max (Cycling’74), and, like Max, is available for most Windows and MacOS configurations. It is distribted under an open-source MIT Licence. It was originally developped by Marco Liuni ([CREAM](cream.md) team, IRCAM, Paris), in collaboration with [Petter Johansson](https://www.fil.lu.se/en/person/PetterJohansson/) and [Lars Hall](https://www.fil.lu.se/en/person/LarsHall/) at Lund University, and [Katsumi Watanabe](http://www.fennel.sci.waseda.ac.jp/indexe.html) at Waseda. 

<a href="https://github.com/neuro-team-femto/david">:material-github: DAVID Github page</a>&nbsp;&nbsp;&nbsp;
<a href="https://link.springer.com/article/10.3758/s13428-017-0873-y">:material-book: Companion paper</a>&nbsp;&nbsp;&nbsp;

<hr>
