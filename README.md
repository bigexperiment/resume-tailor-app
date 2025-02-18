# Resume Tailor

Resume Tailor is a simple web application that helps you generate tailored bullet points for your resume based on specific skills or requirements. It uses AI to help you highlight your experiences in a concise, achievement-oriented way.

## Features

- **AI-Powered Bullet Points**: Generate professional resume bullet points tailored to specific skills
- **Custom Prompts**: Create and save up to 10 different prompts for different use cases
- **Local Storage**: Automatically saves your resume and keywords for convenience
- **Copy to Clipboard**: Easy one-click copying of generated content
- **Real-time Streaming**: See the AI-generated content appear in real-time
- **Mobile Responsive**: Works well on both desktop and mobile devices

## How to Use

1. **First Time Setup**:
   - Click the ⚙️ (settings) icon
   - Enter your OpenAI API key
   - Click Save

2. **Basic Usage**:
   - Paste your resume content in the "Your Resume" field
   - Enter the skills you want to highlight in the "Key Skills" field
   - Click "Generate" to create tailored bullet points
   - Use the copy button (📋) to copy the results

3. **Working with Prompts**:
   - Use the default "Resume Bullet Points" prompt, or create your own
   - Click the ⚙️ icon to manage prompts
   - Create new prompts with the "+ New Prompt" button
   - Select different prompts from the dropdown menu before generating

## Custom Prompts

You can create custom prompts for different purposes:
- Different job types
- Different skill sets
- Different industries
- Different resume sections

The app will remember your last used prompt and automatically select it when you return.

## Tips for Best Results

1. **Resume Content**:
   - Provide relevant experience sections from your resume
   - Include specific details about your roles and responsibilities

2. **Skills Input**:
   - Be specific with the skills you want to highlight
   - Separate multiple skills with spaces
   - Example: "React.js Node.js TypeScript"

3. **Prompt Customization**:
   - Create specific prompts for different types of positions
   - Keep prompts focused and clear
   - Test different prompts to see what works best

## Technical Details

- Single HTML file application
- No server required
- Uses OpenAI's GPT API
- Data stored locally in browser
- No external dependencies

## Privacy & Security

- Your API key and resume content are stored locally in your browser
- No data is sent to any server except OpenAI's API
- Clear your browser data to remove stored information

## Limitations

- Requires an OpenAI API key
- Maximum 10 custom prompts
- Limited to browser local storage capacity
- Requires internet connection for AI generation

## Support

For issues or questions:
1. Check if your API key is valid
2. Ensure you have internet connectivity
3. Try clearing your browser cache if experiencing issues
4. Make sure you're using a modern web browser

## License

MIT License - Feel free to use and modify as needed.
