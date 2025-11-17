# 25-REA-CMP_garo-speech-recognition
Initial work on a speech recognition system for Garo

## Contributors
- Charles Redmon  
- Debika Sangma
- Matsram Sangma
- Triksimeda Sangma
- Scarlett Pechacek
- Rosie Fossberg
- Shanya Wijeyawardana
- ...

## Data structure

### Data (dat/)
All data is maintained in the `dat/` folder, with subfolders for each data source/type.

Currently we have the following sub-corpora for model development:
- **All India Radio** (`AIR/`)

Planned additional sub-corpora include:
- **Digits** (`digits/`)
- **Command Words** (`commands/`)

### Code (src/)
All source code for running the models is contained the `src/` folder. These are primarily Python scripts.

### Resources (res/)
All further resource files are contained in the `res/` folder.

Key resources:
  - **codebook.txt** A tab-separated file with phonemic transcription conventions between IPA and ASCII system.


