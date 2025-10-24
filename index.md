---
layout: default
title: "Lost in Phonation: A Benchmark for Voice Quality in Speech Synthesis"
---

# Lost in Phonation: A Benchmark for Voice Quality in Speech Synthesis

<div class="authors">
  <strong>Authors:</strong> [Author Name 1], [Author Name 2], [Author Name 3]
</div>

<div class="affiliation">
  [Institution Name] | [Conference/Journal Name] 2025
</div>

<div class="paper-links">
  <a href="#" target="_blank">📄 Read Paper</a>
  <a href="#" target="_blank">💾 Download Dataset</a>
  <a href="#" target="_blank">💻 GitHub Repository</a>
  <a href="#audio-examples">🎧 Audio Examples</a>
</div>

---

<div class="abstract">

## Abstract

Voice quality is a critical aspect of speech synthesis that encompasses various phonatory characteristics including breathiness, creakiness, and tenseness. Despite significant advances in neural text-to-speech systems, the ability to accurately model and reproduce diverse voice qualities remains challenging. This work presents **Lost in Phonation**, a comprehensive benchmark for evaluating voice quality in modern speech synthesis systems. We introduce a curated dataset with annotations for multiple voice quality dimensions and evaluate several state-of-the-art TTS models on their ability to reproduce these characteristics. Our findings reveal significant gaps in current systems' capabilities to handle non-modal voice qualities, providing insights for future research directions.

</div>

---

## 🎯 Key Contributions

- **Comprehensive Benchmark**: A systematically designed evaluation framework for voice quality in speech synthesis
- **Annotated Dataset**: High-quality recordings with detailed voice quality annotations across multiple dimensions
- **Model Evaluation**: Systematic comparison of state-of-the-art TTS systems on voice quality reproduction
- **Analysis Framework**: Novel metrics and evaluation protocols for assessing phonatory characteristics
- **Public Resources**: Open-source dataset, evaluation code, and model outputs for reproducibility

---

## 🔊 Voice Quality Dimensions

<div class="voice-quality-grid">
  <div class="quality-category">
    <div class="quality-icon">🌬️</div>
    <h3>Breathy</h3>
    <p>Characterized by audible air turbulence, incomplete vocal fold closure, and a soft, airy quality.</p>
  </div>

  <div class="quality-category">
    <div class="quality-icon">⚡</div>
    <h3>Creaky</h3>
    <p>Low-frequency vocal fold vibration producing a rattling or popping quality, often at phrase endings.</p>
  </div>

  <div class="quality-category">
    <div class="quality-icon">🎵</div>
    <h3>Modal</h3>
    <p>Regular, periodic vocal fold vibration - the most common phonatory pattern in speech.</p>
  </div>

  <div class="quality-category">
    <div class="quality-icon">💪</div>
    <h3>Tense</h3>
    <p>Increased laryngeal tension resulting in a strained, pressed, or harsh vocal quality.</p>
  </div>

  <div class="quality-category">
    <div class="quality-icon">🌊</div>
    <h3>Rough</h3>
    <p>Irregular vocal fold vibration creating an uneven, harsh, or raspy quality.</p>
  </div>

  <div class="quality-category">
    <div class="quality-icon">🎭</div>
    <h3>Falsetto</h3>
    <p>High-pitched phonation with thin vocal folds, producing a light, flute-like quality.</p>
  </div>
</div>

---

## 📊 Benchmark Results

Our evaluation reveals important insights about current TTS systems' ability to model voice quality:

- **Modal Voice**: All systems perform well on modal phonation (95%+ accuracy)
- **Breathiness**: Moderate performance (60-75% detection rate)
- **Creaky Voice**: Significant challenges (40-55% reproduction accuracy)
- **Complex Qualities**: Mixed voice qualities remain highly challenging (<35% accuracy)

<div class="placeholder-notice">
  📈 Detailed results tables and visualizations will be added here
</div>

---

## 🎧 Audio Examples {#audio-examples}

Below are representative examples from our benchmark, comparing input prompts with outputs from different TTS systems.

### Example 1: Breathy Voice

<div class="audio-grid">
  <div class="audio-example">
    <h4>Reference Audio</h4>
    <div class="audio-prompt">
      <strong>Prompt:</strong> "The soft whisper of the wind carries secrets through the trees."
      <br><strong>Voice Quality:</strong> Breathy
    </div>
    <div class="audio-player">
      <span class="audio-label">Ground Truth</span>
      <audio controls>
        <source src="assets/audio/example1_reference.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </div>
  </div>

  <div class="audio-example">
    <h4>Model A</h4>
    <div class="audio-prompt">
      <strong>System:</strong> Neural TTS Model A
      <br><strong>Quality Score:</strong> 7.2/10
    </div>
    <div class="audio-player">
      <span class="audio-label">Synthesis Output</span>
      <audio controls>
        <source src="assets/audio/example1_model_a.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </div>
  </div>

  <div class="audio-example">
    <h4>Model B</h4>
    <div class="audio-prompt">
      <strong>System:</strong> Neural TTS Model B
      <br><strong>Quality Score:</strong> 6.8/10
    </div>
    <div class="audio-player">
      <span class="audio-label">Synthesis Output</span>
      <audio controls>
        <source src="assets/audio/example1_model_b.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </div>
  </div>
