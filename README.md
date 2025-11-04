# Adam

# My Heart Will Go On — TunePad Creative Coding Project

This project focuses on music reconstruction and computational literacy—using code to represent musical phrases, timing, and emotional contours.

This repository contains my creative coding recreation of “My Heart Will Go On” using TunePad.  
The goal of the project was to express musical structure through code — including melody, harmony, bass, and rhythmic texture — while understanding how emotion can be shaped through timing and pitch.



# 🎧 Demo Link
Click to listen to the project here:  
https://tunepad.com/project/117943



![Uploading 11月4日(1).gif…]()





# 🧩 Project Overview
This project re-creates the main melodic theme** and supports it with:
- Piano melody
- Chord accompaniment
- Light guitar-style rhythmic pattern
- Bass root motion

Rather than writing everything in one block, I split the song into reusable melodic phrases (verse phrase, pre-chorus phrase, chorus phrase, and a high-register bridge phrase).  
This made it easier to:
- Organize the song structure clearly
- Repeat and return to themes (just like in real music)
- Adjust timing and phrasing without rewriting entire sections

The tempo is set to 84 BPM, which suits the calm, flowing emotional character of the original song.



# 🎼 Musical & Code Structure

| Element | Description | Function in the Song |
|--------|-------------|----------------------|
| Melody (Piano) | Written in phrases and reused across sections | Carries emotional storytelling |
| Chords (C, G, Am, F, Em) | Simple functional harmony | Creates movement and emotional shape |
| Bass (C2, G1, A1, F1 etc.) | Root‐note support | Grounds the harmony and gives weight |
| Guitar/Strum Pattern | Gentle rhythmic layer | Adds texture without overwhelming melody |
| BPM = 84 | Medium-slow tempo | Maintains gentle, expressive feel |

# Harmonic Progression Highlights
- Verse / Chorus: C → G → Am → F (I–V–vi–IV)  
  Emotionally familiar and warm*
- Pre-Chorus / Bridge: Am → Em → F → G (vi–iii–IV–V)  
  Builds tension before the chorus and peak section*
- Final Note: Long C major to resolve the song  
  Creates closure*



# 🧠 What I Learned

Through building this project, I developed a stronger understanding of:

- How to translate music into code (melody = pitch + duration patterns)
- How repetition and phrasing shape emotional narrative in music
- How chord function and bass movement create a sense of “home → away → return”
- How changing register (higher notes) can increase emotional intensity (used in the bridge section)

This project helped me see that code can be expressive and creative, not only logical.




# 🚀 Possible Future Improvements

If I continue developing this piece, I would consider:

- Adding string pad or vocal-style harmonies to widen the sound
- Introducing more dynamic variation (e.g., softer intro → louder chorus)
- Using more detailed arpeggiated textures in the accompaniment



# 📄 Attribution

Original music written by James Horner & Will Jennings 
Performed by Celine Dion  
Re-created for learning and non-commercial educational purposes.  
Built in TunePad.


# 🧱Code and Computational Thinking

This project uses modular coding principles to build music:

- Functions such as 'verse_phrase()', 'prechorus()', and 'chorus_a()' allow repetitive musical ideas to be written once and reused.

- Drum patterns are written as short algorithmic loops (e.g., 'for i in range(8): playNote()...)') instead of being manually repeated.

- Melodies, harmonies, bass lines, and rhythms are arranged in different TunePad cells, which taught me to think in systems rather than linear sequences.

This approach helped me understand:

- Abstraction (converting musical phrases into reusable code)

- Pattern recognition (identifying repetitive musical structures)

- Systems thinking (how tracks interact rather than being independent)
