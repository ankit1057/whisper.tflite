# Integrate Whisper TFLite for Enhanced Mobile App Performance

If you're interested in incorporating the Whisper TFLite model into your iOS and Android applications, please don't hesitate to reach out to us at yadlaniranjan@gmail.com. Our project features an upgraded iteration of the Whisper quantized TFLite model, finely tuned for optimal performance on both Android and iOS platforms. This model is tailored to excel on edge devices, rendering it versatile for various application scenarios. Contact us for further details and collaboration opportunities

# Whisper Enhanced Quantized TFLite Model

This project contains an enhanced version of the Whisper quantized TFLite model optimized for both Android and iOS platforms. The model is designed to perform well on edge devices, making it suitable for a wide range of applications.

## Requirements

Before you start using this enhanced Whisper model, you need to install Git Large File Storage (LFS) on your system. This is required because the `whisper-tiny.en.tflite` model used in this project is stored using Git LFS.

   
To install Git LFS (Large File Storage), you can use below command:

   ```bash
   git lfs install
   ```

Once you've installed Git LFS, you'll be able to work with repositories that use Git LFS for managing large files.

Remember that you only need to install Git LFS once on your system, and it will work for all Git repositories that use LFS for large file storage.


For more information, you can follow the [Git LFS installation guide](https://git-lfs.github.com/) to install Git LFS on your system.

## Getting Started

To get started with this enhanced Whisper model, follow these steps:

1. Install Git LFS as mentioned in the requirements section.

2. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/nyadla-sys/whisper.tflite.git
   ```

3. You can now use the enhanced Whisper quantized TFLite model in your projects for Android and iOS.

## Android Example

You can find a sample Android app in the [android_example](android_example) folder that demonstrates how to use the Whisper TFLite model for transcription on Android devices.

## DTLN quantized tflite model

Our overarching objective is to incorporate real-time noise suppression through the utilization of a quantized [DTLN](https://github.com/breizhn/DTLN) tflite model, delivering noise-reduced audio data to the whisper tflite model.

Courtesy from [breizhn/DTLN](https://github.com/breizhn/DTLN)

[DTLN Paper](https://arxiv.org/pdf/2005.07551.pdf)

## TODO

 - [ ] Considering adding DTLN noise cancellation tflite model to improve whisper ASR accuracy in noisy environments.

## Here are some noteworthy links for comparing TFLite with other Whisper models:

[Whisper's Comparative Analysis](https://alphacephei.com/nsh/2022/12/11/whisper-other.html)
[Speech Recognition Experiments Repository](https://github.com/fquirin/speech-recognition-experiments)
[OpenVoiceOS' Whisper TFLite Plugin](https://github.com/OpenVoiceOS/ovos-stt-plugin-whisper-tflite)

## Stay Updated

Stay connected to this repository for further developments and updates related to the Whisper enhanced TFLite model. We are constantly working to improve its performance and compatibility with various edge devices.

If you have any questions or encounter any issues, please don't hesitate to open an issue in this repository. We'll be happy to assist you!

## Citing:

If you are using the DTLN model, please cite:

```bash
@inproceedings{Westhausen2020,
  author={Nils L. Westhausen and Bernd T. Meyer},
  title={{Dual-Signal Transformation LSTM Network for Real-Time Noise Suppression}},
  year=2020,
  booktitle={Proc. Interspeech 2020},
  pages={2477--2481},
  doi={10.21437/Interspeech.2020-2631},
  url={http://dx.doi.org/10.21437/Interspeech.2020-2631}
}
```
