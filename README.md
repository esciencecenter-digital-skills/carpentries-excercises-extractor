# CaEx2 (CArpentries EXercises EXtractor)
## What does it do?
No more copy-pasting, automatically extract all exercises from a carpentries lesson.

## How to install?
Install with pip:
```
pip install caex2
```

## How to use?
```commandline
caex2 {LESSON_URL} --output {OPTIONAL_OUTPUT_FILE}
```

### Example
To extract all exercises from the [deep learning lesson](https://github.com/carpentries-incubator/deep-learning-intro):
```commandline
caex2 https://github.com/carpentries-incubator/deep-learning-intro
```
This creates a new file called `exercises-document.md` with all exercises in the lesson,
grouped and ordered by episode.