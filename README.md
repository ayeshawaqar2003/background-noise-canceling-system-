# background-noise-canceling-system-
## Project Description:
This project focuses on implementing an adaptive filtering technique using the Least Mean Squares (LMS) algorithm in MATLAB to reduce noise from a speech signal. The objective is to enhance the clarity of speech by filtering out background noise from a noisy recording.

The system takes three audio inputs: a clean speech signal (cleancall.mp3), a noisy signal (call.mp3), and a noise reference. It aligns signal lengths, then applies adaptive filtering to minimize the error between the noisy input and the desired clean output. By iteratively adjusting filter weights, the LMS algorithm learns to suppress noise while preserving speech.

Key steps include:

Loading and preprocessing the speech and noise signals.

Initializing the adaptive filter parameters (filter order and learning rate).

Running an adaptive loop to update weights and reduce noise.

Comparing the filtered output with the original noisy signal audibly and visually through waveform plots.

The project demonstrates the effectiveness of adaptive filters for real-time speech enhancement and serves as a practical application of signal processing in communication systems
![image](https://github.com/user-attachments/assets/1e5451c8-176f-43e5-aa32-df480c3dcb25)
