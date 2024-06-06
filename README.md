The Sound of Series 
=====================

## Descrition: 

This script maps a sequence of numbers to a range of frequencies and produces audio files (.wav). Each number in the input sequence is converted to a frequency
using modulo operation and an offset. The resulting frequencies are within the range from 100 Hz to (max_frequency + 99) Hz, 3099 Hz in this case.

returns: list of int: A list of frequencies corresponding to the input sequencem and fun .wav files to listen to! 

## Sound (.wav) files

These files are generated after running the jupyter notebook:
- prime_sound.wav
- square_sound.wav
- triangular_sound.wav
- arithmetic_sound.wav

which can be found in the /sound_files directory.

## Figures:

![the_sound_of_series](https://github.com/ianpaga/the_sound_of_series/assets/57350668/446a31d1-d956-4aed-94e4-ed680bdd2578)

## requirements:
- pydub library. You can install this by doing pip install pydub
- Numpy, matplotlib
