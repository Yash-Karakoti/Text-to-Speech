# Text-to-Speech with Coqui TTS

## Installation

1. Clone the Repository
```bash
git clone https://github.com/Yash-Karakoti/Text-to-Speech.git
cd Text-to-Speech
```
2. Environment Setup
```bash
python -m venv .venv
.venv\Scripts\activate
```
3. Install Dependencies
```bash
pip install -r requirements.txt
```
4. Generate your first speech output
```bash
tts --text "Hello, This is my first speech output using Coqui TTS" --model_name tts_models/en/ek1/tacotron2 --out_path output/output.wav
```
