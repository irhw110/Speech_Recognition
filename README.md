# Small Vocabulary Speech Recognizer

![alt text](res\asr_overview.JPG?raw=true)

## Overview
- Project for IF4071 Speech Processing course on Bandung Institute of Technology.
- Develop an Automatic Speech Recognition system for Indonesian Language small vocabulary by employing one of the most popular tool.
- Use HTK Tool and Julius
- Submitted on November 29th, 2020

## Project Milestone
- Tools installation and exploration (1 week, Oct 26 - Nov 8)
- Data preparation (1 week, Nov 8 - Nov 15)
- Experiments and documentation (2 weeks, Nov 15 – Nov 29)

## Development Details
1. Tools Exploration (Reading Material: HTK Book, Julius)
2. Preparation of  speech corpus:
   - Audio file recorded from all group members spoken vocabulary/sentences of selected domains in Indonesian Language. (E.g. For digit recognizer satu, dua, tiga, ...sepuluh, ...)
   - Recorded in a clean environment (silent condition)
   - Use high-quality microphone
   - Divide speech corpus into training and test corpus with ratio 9:1.
3. Build an ASR for recognizing small vocabs (Chapter 3: A Tutorial Example of Using HTK)
4. ASR Evaluation using:
   - Closed experimental condition : use training corpus as evaluation corpus
   - Open experimental condition: use test corpus as evaluation corpus
