![Version](https://img.shields.io/static/v1?label=cryoem-voice-in&message=0.1&color=brightcolor)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)


# CryoEM-related Voice-In commands

This repository contains voice commands used as voice-triggered snippets for `Voice In Plus`, an automated speech recognition (ASR) plugin in Google Chrome and Microsoft Edge. 
The advantage of this software is that it utilizes the browser's built-in speech-to-text engine so your sound waves are not being sent to a remote server.
There is less latency compared to chatbots and `whisper`.
If you speak clearly and somewhat slowly, the software can keep up with you for several paragraphs.

The more clearly you speak, the less likely the software will make a mistake.
You have to say the punctuation marks because the software does not infer them from the context, unlike the situation with `whisper`.
The main advantage of `Voice In Plus` is that it enables you to supply text replacements.
These text replacements allow for all kinds of amazing things and, unlike chatbots, return the expected result every time.

The word error rate (WER) is quite low except for technical terms.
The CSV file in this repository contains acronyms for jargon used in cryogenic electron microscopy (cryoEM).
The acronyms are prepended with the word `expand`.
I use `expand` to group all my acronym expansions into one region of my voice command library to ease their subsequent locating and editing.

You can select the file's contents and paste them into the bulk ad window of the `Voice In Plus` web page for your individual account.
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

