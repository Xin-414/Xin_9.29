# 🎵 Simple Music Composer (Design Idea)

## Problem Definition
This project aims to design a **Python-based simple music composer** that can automatically generate short melodies.  
The goal is to explore how basic logic and data representation can create music-like patterns without human input.

---

##  Input
- The program starts by defining:
  - Number of notes to generate
  - Musical scale (e.g., C major)
  - Tempo or beats per minute (BPM)
- User input: optional  
  - The program **can** ask the user to choose a mood (happy, sad, calm).  
  - If not provided, it randomly selects a mood and scale.

---

##  Output
- The program outputs:
  - A sequence of notes (e.g., `C4, D4, E4, F4, G4`)  
  - Each note has a time duration (e.g., quarter note)
- Output format options:
  - Plain text (list of notes)
  - Simple visual chart (using matplotlib)
  - MIDI file for playback (extension idea)

---

##  Representation
- Notes can be represented as:
  - Strings (`"C4"`, `"E4"`)
  - Or numerical frequencies (e.g., 261.63 Hz)
- Duration of notes:
  - Quarter = 1 beat  
  - Half = 2 beats  
  - Whole = 4 beats

Example:
```python
notes = [("C4", 1), ("D4", 1), ("E4", 2)]
