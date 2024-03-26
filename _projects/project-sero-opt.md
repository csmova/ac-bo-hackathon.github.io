---
number: 1 # leave as-is, maintainers will adjust
title: Active learning for voltammetry waveform design
topic: real-world
team_leads:
  - Cameron Movassaghi (University of California, Los Angeles)

# Comment these lines by prepending the pound symbol (#) to each line to hide these elements
contributors:
#  - Contributor 1 (Institution 1)
#  - Contributor 2 (Institution 2)

# github: AC-BO-Hackathon/project-sero-opt
# youtube_video: <your-video-id>

---

This project will use real-world fast voltammetry (i.e., rapid pulse voltammetry, RPV) data to demonstrate adaptive experimental design of voltammetry waveforms.  Voltammetry waveforms have an underappreciated richness of information but lack design principles in light of an intractable number of possible designs. A key use of fast voltammetry is in sensing neurochemicals, such as designing waveforms for the neurochemical serotonin. This usually entails a one-factor-a-time, guess and check like process. Using a pre-curated set of voltammetry waveforms and calibration curves in vitro, we will demonstrate the ability of Bayesian optimization to generate customized waveforms for human-in-the-loop testing in a more sample efficient process.  We will demonstrate success of identifying a serotonin waveforms that outperforms random and chemist designed waveforms. This real-world application will also be accomponaied by 'ask/tell' tuotrials using the scikit-optimize and Ax packages.

References:
