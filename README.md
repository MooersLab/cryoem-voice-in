![Version](https://img.shields.io/static/v1?label=cryoem-voice-in&message=0.1&color=brightcolor)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)


# CryoEM-related Voice-In commands

This Repository contains voice-triggered Snippets for use with the Voice In Plus, automated speech recognition (ASR) software that runs in Google Chrome and Microsoft Edge. 
The advantage of this software is that it utilizes the built-in speech-to-text engine that comes with a browser so your sound waves are not being sent to a remote server.
There is much less of a latency limitation that you encounter with chatbots and with `whisper`.
If you speak clearly and somewhat slowly, the software can keep up with you for several paragraphs.
The more clearly you speak, the less likely the software will make a mistake.
You have to say the punctuation because it does not infer it from the context like `whisper`.
The main advantage of this ASR software is that it enables the supply of text replacements, which opens up the possibility of doing all kinds of amazing things and returning the expected result every time, unlike chatbots.

The word error rate is generally quite low except for technical terms.
The CSV file in this repository contains acronyms for jargon found in the world of cryoEM.
The acronyms are prepended with the word `expand`.
I use the word `expand` to group all of my acronym expansions into one region of my Voice In library.

You can select the contents of the file and paste them into the bulk ad window of the Voice In plus web page for your individual account.
You can add thousands of commands this way to your existing library of commands.
Those entries that have the same voice command will be overwritten.

At this point in time, it is unclear how to do bulk deletions of this Library so do the bulk editions in moderation.
Once you have more than 20,000 commands, interaction with your library tensor slows down and becomes painful.

## Funding sources

- NIH: R01 CA242845, R01 AI088011
- NIH: P30 CA225520 (PI: R. Mannel); P20GM103640 and P30GM145423 (PI: A. West)

## Update table

|Version      | Changes                                                                                                                                    | Date                 |
|:-----------:|:------------------------------------------------------------------------------------------------------------------------------------------:|:--------------------:|
| Version 0.2 |  Added update table  and funding                                                                                                           | 2024 April 28        |

