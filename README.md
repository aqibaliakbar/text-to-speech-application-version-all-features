# Text to Speech Model Using Elevenlabs API | Voice Cloning | Recording

A modern and feature-rich Text-to-Speech application built with Next.js and powered by ElevenLabs' state-of-the-art AI voice technology.

![tts](https://github.com/user-attachments/assets/78c5926b-f4fa-4b8b-870a-04d0bb441db5)


## 🚀 Features

- **Premium AI Voices**: Access to ElevenLabs' high-quality, lifelike AI voices
- **Voice Customization**: Adjust voice settings including stability and clarity
- **Real-time Preview**: Listen to generated speech in real-time
- **Save & Export**: Export audio files in MP3 format
- **User-friendly Interface**: Clean, intuitive UI built with modern web technologies
- **History Management**: Track and replay previously generated speech
- **Text Formatting**: Support for SSML tags for advanced voice control

## 🛠️ Technology Stack

- **Framework**: Next.js (React framework)
- **Styling**: Tailwind CSS for utility-first styling
- **UI Components**: ShadCn UI library (built on Tailwind)
- **Voice Technology**: ElevenLabs API integration
- **State Management**: React Context API
- **API Integration**: Next.js API routes
- **Audio Processing**: Web Audio API for playback

## 📋 Prerequisites

Before you begin, ensure you have the following:
- [Node.js](https://nodejs.org/) (v16.x or later)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- An [ElevenLabs](https://elevenlabs.io/) API key

## 🔧 Installation

1. Clone the repository:
```bash
git clone https://github.com/aqibaliakbar/text-to-speech-application-version-all-features.git
cd text-to-speech-application-version-all-features
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Create a `.env.local` file in the root directory with your ElevenLabs API key:
```
NEXT_PUBLIC_ELEVENLABS_API_KEY=your_elevenlabs_api_key
```

4. Start the development server:
```bash
npm run dev
# or
yarn dev
```

5. Open your browser and navigate to `http://localhost:3000`

## 📝 Usage

1. Enter your text in the input area
2. Select your preferred voice from the dropdown menu
3. Adjust voice settings as needed (stability, clarity, etc.)
4. Click "Generate" to convert your text to speech
5. Use the playback controls to listen to the generated audio
6. Click "Download" to save the audio as an MP3 file

## ✨ Voice Features

This application leverages ElevenLabs' advanced voice technology to provide:

- Natural-sounding speech with human-like intonation and emotion
- Various voice styles and personalities to choose from
- Real-time streaming capabilities for immediate feedback
- Adjustable voice parameters for customized output

## 🔒 Environment Variables

- `NEXT_PUBLIC_ELEVENLABS_API_KEY`: Your ElevenLabs API key

## 🚀 Deployment

To build the application for production:

```bash
npm run build
# or
yarn build
```

The build artifacts will be stored in the `.next/` directory. You can deploy to platforms like Vercel or Netlify that support Next.js deployments.

## 📚 API Documentation

This application uses the ElevenLabs API for text-to-speech conversion. For more information about the API, visit the [ElevenLabs Documentation](https://elevenlabs.io/docs).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👏 Acknowledgements

- [ElevenLabs](https://elevenlabs.io/) for providing the AI voice technology
- [Next.js](https://nextjs.org/) for the React framework
- [Tailwind CSS](https://tailwindcss.com/) for utility-first styling
- [ShadCn UI](https://ui.shadcn.com/) for the UI components
- All the open-source libraries and tools used in this project