</div>

---

### Example 2: Creaky Voice

<div class="audio-grid">
  <div class="audio-example">
    <h4>Reference Audio</h4>
    <div class="audio-prompt">
      <strong>Prompt:</strong> "I really don't think that's a good idea at all."
      <br><strong>Voice Quality:</strong> Creaky (vocal fry)
    </div>
    <div class="audio-player">
      <span class="audio-label">Ground Truth</span>
      <audio controls>
        <source src="assets/audio/example2_reference.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </div>
  </div>

  <div class="audio-example">
    <h4>Model A</h4>
    <div class="audio-prompt">
      <strong>System:</strong> Neural TTS Model A
      <br><strong>Quality Score:</strong> 4.5/10
    </div>
    <div class="audio-player">
      <span class="audio-label">Synthesis Output</span>
      <audio controls>
        <source src="assets/audio/example2_model_a.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </div>
  </div>

  <div class="audio-example">
    <h4>Model B</h4>
    <div class="audio-prompt">
      <strong>System:</strong> Neural TTS Model B
      <br><strong>Quality Score:</strong> 5.2/10
    </div>
    <div class="audio-player">
      <span class="audio-label">Synthesis Output</span>
      <audio controls>
        <source src="assets/audio/example2_model_b.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </div>
  </div>
</div>

---

### Example 3: Modal Voice (Baseline)

<div class="audio-grid">
  <div class="audio-example">
    <h4>Reference Audio</h4>
    <div class="audio-prompt">
      <strong>Prompt:</strong> "The quick brown fox jumps over the lazy dog."
      <br><strong>Voice Quality:</strong> Modal (neutral)
    </div>
    <div class="audio-player">
      <span class="audio-label">Ground Truth</span>
      <audio controls>
        <source src="assets/audio/example3_reference.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </div>
  </div>

  <div class="audio-example">
    <h4>Model A</h4>
    <div class="audio-prompt">
      <strong>System:</strong> Neural TTS Model A
      <br><strong>Quality Score:</strong> 9.1/10
    </div>
    <div class="audio-player">
      <span class="audio-label">Synthesis Output</span>
      <audio controls>
        <source src="assets/audio/example3_model_a.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </div>
  </div>

  <div class="audio-example">
    <h4>Model B</h4>
    <div class="audio-prompt">
      <strong>System:</strong> Neural TTS Model B
      <br><strong>Quality Score:</strong> 8.9/10
    </div>
    <div class="audio-player">
      <span class="audio-label">Synthesis Output</span>
      <audio controls>
        <source src="assets/audio/example3_model_b.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </div>
  </div>
</div>

---

### Example 4: Tense Voice

<div class="audio-grid">
  <div class="audio-example">
    <h4>Reference Audio</h4>
    <div class="audio-prompt">
      <strong>Prompt:</strong> "Stop right there! Don't you dare move!"
      <br><strong>Voice Quality:</strong> Tense (strained)
    </div>
    <div class="audio-player">
      <span class="audio-label">Ground Truth</span>
      <audio controls>
        <source src="assets/audio/example4_reference.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </div>
  </div>

  <div class="audio-example">
    <h4>Model A</h4>
    <div class="audio-prompt">
      <strong>System:</strong> Neural TTS Model A
      <br><strong>Quality Score:</strong> 5.8/10
    </div>
    <div class="audio-player">
      <span class="audio-label">Synthesis Output</span>
      <audio controls>
        <source src="assets/audio/example4_model_a.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </div>
  </div>

  <div class="audio-example">
    <h4>Model B</h4>
    <div class="audio-prompt">
      <strong>System:</strong> Neural TTS Model B
      <br><strong>Quality Score:</strong> 6.3/10
    </div>
    <div class="audio-player">
      <span class="audio-label">Synthesis Output</span>
      <audio controls>
        <source src="assets/audio/example4_model_b.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </div>
  </div>
</div>

---

### Comparative Model Analysis

