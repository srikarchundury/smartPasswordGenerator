# Smart Password Generator
Uses some heuristics to generate a long and complex password while not compromising on the difficulty of remembering it.

## Try it yourself.
```
python GenPass.py
```

## How does it work?

* This tool asks you to key in a word or a phrase that you can remember very well.
* It then uses this phrase and generates mnemonics to remember your phrase easily.
* After that it generates a highly complex password and a key that it uses to encode.
* All you have to remember is this short key and the phrase (for which you have the mnemonics).
* We measure and show you the entropy of both the phrase and the password we generate.

Tough to crack! Quantum can crack it? may not be. More about that? Feel free to email me at srikar.chundury@gmail.com