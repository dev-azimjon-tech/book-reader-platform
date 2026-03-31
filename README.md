# BookReader Platform

A free, feature-rich online platform for discovering and reading books instantly in your browser. Access thousands of books without downloads—perfect for readers who want instant access to their favorite stories anytime, anywhere.

## About BookReader Platform

BookReader Platform is designed to make reading accessible to everyone. Our lightweight, browser-based reader lets you explore a vast library of books for free, track your reading progress, and connect with other book lovers—all without leaving your browser.

## Core Features

### Free Book Search & Reading
Search and read any book from our library instantly—completely free. Normal mode includes ads to support the platform, while ad-free reading is available in premium mode.

### Favorite Books & Personal Library
Build your collection by saving favorite books to your profile. Keep track of books you love and want to revisit anytime.

### Reading Limits & Premium Mode
- **Normal Mode**: Read up to 2 books simultaneously
- **Premium Mode**: Unlock the ability to read up to 10 books at the same time

### Video Book Versions
Experience stories in a new way. Watch video versions of books alongside reading, combining visual storytelling with traditional reading.

### Follow Readers & Discover Books
Follow other readers in the community and see what books they're currently reading. Discover new titles through the interests of readers you follow.

### Reading Progress Tracking
Automatically save your reading position in every book. Pick up right where you left off, whether you're reading on desktop or mobile.

### Notes & Bookmarks
Highlight important passages and leave personal notes as you read. Build your personal annotations library for future reference.

### Secure User Accounts
Create a personal account to keep your library, progress, and preferences synced across all devices.

## Tech Stack

- **Backend & Frontend**: [Flask](https://flask.palletsprojects.com/) (Python)
- **Frontend Technologies**: HTML5, CSS3, JavaScript (Vanilla)
- **Database**: Local JSON storage (Simple & Fast)
- **Development Tools**: Claude, Gemini CLI

## Getting Started

### Prerequisites
- [Python 3.9+](https://www.python.org/downloads/)
- [pip](https://pip.pypa.io/en/stable/installation/) (Python package manager)

### Installation Steps

**1. Clone the repository**
```bash
git clone https://github.com/dev-azimjon-tech/book-reader-platform.git
cd book-reader-platform
```

**2. Create a Virtual Environment** (Recommended)
```bash
# Create virtual environment
python -m venv venv

# Activate it
# On macOS/Linux:
source venv/bin/activate
# On Windows:
venv\Scripts\activate
```

**3. Install Dependencies**
```bash
pip install flask flask-login flask-cors
```

**4. Start the Application**
```bash
python app.py
```

Open your browser and navigate to: **`http://127.0.0.1:5000`**

Your BookReader Platform is now ready to use!
