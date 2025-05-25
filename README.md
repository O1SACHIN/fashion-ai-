# AI Fashion Style Assistant

An intelligent chatbot that helps users find their perfect fashion style based on their unique characteristics and preferences.

## Features

- Interactive chat interface
- Personalized style recommendations
- Analysis based on:
  - Face shape
  - Skin tone
  - Body type
  - Style goals
  - Favorite colors
  - Occasion type
- Markdown-formatted responses
- Mobile-friendly design

## Tech Stack

- React with TypeScript
- Material-UI for styling
- OpenAI GPT-4 API for AI interactions
- Firebase (optional) for user data storage

## Setup

1. Clone the repository:
```bash
git clone <repository-url>
cd fashion-style-assistant
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory and add your OpenAI API key:
```
REACT_APP_OPENAI_API_KEY=your_api_key_here
```

4. Start the development server:
```bash
npm start
```

The application will be available at `http://localhost:3000`.

## Environment Variables

- `REACT_APP_OPENAI_API_KEY`: Your OpenAI API key

## Usage

1. Open the application in your browser
2. Start chatting with the AI fashion assistant
3. Answer the questions about your characteristics and preferences
4. Receive personalized style recommendations

## Development

- The main chat interface is in `src/components/ChatInterface.tsx`
- OpenAI service is in `src/services/openai.ts`
- Styling is handled through Material-UI components

## Security Notes

- In production, you should implement a backend proxy for OpenAI API calls
- Never expose your API keys in the frontend code
- Consider implementing user authentication for storing preferences

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License

MIT License 