# 🤖 AI Research Paper Assistant

<div align="center">
  <img src="https://res.cloudinary.com/ddz20cb8v/image/upload/v1755791983/Screenshot_2025-08-21_212712_uarpev.png" alt="AI Research Paper Assistant Interface" width="800"/>
  
  [![Python](https://img.shields.io/badge/Python-3.13+-blue.svg)](https://www.python.org/downloads/)
  [![Streamlit](https://img.shields.io/badge/Streamlit-1.48+-red.svg)](https://streamlit.io/)
  [![LangChain](https://img.shields.io/badge/LangChain-0.3+-green.svg)](https://langchain.com/)
  [![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
</div>

## 📋 Overview

An intelligent AI-powered research assistant that helps researchers **discover, analyze, and generate academic papers** efficiently. Built with modern AI technologies including Google's Gemini 2.5 Pro, LangChain, and LangGraph, this tool streamlines the entire research workflow from literature discovery to paper generation.

## ✨ Key Features

### 🔍 **Intelligent Paper Discovery**
- **arXiv Integration**: Automated search across arXiv's vast repository
- **Smart Filtering**: Find relevant papers based on research topics
- **Citation Tracking**: Automatic reference management with PDF links

### 📚 **Advanced Analysis & Understanding**
- **PDF Processing**: Extract and analyze research papers automatically
- **Key Insight Extraction**: Identify main findings and methodologies
- **Future Work Analysis**: Discover promising research directions

### 🤖 **AI-Powered Paper Generation**
- **LaTeX Generation**: Create properly formatted academic papers
- **Mathematical Equations**: Support for complex mathematical notation
- **Structured Output**: Generate complete research papers with proper sections

### 💬 **Interactive Chat Interface**
- **Streamlit UI**: Modern, responsive web interface
- **Real-time Streaming**: Watch AI responses as they're generated
- **Conversation Memory**: Maintain context throughout research sessions

## 🏗️ Architecture

This project leverages a sophisticated AI workflow built with:

- **LangGraph**: Orchestrates the research workflow with state management
- **Google Gemini 2.5 Pro**: Powers the AI reasoning and content generation
- **LangChain**: Provides the framework for AI tool integration
- **Streamlit**: Delivers the user-friendly web interface

## 🚀 Quick Start

### 🌐 Live Demo

**Try the application online:** [https://ai-research-paper-8z9u.onrender.com](https://ai-research-paper-8z9u.onrender.com)

### Prerequisites

- Python 3.13 or higher
- Google API key for Gemini 2.5 Pro
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/ai-research-paper.git
   cd ai-research-paper
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up environment variables**
   Create a `.env` file in the root directory:
   ```env
   GOOGLE_API_KEY="your_google_api_key_here"
   ```

4. **Run the application**
   ```bash
   streamlit run frontend.py
   ```

5. **Access the application**
   Open your browser and navigate to: [http://localhost:8501](http://localhost:8501)

## 📖 Usage Guide

### 1. **Start a Research Session**
- Enter your research topic in the chat interface
- The AI will help you explore and refine your research direction

### 2. **Discover Relevant Papers**
- The assistant searches arXiv for recent papers in your field
- Review summaries and select papers of interest

### 3. **Analyze Research Content**
- Upload or reference papers for detailed analysis
- Extract key insights and identify research gaps

### 4. **Generate New Research**
- Based on analysis, the AI suggests novel research directions
- Generate complete research papers with proper academic formatting

## 🛠️ Project Structure

```
ai-research-paper/
├── frontend.py              # Streamlit web interface
├── ai_researcher_2.py       # Main AI workflow and LangGraph setup
├── arxiv_tool.py           # arXiv API integration
├── read_pdf.py             # PDF processing and analysis
├── write_pdf.py            # LaTeX generation and PDF rendering
├── requirements.txt        # Python dependencies
├── pyproject.toml         # Project configuration
├── render.yaml            # Render.com deployment config
├── .streamlit/            # Streamlit configuration
│   └── config.toml
└── output/                # Generated papers and outputs
```

## 🔧 Configuration

### Environment Variables

| Variable | Description | Required |
|----------|-------------|----------|
| `GOOGLE_API_KEY` | Google Gemini API key | Yes |

### Streamlit Configuration

The application is configured for optimal performance with:
- Headless mode for deployment
- CORS disabled for web access
- Memory optimization settings

## 🌐 Deployment

### Render.com Deployment

This project is configured for easy deployment on Render.com:

1. **Connect your repository** to Render.com
2. **Create a new Web Service**
3. **Use the provided `render.yaml`** configuration
4. **Set environment variables** in Render dashboard
5. **Deploy automatically** on every push

### Local Development

For local development, ensure you have:
- Python 3.13+ installed
- Virtual environment activated
- All dependencies installed
- Environment variables configured

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Google Gemini Team** for providing the powerful AI model
- **LangChain Community** for the excellent AI framework
- **Streamlit Team** for the intuitive web framework
- **arXiv** for providing access to research papers

## 📞 Support

If you encounter any issues or have questions:

- 📧 **Email**: your-email@example.com
- 🐛 **Issues**: [GitHub Issues](https://github.com/yourusername/ai-research-paper/issues)
- 📖 **Documentation**: [Wiki](https://github.com/yourusername/ai-research-paper/wiki)

---

<div align="center">
  <p>Made with ❤️ by the AI Research Team</p>
  <p>⭐ Star this repository if you find it helpful!</p>
</div>
