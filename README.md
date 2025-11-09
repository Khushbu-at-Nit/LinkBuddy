# LinkBuddy

**LinkBuddy** is a web-based tool that fetches content from URLs and uses a local LLM (Large Language Model) to generate responses or summaries. It’s built with HTML, CSS, JavaScript, and the MediaPipe GenAI library for inference.

---

## Features

- **URL Content Fetching**: Enter a URL to fetch its content directly into the app.
- **LLM Inference**: Uses the `gemma-2b-it-gpu-int4.bin` model to generate responses based on the fetched content.
- **User-Friendly UI**: Clean, modern interface with loading indicators and responsive design.
- **Real-Time Output**: Displays generated responses in real-time as they are produced.

---

## Demo

![LinkBuddy UI](demo.png) *(Add a screenshot of your app here if available)*

---

## Setup

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, etc.).
- Internet connection to load the MediaPipe library and fetch URL content.

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/linkbuddy.git
   cd linkbuddy
