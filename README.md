## WordFlow: Voice-to-Image Generator

A desktop application that allows users to speak a prompt in any language, translate and transcribe it, and generate high-quality images using the Stable Diffusion model. The app also evaluates image and audio quality using FID (Fréchet Inception Distance), Inception Score (IS), and MOS (Mean Opinion Score) estimations.

## Features

- Speech Recognition
- Translation
- Image Generation
- Image saves to downloads folder
- # Quality Metrics:
  - FID Score: Real vs Generated image similarity
  - Inception Score: Image diversity & quality
  - MOS Estimate: TTS audio naturalness

## How to Use
1. Run the App
2. Record Voice Prompt:
   - Click the Speak button to record your voice
   - The app will transcribe and translate it.
3. Generate Image:
   - Press Generate Image to create an image based on the translated prompt
4. Save Image:
   - Use Save Image to download it to your system
5. Translate prompt (If other language):
   - Enter text manually and click Translate to process it.
  
## Platform Support
- macOS (Optimized for Apple Silicon with MPS)
- Windows/Linux (uses CPU/GPU if available)

## Notes
- Ensure you have at least two real and two generated images to compute FID.

## Credits
- Stable Diffusion
- OpenAI Whisper
- Google Translate
- Pytorch FID
