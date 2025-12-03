# Audio Processing Tools

A comprehensive collection of sound analysis and synthesis tools for music applications and audio signal processing education. This repository combines spectral models, sample audio files, educational materials, and interactive interfaces for hands-on learning and experimentation.

## Features

- **Multiple Audio Analysis Models**: Implementations of various spectral processing techniques
- **Sample Sound Library**: Diverse collection of instruments, speech, and synthesized audio
- **Educational Materials**: Lectures, exercises, and examples for learning audio signal processing
- **Interactive Interfaces**: GUI tools for real-time model exploration and audio transformations
- **Workspace**: Development environment for audio processing experiments

## Repository Structure

```
audio-processing-tools/
├── software/              # Core audio processing models and transformations
│   ├── models/           # Analysis models (DFT, STFT, Sine, Harmonic, Stochastic)
│   └── transformations/  # Audio transformation functions
├── sounds/               # Sample audio files (instruments, speech, synthesized signals)
├── materials/            # Educational content
│   ├── lectures/        # Lecture materials and examples
│   ├── exercises/       # Practice exercises
│   ├── examples/        # Code examples
│   ├── interface-models/        # GUI for exploring models
│   └── interface-transformations/  # GUI for audio transformations
├── workspace/           # Working directory for experiments
└── assignments/         # Coursework and projects
```

## Audio Analysis Models

The `software/models/` directory includes implementations of:

- **dftModel.py**: Discrete Fourier Transform models
- **stft.py**: Short-Time Fourier Transform models
- **sineModel.py**: Sinusoidal modeling
- **harmonicModel.py**: Harmonic analysis
- **stochasticModel.py**: Stochastic modeling
- **sprModel.py**: Sinusoidal plus Residual Model
- **spsModel.py**: Sinusoidal plus Stochastic Model
- **hprModel.py**: Harmonic plus Residual Model
- **hpsModel.py**: Harmonic plus Stochastic Model

## Installation

1. Clone the repository:
```bash
git clone https://github.com/arsonor/audio-processing-tools.git
cd audio-processing-tools
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. (Optional) Install sms-tools package:
```bash
pip install sms-tools
```

## Sample Sounds

The `sounds/` directory contains a variety of audio samples including:
- Musical instruments (flute, oboe, cello, violin, saxophone, trumpet, piano, organ, vibraphone)
- Percussion (bendir, mridangam)
- Vocals (speech, singing, soprano)
- Synthesized signals (sine waves, sawtooth, chirps)
- Natural sounds (ocean, rain)

## Usage

Explore the interactive interfaces in the `materials/` directory:
- Navigate to `materials/interface-models/` for model exploration
- Navigate to `materials/interface-transformations/` for audio transformations
- Use `workspace/` for your own experiments and analysis

## Educational Resources

This repository includes comprehensive educational materials based on audio signal processing techniques. The `materials/` directory contains:
- Lecture notes and code examples
- Hands-on exercises
- Interactive demonstrations

## Credits

Based on the sms-tools package developed by the Music Technology Group (MTG) at Universitat Pompeu Fabra.

## License

This project is made available under the terms of the Affero GPL license (http://www.gnu.org/licenses/agpl-3.0.en.html). 
