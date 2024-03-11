# BE in Automatic Control and Robotics | MSc Student in Computer Science | Software Developer

I hold a Bachelor of Engineering degree in Automatic Control, Cybernetics, and Robotics and am currently pursuing a master's degree in Computer Science. My interests are primarily in the fields of sound and image processing, machine learning, and physics. I also have a profound interest in music, both from a creative and technical perspective. I enjoy reading scientific articles on Music Information Retrieval and Generative AI in music, keen to expand my knowledge in these areas.

#### Main Skills: Python, Machine Learning, C++, Signal Processing

## Education
**(MSc) Computer Science | Warsaw University of Technology (_Feb 2024 - present_)**

**(BE) Automatic Control, Cybernetics and Robotics	| Gdańsk University of Technology (_Oct 2020 - Feb 2024_)**
- Grade: 5/5 with distinction, GPA: 4.702/5

## Work Experience
**Working Student - Software Developer / Test Automation Developer (part time) | Nokia (_Oct 2023 - Present_)**
- Development and maintanance of source code in C/C++
- Technologies in use: C/C++, Linux, Docker, Kubernetes, Git, Jira, Gerrit

**Summer Trainee - Software Developer / Test Automation Developer (full time) | Nokia (_Jul 2023 - Sep 2023_)**
- Writing automated tests in Robot Framework, development and maintanance of source code in C/C++
- Technologies in use: Robot Framework, Python, C/C++, Linux, Docker, Kubernetes, Git, Jira, Gerrit