<table class="comparison-table">
  <thead>
    <tr>
      <th>Text Prompt</th>
      <th>Voice Quality</th>
      <th>Reference</th>
      <th>Model A</th>
      <th>Model B</th>
      <th>Model C</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>"The meeting starts at noon"</td>
      <td>Modal</td>
      <td><audio controls><source src="assets/audio/comparison1_ref.wav" type="audio/wav"></audio></td>
      <td><audio controls><source src="assets/audio/comparison1_a.wav" type="audio/wav"></audio></td>
      <td><audio controls><source src="assets/audio/comparison1_b.wav" type="audio/wav"></audio></td>
      <td><audio controls><source src="assets/audio/comparison1_c.wav" type="audio/wav"></audio></td>
    </tr>
    <tr>
      <td>"Whisper it quietly"</td>
      <td>Breathy</td>
      <td><audio controls><source src="assets/audio/comparison2_ref.wav" type="audio/wav"></audio></td>
      <td><audio controls><source src="assets/audio/comparison2_a.wav" type="audio/wav"></audio></td>
      <td><audio controls><source src="assets/audio/comparison2_b.wav" type="audio/wav"></audio></td>
      <td><audio controls><source src="assets/audio/comparison2_c.wav" type="audio/wav"></audio></td>
    </tr>
    <tr>
      <td>"I told you so"</td>
      <td>Creaky</td>
      <td><audio controls><source src="assets/audio/comparison3_ref.wav" type="audio/wav"></audio></td>
      <td><audio controls><source src="assets/audio/comparison3_a.wav" type="audio/wav"></audio></td>
      <td><audio controls><source src="assets/audio/comparison3_b.wav" type="audio/wav"></audio></td>
      <td><audio controls><source src="assets/audio/comparison3_c.wav" type="audio/wav"></audio></td>
    </tr>
  </tbody>
</table>

<div class="placeholder-notice">
  🎵 Audio files are placeholders. Replace with your actual audio files in the assets/audio/ directory.
</div>

---

## 📈 Dataset Information

The **Lost in Phonation** dataset includes:

- **1,200+ utterances** covering diverse voice quality types
- **Multi-speaker recordings** (20 speakers, balanced gender distribution)
- **Expert annotations** for voice quality dimensions (H1-H2, H1-A3, CPP, etc.)
- **Acoustic measures** including fundamental frequency, spectral tilt, and formant trajectories
- **Perceptual ratings** from trained phoneticians

### Dataset Structure

```
dataset/
├── audio/
│   ├── breathy/
│   ├── creaky/
│   ├── modal/
│   ├── tense/
│   └── mixed/
├── annotations/
│   ├── voice_quality_labels.csv
│   ├── acoustic_features.csv
│   └── perceptual_ratings.csv
└── metadata/
    ├── speaker_info.json
    └── recording_conditions.json
```

<div class="paper-links">
  <a href="#" target="_blank">📦 Download Full Dataset</a>
  <a href="#" target="_blank">📊 View Dataset Statistics</a>
</div>

---

## 🔬 Methodology

Our benchmark evaluation follows a rigorous protocol:

1. **Data Collection**: Systematic elicitation of various voice qualities from professional voice actors
2. **Annotation**: Multi-rater annotation scheme with inter-rater reliability measures
3. **Feature Extraction**: Acoustic analysis using established voice quality metrics
4. **Model Evaluation**: Systematic testing of TTS systems on the benchmark
5. **Analysis**: Statistical comparison and perceptual validation

### Evaluation Metrics

- **Acoustic Similarity**: MCD, F0 RMSE, spectral envelope distance
- **Voice Quality Metrics**: H1-H2, H1-A3, CPP, jitter, shimmer
- **Perceptual Measures**: MOS ratings, ABX discrimination tests
- **Objective Quality**: PESQ, STOI, speaker similarity

---

## 💻 Code and Resources

### Quick Start

```bash
# Clone the repository
git clone https://github.com/username/lost-in-phonation.git
cd lost-in-phonation

# Install dependencies
pip install -r requirements.txt

# Run benchmark evaluation
python evaluate.py --model your_model --dataset data/
```

### Reproduce Results

```python
from lost_in_phonation import Benchmark, Evaluator

# Load benchmark dataset
benchmark = Benchmark.load('dataset/')

# Evaluate your model
evaluator = Evaluator(benchmark)
results = evaluator.evaluate(your_model)

# Generate report
evaluator.generate_report(results, output='results.html')
```

<div class="paper-links">
  <a href="#" target="_blank">💻 GitHub Repository</a>
  <a href="#" target="_blank">📚 Documentation</a>
  <a href="#" target="_blank">🐍 PyPI Package</a>
</div>

---

## 📝 Citation

If you use this benchmark in your research, please cite:

<div class="citation-box">
@inproceedings{authors2025lostinphonation,
  title={Lost in Phonation: A Benchmark for Voice Quality in Speech Synthesis},
  author={Author1, Author2, Author3},
  booktitle={Proceedings of LREC-COLING 2025},
  year={2025}
}
</div>

---

## 👥 Team

This work was conducted by researchers at [Institution Name].

**Principal Investigators:**
- [Name 1] - [Email]
- [Name 2] - [Email]

**Contributors:**
- [Name 3] - Data Collection
- [Name 4] - Annotation
- [Name 5] - Analysis

---

## 📧 Contact

For questions, suggestions, or collaborations:

- **Email**: contact@example.com
- **GitHub Issues**: [Report an issue](https://github.com/username/lost-in-phonation/issues)
- **Twitter**: [@ProjectHandle](https://twitter.com/handle)

---

## 📜 License

This dataset and code are released under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

---

<div style="text-align: center; margin-top: 3rem; padding-top: 2rem; border-top: 2px solid #e0e0e0; color: #666;">
  <p>© 2025 Lost in Phonation Project. All rights reserved.</p>
  <p>Built with ❤️ for the speech synthesis research community</p>
</div>
