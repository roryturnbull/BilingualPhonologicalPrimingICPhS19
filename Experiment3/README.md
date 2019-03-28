# Stimulus lists for experiment 3

## Master list

Exp3MasterStimulusList.csv contains all of the prime-target combinations that were used in the construction of the stimulus presentation lists. This file has seven columns:

- prime_word:
The prime word itself (in orthography).

- prime_lex:
The lexicality of the English prime word: either "FrenchPrime" (i.e. an English word which could plausibly be parsed as a French word, e.g. English "pill" could be perceived as French "pile"), or "NonFrenchPrime" (i.e. an English word which could not be parsed as a French word, e.g. "bed" for which there is no corresponding French *"bêde").

- target_word:
The target word itself (in orthography).

- target_lex:
The lexicality of the French target: either "Word" or "Nonword"

- similarity:
The (supposed) phonological similarity between the prime and target: either "Match" or "NoMatch".

Stimulus presentation lists.

list0.csv, list1.csv, list2.csv, and list3.csv are the stimulus files that were directly read by our PsychoPy script. Each file has seven columns:

- prime_text:
Orthographic representation of the prime phrase.

- prime_audio:
Location of the audio file for the prime phrase.

- prime_lex:
Same as "prime_lex" above.

- target_text:
Orthographic representation of the target phrase. (Note that this information was never presented to participants.)

- target_audio:
Location of the audio file for the target phrase.

- target_lex:
Same as "target_lex" above.

- similarity:
Same as "similarity" above.