## Certificates
- [Deep Learning Specialization](https://www.coursera.org/account/accomplishments/specialization/PYP8WKSV9SNV)
- [Self-Driving Cars Specialization](https://www.coursera.org/account/accomplishments/specialization/GC3UMG2D8USH?utm_source=link&utm_medium=certificate&utm_content=cert_image&utm_campaign=sharing_cta&utm_product=s12n)
- [Practical Data Science on the AWS Cloud](https://www.coursera.org/account/accomplishments/specialization/PWMCC339YXJN)

## Achievements
- Golden Badge for the best graduates of GUT
- Rector's Scholarship for the best students for the 2020/21, 2021/22, 2022/23 academic years.

## Projects
### GGPT Music Composer [2023]

My biggest solo project and bachelor thesis work was developed using **Python**. It presents an **alternative approach to generating multitrack, full-length MIDI songs from text using ChatGPT API, genetic algorithms and probabilistic methods**. LLM defines structure, which includes time signature, scales, chord progressions, and valence-arousal values, from which accompaniment, melody,
bass, motif, and percussion tracks are created. The hybrid system uses emotional parameters from predicted point on valence-arousal plane, which have impact on GA fitness function and other parameters such as MIDI velocity range. Tracks and their sections are given their titles, and creative process is explained by ChatGPT in the chat window. The system can serve as an inspiration for musicians because of MIDI usage and no limits imposed by dominating structures in music.

![GGPT Music Composer Interface](/assets/img/GGPTComposer.png)

#### Example generations
To present the functionality of the system, I generated couple of songs using descriptions from [Meta's MusicGen](https://audiocraft.metademolab.com/musicgen.html) and [Google's MusicLM](https://google-research.github.io/seanet/musiclm/examples/) sites. Presented wav files are synthesized from MIDI, so they have quite basic instrument sounding. They can however be used to synthesize with finer samples.

<table>
<tr>
<td>

Prompt: Smooth jazz, with a saxophone solo, piano chords, and snare full drums

</td>
<td>

<audio controls>
  <source src="assets/audio/Velvet-Evening-20231208-114938.wav" type="audio/wav">
Audio can not be played.
</audio>

</td>
</tr>

<tr>
<td>

Prompt: 80s electronic track with melodic synthesizers, catchy beat and groovy bass

</td>
<td>

<audio controls>
  <source src="assets/audio/Retro-Synthwave-20231209-175338.wav" type="audio/wav">
Audio can not be played.
</audio>

</td>
</tr>

<tr>
<td>

Prompt: Progressive rock drum and bass solo

</td>
<td>

<audio controls>
  <source src="assets/audio/Progressive-Odyssey-20231208-143.wav" type="audio/wav">
Audio can not be played.
</audio>

</td>
</tr>

<tr>
<td>

Prompt: drum and bass beat with intense percussions

</td>
<td>

<audio controls>
  <source src="assets/audio/Intense-Rhythm-20231208-115146.wav" type="audio/wav">
Audio can not be played.
</audio>

</td>
</tr>

<tr>
<td>

Prompt: A grand orchestral arrangement with thunderous percussion, epic brass fanfares, and soaring strings, creating a cinematic atmosphere fit for a heroic battle.

</td>
<td>

<audio controls>
  <source src="assets/audio/Heroic-Skies-20231208-130450.wav" type="audio/wav">
Audio can not be played.
</audio>

</td>
</tr>

<tr>
<td>

Prompt: Funky piece with a strong, danceable beat and a prominent bassline. A catchy melody from a keyboard adds a layer of richness and complexity to the song.

</td>
<td>

<audio controls>
  <source src="assets/audio/Funk-Odyssey-20231209-134348.wav" type="audio/wav">
Audio can not be played.
</audio>

</td>
</tr>

<tr>
<td>

Prompt: Funky piece with a strong, danceable beat and a prominent bassline. A catchy melody from a keyboard adds a layer of richness and complexity to the song.

</td>
<td>

<audio controls>
  <source src="assets/audio/Funk-Odyssey-20231209-134348.wav" type="audio/wav">
Audio can not be played.
</audio>

</td>
</tr>
<tr>
<td>

Prompt: Epic soundtrack using orchestral instruments. The piece builds tension, creates a sense of urgency. An a cappella chorus sing in unison, it creates a sense of power and strength.

</td>
<td>

<audio controls>
  <source src="assets/audio/Epic-Orchestral-Surge-20231208-1.wav" type="audio/wav">
Audio can not be played.
</audio>

</td>
</tr>

<tr>
<td>

Prompt: Violins and synths that inspire awe at the finiteness of life and the universe.

</td>
<td>

<audio controls>
  <source src="assets/audio/Celestial-Reverie-20231208-11391.wav" type="audio/wav">
Audio can not be played.
</audio>

</td>
</tr>

<tr>
<td>

Prompt: The main soundtrack of an arcade game. It is fast-paced and upbeat, with a catchy electric guitar riff. The music is repetitive and easy to remember, but with unexpected sounds, like cymbal crashes or drum rolls.

</td>
<td>

<audio controls>
  <source src="assets/audio/Arcade-Rush-20231208-135906.wav" type="audio/wav">
Audio can not be played.
</audio>

</td>
</tr>

<tr>
<td>

Prompt: We can hear a choir, singing a Gregorian chant, and a drum machine, creating a rhythmic beat. The slow, stately sounds of strings provide a calming backdrop for the fast, complex sounds of futuristic electronic music.

</td>
<td>

<audio controls>
  <source src="assets/audio/Ancient-Future-20231208-121749.wav" type="audio/wav">
Audio can not be played.
</audio>

</td>
</tr>

</table>

Technologies used: Python, PySide6, NumPy, Pandas, openai, matplotlib, MidiUtil, Mingus, PyGame

## Meta-learning app (as a leader of a group) [2023]

I was a leader of a group which aimed to create a hub of meta-learning models to train them on small number of images, enabing for further classification of desired categories. We implemented models such as MAML, Prototypical, Siamese Network and state-of-the-art EASY model. Best models achieved around 80% accuracy on 5-way, 10-shot task. In the app user is able to upload photos, name the categories, define hyperparameters and observe the results of the training. In another page images can be classified by a model chosen from a list of trained ones. I was responsible for planning the whole project, distributing tasks, code reviewing, writing documentation, testing and implementing the Siamese network. 

Technologies used: Python, PyTorch, Tensorflow, NumPy, Matplotlib, OpenCV, Cuda, Pandas, Keras, PyQt5

<table>
  <tr>
    <td>
      <img src="/assets/img/meta-learning.png" alt="Meta-learning App Interface page 1" style="width: 100%;">
    </td>
    <td>
      <img src="/assets/img/meta-learning2.png" alt="Meta-learning App Interface page 2" style="width: 100%;">
    </td>
  </tr>
</table>


## Image Sonification (as a leader of a group) [2022/23]

I was a leader of a group project which aimed to turn data into sound. We created an app that takes any RGB image as an input, removes a background (if it is a photo), then finds the edges and creates MIDI out of them, assuming that height of the image influences the pitch of a note and width - the time. MIDI track is later changed into sound using implemented music synthesizer. Colors of the image have impact on synthesizer's parameters like type of wave, filters and applied effects. I was responsible for planning the whole project, distributing tasks, code review, writing documentation and converting image data into MIDI and synth parameters. 

Technologies used: Python, PyQt6, NumPy, OpenCV, SciPy, matplotlib, MidiUtil, Mingus

![Sonification App Interface](/assets/img/sonification.png)


