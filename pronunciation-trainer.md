# Prisencolinensinainciusol

[Prisencolinensinainciusol](https://en.wikipedia.org/wiki/Prisencolinensinainciusol), a song by an Italian dude that sounds like English, but is actually gibberish.

The majority of foreign language speakers have an accent from their mothertongue. Many people can't read phonetics either and even trying to copy a native speaker, the pronunciation can be a little of.

# Suspicion

It should be possible to get a text in one language, pass it through a filter and get an output in another language that might look like gibberish to both, but sound like the input language were spoken by a native speaker.

# Possible solutions

# Build a mapping of phonetics

Dictionaries are already full of words with their corresponding phonems, so it might be possible to have a simple mapping of phonetics to normal alphabet between the 2 languages. It is however doubtful, since a simple `a` can have different sounds depending on the word it is in.

# Machine learning

Training a neural net \(or whatever else exists at the moment\) might be one way of doing it. The training set could a hand picked list of words \(or just phonems\) and their pronunciation by a robot in the native language with the equivalent jumble of letters given to a robot configured in the foreign language. That would be guided training.

Unspervised training could use the same principle without the solution basically:

* provide a word and its phonems \(or maybe just phonems\)
* generate a recording with a robot in the native language
* output a string of letters that when given to a robot in the foreign language sound the same as the original recording

**Terms to search**:

* [LSTM](https://en.wikipedia.org/wiki/Long_short-term_memory)
* [Autoencoder](https://en.wikipedia.org/wiki/Autoencoder)

It sounds super naive and I'm sure that's not how it works, but anyway...

