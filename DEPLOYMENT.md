# 🔮 Gemini Vision Pro - Image Analysis Studio

A powerful image analysis application powered by Google's Gemini 2.0 Flash AI model.

## Features

- 📸 **Advanced Image Analysis** - Upload and analyze images with AI
- 🔍 **OCR Capabilities** - Extract text from images
- 💬 **Natural Language Queries** - Ask questions about your images
- ⚡ **Fast Processing** - Powered by Gemini 2.0 Flash
- 📥 **Export Results** - Download analysis as text files

## Live Demo

🚀 [Try it on Streamlit Cloud](your-app-url-here)

## Local Setup

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd gemini-vision-pro
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up your API key**
   - Create a `.env` file in the project root
   - Add your Google API key:
     ```
     GOOGLE_API_KEY=your_api_key_here
     ```
   - Get your API key from [Google AI Studio](https://aistudio.google.com/app/apikey)

4. **Run the app**
   ```bash
   streamlit run app.py
   ```

## Deployment to Streamlit Cloud

### Prerequisites
- GitHub account
- Google Gemini API key

### Steps

1. **Push to GitHub**
   - Create a new repository on GitHub
   - Push this code to your repository

2. **Deploy on Streamlit Cloud**
   - Go to [share.streamlit.io](https://share.streamlit.io)
   - Click "New app"
   - Select your GitHub repository
   - Set main file: `app.py`
   - Click "Advanced settings"
   - Add your secrets:
     ```toml
     GOOGLE_API_KEY = "your_api_key_here"
     ```
   - Click "Deploy"

## Configuration

The app uses the following environment variables:

- `GOOGLE_API_KEY` - Your Google Gemini API key (required)

## Tech Stack

- **Streamlit** - Web framework
- **Google Gemini 2.0 Flash** - AI model
- **Python 3.8+** - Programming language
- **PIL/Pillow** - Image processing

## Usage

1. Open the application
2. Enter your question or analysis request
3. Upload an image (JPEG/PNG)
4. Click "Analyze with Gemini AI"
5. View and download the results

## Requirements

See `requirements.txt` for all dependencies.

## License

MIT License

## Support

For issues or questions, please open an issue on GitHub.

---

Created with ❤️ using Streamlit and Gemini AI
