# InterviewAI 🎙️

An AI-powered platform for preparing for mock interviews with real-time voice interaction and comprehensive feedback.

## 🌟 Features

### Core Functionality
- **AI-Powered Voice Interviews**: Real-time voice conversations with an AI interviewer using Vapi AI
- **Personalized Question Generation**: Custom interview questions based on role, experience level, and tech stack
- **Real-time Feedback**: Instant analysis and scoring across multiple categories
- **Interview History**: Track and review past interview sessions
- **Multi-format Support**: Technical, behavioral, and mixed interview types

### Technical Capabilities
- **Voice Integration**: Natural voice conversations with speech-to-text and text-to-speech
- **Smart Question Generation**: AI-generated questions using Google's Gemini 2.0 Flash model
- **Comprehensive Scoring**: 5-category evaluation system with detailed feedback
- **Technology Stack Recognition**: Support for 50+ technologies and frameworks
- **User Authentication**: Secure Firebase authentication with session management

## 🚀 Tech Stack

### Frontend
- **Next.js 15.2.2** - React framework with App Router
- **React 19** - User interface library
- **TypeScript** - Type-safe development
- **Tailwind CSS 4** - Utility-first styling
- **Radix UI** - Accessible component primitives
- **Lucide React** - Beautiful icons

### Backend & AI
- **Vapi AI** - Voice AI platform for real-time conversations
- **Google AI (Gemini 2.0)** - Question generation and feedback analysis
- **Firebase** - Authentication and Firestore database
- **Firebase Admin** - Server-side Firebase operations

### Development Tools
- **ESLint** - Code linting
- **React Hook Form** - Form management
- **Zod** - Schema validation
- **Day.js** - Date manipulation

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd ai_mock_interviews
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Environment Setup**
   Create a `.env.local` file with the following variables:

4. **Firebase Setup**
   - Create a Firebase project
   - Enable Authentication (Email/Password)
   - Set up Firestore database
   - Generate and download admin SDK credentials

5. **Run the development server**
   ```bash
   npm run dev
   ```

   Open [http://localhost:3000](http://localhost:3000) to view the application.

## 🎯 Usage

### Getting Started
1. **Sign Up/Sign In**: Create an account or log in with existing credentials
2. **Start Interview**: Click "Start an Interview" from the dashboard
3. **Configure Interview**: Select role, experience level, tech stack, and question count
4. **Begin Voice Interview**: Click "Call" to start the AI-powered voice interview
5. **Receive Feedback**: Get comprehensive feedback and scoring after completion

### Interview Process
1. **Question Generation**: AI generates relevant questions based on your configuration
2. **Voice Conversation**: Natural voice interaction with the AI interviewer
3. **Real-time Transcription**: Live transcription of the conversation
4. **Automated Analysis**: AI analyzes responses across 5 key categories
5. **Detailed Feedback**: Receive scores, strengths, and improvement areas

### Feedback Categories
- **Communication Skills** - Clarity and articulation
- **Technical Knowledge** - Domain-specific expertise
- **Problem Solving** - Analytical thinking approach
- **Cultural Fit** - Alignment with company values
- **Confidence and Clarity** - Presentation and self-assurance

## 🏗️ Project Structure

```
ai_mock_interviews/
├── app/                          # Next.js App Router
│   ├── (auth)/                   # Authentication routes
│   │   ├── sign-in/
│   │   └── sign-up/
│   ├── (root)/                   # Main application routes
│   │   ├── interview/
│   │   │   ├── [id]/            # Dynamic interview routes
│   │   │   │   ├── feedback/    # Feedback display
│   │   │   │   └── page.tsx     # Interview session
│   │   │   └── page.tsx         # Interview setup
│   │   └── page.tsx             # Dashboard
│   ├── api/                     # API routes
│   │   └── vapi/
│   │       └── generate/        # Question generation endpoint
│   └── globals.css              # Global styles
├── components/                  # Reusable components
│   ├── ui/                      # UI primitives
│   ├── Agent.tsx                # Voice interaction component
│   ├── AuthForm.tsx             # Authentication forms
│   ├── InterviewCard.tsx        # Interview display card
│   └── DisplayTechIcons.tsx     # Technology icons
├── lib/                         # Utilities and actions
│   ├── actions/                 # Server actions
│   ├── utils.ts                 # Helper functions
│   └── vapi.sdk.ts              # Vapi AI SDK setup
├── constants/                   # Application constants
├── firebase/                    # Firebase configuration
├── types/                       # TypeScript definitions
└── public/                      # Static assets
```

## 🔧 Configuration

### Supported Technologies
The platform supports 50+ technologies including:
- **Frontend**: React, Vue.js, Angular, Next.js, Nuxt.js
- **Backend**: Node.js, Express.js, NestJS
- **Databases**: MongoDB, PostgreSQL, MySQL, Firebase
- **Cloud**: AWS, Azure, GCP, Vercel, Netlify
- **And many more...**

### Interview Customization
- **Roles**: Any job position
- **Experience Levels**: Junior, Mid-level, Senior
- **Interview Types**: Technical, Behavioral, Mixed
- **Question Count**: 1-20 questions per session

## 🚀 Deployment

### Build for Production
```bash
npm run build
npm start
```

### Deploy to Vercel
1. Connect your repository to Vercel
2. Configure environment variables
3. Deploy automatically on push to main branch

## 🔒 Security Features

- **Firebase Authentication**: Secure user authentication
- **Session Management**: HTTP-only cookies with secure settings
- **Server-side Validation**: Zod schema validation
- **Environment Variables**: Secure API key management

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🆘 Support

For support and questions:
- Open an issue on GitHub
- Check existing documentation
- Review the troubleshooting section

## 🎉 Acknowledgments

- **Vapi AI** for voice interaction capabilities
- **Google AI** for advanced language models
- **Firebase** for backend infrastructure
- **Vercel** for deployment platform
- **Next.js** team for the excellent framework

---

Built with ❤️ using modern web technologies for the next generation of interview preparation.