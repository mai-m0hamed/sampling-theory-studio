# Sampling_Theory Studio

## Overview
Sampling_Theory Studio is a desktop application developed using PyQt5 Designer and Python. This application allows users to work with signals, perform sampling, and recover the original signal using different frequencies.

## Team Information
Sampling_Theory Studio is a desktop application developed by Team 4, consisting of the following members:
- Sondos Mahmoud
- Fatma Ehab
- Mai Mohamed
- Noura Osama

## Features

1. **Signal Loading and Visualization**: Users can load a mid-length signal with approximately 1000 points. The application provides a graph to visualize the loaded signal.

![image](https://github.com/mai-m0hamed/sampling-theory-studio/assets/115077795/a276d6b3-e061-4580-ad3c-06cb34f8e73b)

2. **Sampling**: The loaded signal can be sampled using different frequencies. Users can choose the sampling frequency, which is displayed either as the actual frequency or the normalized one based on the state of the "Normalized" checkbox.

![image](https://github.com/mai-m0hamed/sampling-theory-studio/assets/115077795/c55af970-1988-4ac8-8d74-ba16fd326d8f)


3. **Signal Recovery**: After sampling, the application utilizes the sampled points to recover the original signal. A graph is provided to display the reconstructed signal.

4. **Difference Visualization**: Users can compare the original signal with the reconstructed one using a third graph, which shows the difference between the two signals.
   
![image](https://github.com/mai-m0hamed/sampling-theory-studio/assets/115077795/28fcf1f6-59b2-4987-a52a-68573800f078)

6. **Signal Mixer/Composer**: The loaded signal can be sourced from a file or created in the application's signal mixer/composer. In the mixer, users can add multiple sinusoidal signals of different frequencies and magnitudes. Components can also be removed while preparing the mixed signal.
   
![image](https://github.com/mai-m0hamed/sampling-theory-studio/assets/115077795/7a160819-c38a-4e28-8908-508c1d7379ca)

7. **Noise Addition**: Users have the option to add noise to the loaded signal. The noise level can be controlled using a custom Signal-to-Noise Ratio (SNR). The application demonstrates the dependency of the noise effect on the signal frequency.

![image](https://github.com/mai-m0hamed/sampling-theory-studio/assets/115077795/92b52824-7e05-49e6-b957-cf55b0aa163d)


8. **Real-time Processing**: Sampling and recovery are performed in real-time, instantly reflecting any changes made by the user.

9. **Resizable UI**: The application's UI is designed to be easily resizable, ensuring a smooth user experience.


## Usage

Upon launching Sampling_Theory Studio, you will be presented with a user-friendly interface that allows you to interact with the various features of the application. Load your signal, adjust the sampling frequency, add/remove components in the signal mixer, and explore the visualizations of the original signal, reconstructed signal, and difference between them.

