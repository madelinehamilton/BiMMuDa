# The Billboard Melodic Music Dataset

The Billboard Melodic Music Dataset (BiMMuDa) is a MIDI dataset of the main melodies of the top five singles from the Billboard Year-End Singles Charts for each year from 1950 to 2022. This repository stores the dataset, as well as its metadata and appendices. 

The "melodies" directory contains zip files of three different elements of the dataset:

    1. bimmuda_midis.zip contains the main dataset, the main melodies of the singles, separated by section. Each MIDI is named according to the year of
       the single, its position, and the section's order of appearance in the song. For example, "1960_01_1.mid" contains the first main melody heard in
       the number 1 song of 1960. This is the version of the dataset used for analysis. 
       
    2. bimmuda_full_midis.zip contains the entire main melody of each single in MIDI format. Each MIDI is named according to the year and
       position of the single ("1960_01_full.mid" contains the entire main melody of the number 1 song of 1960).
       
    3. bimmuda_full_scores.zip contains the full score of the main melody of each single, in .mcsz (Musescore sheet music) format. For example,
       "1960_01_full.mcsz" is the full score of the main melody of the number 1 song of 1960. These scores are exported as MIDIs to create the full
       MIDI files, and sections of the scores are exported as MIDIs to create the individual MIDI files. 

The "metadata" directory contains three .csv files of metadata:

    1. bimmuda_per_song_metadata.csv contains the per-song metadata 
    2. bimmuda_per_melody_metadata.csv contains the per-melody metadata
    
Finally, the "lyrics" directory has bimmuda_lyrics.zip, which contains .txt files with the lyrics of each single. 

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


