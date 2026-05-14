# Traditional Telugu Cuisine Data Collection Platform

**Deployed Link:** https://hemaditya05-manateluguruchulu-app-dzqgkp.streamlit.app/

**Video Discussion Link:** [https://drive.google.com/file/d/1gg6XEaeOErWUE3EoqwCo6WYu16vqZAJj/view?usp=sharing](https://drive.google.com/file/d/1gg6XEaeOErWUE3EoqwCo6WYu16vqZAJj/view?usp=sharing)

# Mana Telugu Ruchulu

A modern, user-friendly platform for sharing and preserving traditional Telugu recipes. This app provides a beautiful, accessible interface for submitting, browsing, and celebrating Telugu culinary heritage.

## Features
- Clean, responsive UI with custom CSS
- Step-by-step recipe submission form
- Multilingual interface (English & Telugu)
- In-memory storage for demo/testing (no database required)
- Static user model (no authentication needed)
- Support for text, ingredients, and method entry
- Modern navigation and form styling

## Getting Started

### Prerequisites
- Python 3.8+
- [Streamlit](https://streamlit.io/)

### Installation
1. Clone this repository:
   ```bash
   git clone <your-repo-url>
   cd ManaTeluguRuchulu
   ```
2. (Optional) Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the App
```bash
streamlit run app.py
```

The app will open in your browser at `http://localhost:8501`.

## Usage
- Use the navigation bar to explore, contribute, or learn about the project.
- Submit recipes using the "Contribute" page. All fields are optional for demo purposes.
- Browse submitted recipes on the "Explore" page.
- The interface is always logged in as a static user (`demo`).

## Customization
- **Styling:** Edit `style.css` to change the look and feel.
- **Language:** Add or modify translations in `app.py`.
- **Persistence:** For production, connect to a real database and implement authentication.

## Credits
- UI/UX: Inspired by modern recipe and community platforms
- Built with [Streamlit](https://streamlit.io/)
- Designed for the Telugu food community



For questions or contributions, please open an issue or pull request. 