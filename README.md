# Ai-music-generator


An AI-based music generation project that learns musical patterns from classical piano MIDI files and generates new original music.

## How it works
- Collects MIDI music data from a dataset of classical piano compositions
- Extracts notes and chords from the MIDI files using `music21`
- Converts notes into numerical sequences for training
- Builds and trains an LSTM (deep learning) model to learn musical patterns
- Generates new note sequences from the trained model
- Converts the generated sequences back into a playable MIDI file

## Built with
- Python
- music21
- TensorFlow / Keras (LSTM)
- NumPy

## Project context
Built as part of the CodeAlpha Artificial Intelligence Internship (Task 3: Music Generation with AI).
