# Task

## Requirements for the Problem

Your task is to develop a program that can be hosted on GitHub or a similar platform. The program should meet the following specifications:

- **Input**: A video file in MP4 format.
- **Output**: Two separate audio tracks:
  - **Track 1**: Cleaned vocals, with as much background noise removed as possible.
  - **Track 2**: Isolated background noises.

### Implementation Guidelines

- Utilize any open-source libraries or tools you are familiar with.
- Deep learning solutions like U-Net architectures are commonly used for such tasks, but classical digital signal processing methods are also an option, depending on their effectiveness within the project's time constraints.
- The primary focus should be on separating vocals from background noises, specifically those that are disruptive to STT systems.

### Evaluation

- **Approach**: Briefly explain your approach and the rationale behind your choices.
- **Demonstration of Effectiveness**: If possible, demonstrate the effectiveness of your solution by running a simple STT on the original and cleaned audio tracks. You may use any open-source STT for this purpose. Then, compare the transcription accuracy.
- **Potential Improvements and Limitations**: Discuss any potential improvements and limitations of your solution.

### Bonus (if time permits)

- **Integration into a Larger STT Pipeline**: Consider how this audio separation module could be integrated into a larger speech-to-text pipeline, taking into account factors such as real-time processing, scalability, and adaptability to different video sources.

### Hints and Tips

- Consider using tools/libraries like TensorFlow, PyTorch, and librosa.
- Pretrained models and solutions are available for these kinds of tasks. While these can serve as a starting point, ensure you properly cite any sources if you borrow code or ideas.


