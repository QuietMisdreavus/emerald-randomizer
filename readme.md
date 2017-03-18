# misdreavus' fork of the emerald randomizer

a friend and i have been investigating some of the randomizer features and figuring out how to tweak
them and add and/or port them over. slight problem: he's not much of a coder, and i don't know java
at all. so, we're going to explore this together, and if i get enough of a hang of romhacking, i'd
like to port some functionality to a language i'm more comfortable with.

the emerald randomizer seems to be written with an older version of NetBeans. since newer netbeans
versions ditched the ability to design Swing windows, i won't be able to modify the ui without some
effort. thus, any new tweaks will be overloaded atop something else.

here are the tweaks we've made:

* randomize "special trainer" movesets, even when not changing their pokemon, when their held items
  are being changed, to apply this feature to roms run through another randomizer (the universal
  randomizer apparently doesn't inspect special-trainer movesets)
