# Flask Project

A simple Flask web application that returns "Hello, World!" on the homepage.

## Project Structure

- `main.py` - Flask application entry point
- `requirements.txt` - Python dependencies for the project

## Requirements

- Python 3.10 or later
- pip

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/gavithgethmin01/Flask.git
   cd Flask
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   ```

3. Activate the virtual environment:

   On macOS/Linux:
   ```bash
   source venv/bin/activate
   ```

   On Windows:
   ```bash
   venv\Scripts\activate
   ```

4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Run the Application

```bash
python main.py
```

Then open your browser and visit:

```text
http://127.0.0.1:5000/
```

You should see:

```text
Hello, World!
```

## Notes

- The app runs in debug mode by default.
- To stop the server, press `Ctrl + C` in the terminal.
