# The Billboard Melodic Music Dataset

The Billboard Melodic Music Dataset (BiMMuDa) is a MIDI dataset of the main melodies of the top five singles from the Billboard Year-End Singles Charts for each year from 1950 to 2022. This repository stores the dataset, as well as its metadata and appendices. 

The "bimmuda_dataset" directory contains all MIDIs, scores, and lyrics files. The highest level of folders organize the data by year, while the second level organize the data within each year by single. Each second-level folder contains (with some exceptions, see "List of Top Singles with No Main Melody"):

    1. A .mcsz file, the full score of the main melody

    2. A MIDI file (suffix "_full.mid") containing the full main melody (exported from the .mcsz file)

    3. MIDI files of the individual sections of the single, e.g., verse, chorus, bridge. These are labeled with "_1.mid", "_2.mid", etc. suffixes, according to
       the order in which the section first appears in the song.

    4. A .txt file containing the song's lyrics, if there are any (see "List of Top Singles with Non-Vocal Main Melodies")
       
The "metadata" directory contains two .csv files of metadata:

    1. bimmuda_per_song_metadata.csv contains the per-song metadata 
    2. bimmuda_per_melody_metadata.csv contains the per-melody metadata

The "source_midis" directory contains files related to the pre-existing MIDI files used in the creation of the dataset.

Finally, the "resources" directory contains a document describing the details of the BiMMuDa transcription strategy.

# List of Top Singles with No Main Melody

The following top singles contain no main melody and thus have lyrics files but no corresponding MIDI or Musescore files:

    - "Baby Got Back" by Sir Mix-a-Lot (1992_02)
    - "Jump" by Kriss Kross (1992_03)
    - "Whoomp! There It Is" by Tag Team (1993_02)
    - "Can't Nobody Hold Me Down" by Diddy feat. Mase (1997_05)
    - "Humble" by Kendrick Lamar (2017_04)
    
# List of Top Singles with Non-Vocal Main Melodies

The main melodies of the following top singles are carried by instruments rather than by vocals and therefore do not have lyrics files:

    - "Third Man Theme" by Anton Karas (1950_03)
    - "Blue Tango" by Leroy Anderson (1952_01)
    - "The Song from Moulin Rouge" by Percy Faith (1953_01)
    - "Cherry Pink and Apple Blossom White" by Perez Prado (1955_01)
    - "Autumn Leaves" by Roger Williams (1955_04)
    - "Lisbon Antigua" by Nelson Riddle (1956_03)
    - "Patricia" by Perez Prado (1958_05)
    - "The Theme from 'A Summer Place'" by Percy Faith (1960_01)
    - "Stranger on the Shore" by Acker Bilk (1962_01)
    - "The Stripper" by David Rose (1962_05)
    - "Love is Blue" by Paul Mauriat (1968_02)
    - "Love's Theme" by Love Unlimited Orchestra (1974_03)
    - "Harlem Shake" by Baauer (2013_04)

# Submitting Corrections

Each song represented in the BiMMuDa has been manually transcribed, and the transcriptions have been checked multiple times by different individuals (see the transcription guide for more details). However, there may still be small mistakes in some of the transcriptions. If you find a mistake, you can email Madeline Hamilton at m.a.hamilton@qmul.ac.uk (please use the subject line "BiMMuDa Corrections"). You can also make corrections yourself and submit a pull request. 

