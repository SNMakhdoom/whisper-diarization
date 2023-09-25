# Speech Processing Pipeline for Diarization and Punctuation Restoration

This GitHub repository contains a comprehensive speech processing pipeline for diarization and punctuation restoration. It leverages state-of-the-art AI models and cloud infrastructure to provide accurate results for audio data.

## Key Features

- **Diarization:** The pipeline uses the NeMo ASR library to perform speaker diarization on telephonic audio data. It identifies and labels speakers in the audio, enabling better comprehension of conversations.

- **Punctuation Restoration:** For supported languages, punctuation restoration is applied to enhance the readability of transcriptions. This step ensures that sentences are correctly punctuated, improving the overall transcript quality.

- **AWS Deployment:** The pipeline is designed to be deployed on Amazon Web Services (AWS), utilizing cloud resources for scalability and reliability.

- **Custom Domain:** The application is hosted with a custom domain, providing a user-friendly interface for accessing and interacting with the diarized and punctuated audio transcripts.

## Usage

1. Upload your audio file to the pipeline.
2. The pipeline will perform speaker diarization and, if applicable, punctuation restoration.
3. Access the results through the provided custom domain.

## Dependencies

- Python
- NeMo ASR Library
- Whisper Model
- AWS (for deployment)
- OmegaConf
- librosa
- soundfile
- wget
- deepmultilingualpunctuation

## Deployment Instructions

1. Clone this repository.
2. Configure your AWS settings for deployment.
3. Run the provided script to deploy the pipeline.
4. Access the deployed application through the custom domain.
