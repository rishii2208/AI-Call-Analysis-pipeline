## Technical Details

### Models Used

- **Speaker Diarization**: pyannote/speaker-diarization-3.1
- **Speech Recognition**: OpenAI Whisper-small
- **Text Classification**: Facebook BART-large-mnli
- **Response Generation**: Facebook BlenderBot-400M-distill

### Processing Pipeline

1. Audio preprocessing and format conversion
2. Speaker identification and segmentation
3. Speech-to-text transcription
4. Natural language understanding
5. Intent classification and analysis
6. Probability calculation
7. Response generation
8. Visualization and export

###Model Chaining Strategy

- 1. Diarization → 2. Transcription → 3. Analysis → 4. Response
- (Structure)     (Content)        (Understanding)  (Action)
