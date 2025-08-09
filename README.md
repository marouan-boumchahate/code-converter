# Code Converter 🔄

A powerful AI-powered tool that converts code between different programming languages with high performance optimizations. Built with OpenAI's GPT-4o and featuring a sleek Gradio interface.

![Code Converter Demo](https://via.placeholder.com/800x400/667eea/ffffff?text=Code+Converter+Interface)

## ✨ Features

- **Multi-language Support**: Convert between Python, JavaScript, C++, C#, Java, and Rust
- **AI-Powered**: Leverages OpenAI's GPT-4o for intelligent code translation
- **Performance Optimized**: Focuses on generating the fastest possible implementation
- **Real-time Streaming**: See your code being converted in real-time
- **Clean Interface**: Modern, responsive UI built with Gradio
- **Ready-to-Run**: Generated code includes all necessary imports and dependencies

## 🚀 Quick Start

### Prerequisites

- Python 3.7+
- OpenAI API key

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/code-converter.git
cd code-converter
```

2. Install required packages:
```bash
pip install openai python-dotenv gradio ipython
```

3. Set up your OpenAI API key:
   - Create a `.env` file in the project root
   - Add your OpenAI API key:
```env
OPENAI_API_KEY=your_openai_api_key_here
```

### Usage

1. **Jupyter Notebook**: Open `Code_Converter.ipynb` and run all cells
2. **Direct Script**: Convert the notebook to a Python script and run it

The application will launch in your default browser at `http://127.0.0.1:7884`

## 🎯 How It Works

1. **Select Languages**: Choose your source and target programming languages
2. **Input Code**: Paste your code in the source code textbox
3. **Convert**: Click the "Convert Code" button
4. **Get Results**: Watch as the AI generates optimized code in your target language

## 📋 Supported Languages

- **Python** 🐍
- **JavaScript** 🟨
- **C++** ⚡
- **C#** 💙
- **Java** ☕
- **Rust** 🦀

## 🛠️ Technical Details

### Architecture

- **Backend**: OpenAI GPT-4o API with streaming responses
- **Frontend**: Gradio web interface with custom CSS styling
- **Environment**: Jupyter Notebook compatible

### Key Components

- **System Prompt**: Optimized for high-performance code generation
- **User Prompt**: Dynamic prompt generation based on language selection
- **Streaming**: Real-time code generation display
- **Error Handling**: Built-in error prevention and code validation

## 🎨 Interface Features

- **Gradient Buttons**: Beautiful gradient styling with hover effects
- **Glass Morphism**: Modern frosted glass effect on containers
- **Responsive Design**: Works on desktop and mobile devices
- **Real-time Updates**: Live code generation with streaming

## ⚙️ Configuration

### Environment Variables

Create a `.env` file with the following:

```env
OPENAI_API_KEY=your_api_key_here
```

### Model Configuration

The default model is GPT-4o, but you can modify it in the notebook:

```python
OPENAI_MODEL = "gpt-4o"  # Change to your preferred model
```

## 📝 Example Usage

**Input (Python):**
```python
def fibonacci(n):
    if n <= 1:
        return n
    return fibonacci(n-1) + fibonacci(n-2)

print(fibonacci(10))
```

**Output (C++):**
```cpp
#include <iostream>
using namespace std;

int fibonacci(int n) {
    if (n <= 1) {
        return n;
    }
    return fibonacci(n-1) + fibonacci(n-2);
}

int main() {
    cout << fibonacci(10) << endl;
    return 0;
}
```

## 🙏 Acknowledgments

- OpenAI for providing the powerful GPT-4o API
- Gradio team for the excellent web interface framework
- The open-source community for continuous inspiration

## 🔮 Future Enhancements

- [ ] Support for more programming languages
- [ ] Code optimization suggestions
- [ ] Batch file conversion
- [ ] Code quality metrics
- [ ] Export functionality
- [ ] Dark/Light theme toggle
- [ ] Code syntax highlighting

---

**⭐ If you find this project helpful, please consider giving it a star!**
