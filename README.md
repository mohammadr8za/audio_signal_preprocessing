# Audio Signal Preprocessing

This repository contains a collection of audio signal preprocessing techniques implemented using the SciPy library in Python. These techniques are useful for enhancing audio quality, reducing noise, and extracting relevant information from audio or speech signals.

## Preprocessing Techniques

* Moving Average Filter: Implements a moving average filter to smooth out the audio signal by calculating the average of a sliding window of samples.

* Moving Median Filter: Implements a moving median filter to reduce noise in the audio signal by calculating the median of a sliding window of samples.

* Bandstop Filter: Implements a bandstop filter using the Butterworth filter design from the SciPy library. This filter attenuates frequencies within a specified frequency range while allowing other frequencies to pass through.

* Notch Filter: Implements a notch filter using the Butterworth filter design from the SciPy library. This filter attenuates a specific frequency or a narrow range of frequencies while preserving the rest of the audio signal.

* Adaptive Filter: Implements an adaptive filter that adapts its parameters based on the input signal to reduce noise or interference in real-time. This technique is useful in scenarios where the characteristics of the noise or interference are not known in advance.

* Scaling Input Signal: Provides a function to scale the input audio signal to a desired range, such as normalizing the signal between -1 and 1.

* Adaptive Dynamic Range Compression: Implements a dynamic range compression technique to enhance the audibility of soft sounds and reduce the intensity of loud sounds, improving the overall listening experience.

* Frame-by-Frame Analysis: Includes a code snippet for performing frame-by-frame analysis of audio or speech signals. This technique involves dividing the audio signal into smaller frames and processing each frame individually, allowing for more accurate analysis and modification.

## Usage

Each preprocessing technique is implemented as a separate Python module in this repository. You can import the desired module into your own project or experiment with the provided example code.

Please refer to the documentation and comments within each module for detailed instructions on how to use the functions and adjust the parameters as needed.

## Dependencies

* Python 3.x
* NumPy
* SciPy

## License

This repository is licensed under the MIT License. Feel free to modify, distribute, and use the code for your own projects.

## Acknowledgments

This repository is inspired by the need for efficient audio signal preprocessing techniques in various applications, including speech recognition, audio analysis, and noise reduction.

## Contributing

Contributions to this repository are welcome! If you have suggestions, bug fixes, or additional preprocessing techniques you would like to contribute, please feel free to submit a pull request.

## Contact

If you have any questions, suggestions, or feedback, please feel free to contact me at [mohammadreza.peyghan@gmail.com].

Happy audio signal preprocessing!
